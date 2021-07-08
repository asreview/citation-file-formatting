# Citation File Formatting
A collection of documentation highlighting quirks around the file formatting for citation and reference managers.

## Table of Contents
* [Introduction](#introduction)
* [Usage](#usage)
  * [File Formats](#file-formats)
  * [Citation and Reference Managers](#citation-and-reference-managers)
  * [Search Engines](#search-engines)
  * [Systematic Review Software](#systematic-review-software)
* [Compatibility](#compatibility)
  * [Supported Formats Per Software](#supported-formats-per-software)
  * [Systematic Review Workflow (Example)](#systematic-review-workflow-(example))
* [Contributing](#contributing)
* [Credits](#credits)
* [License](#license)

## Introduction
There are many software solutions and tools that allow you to manage your scientific work. Often times, you need to use multiple solutions to cover your whole workflow. This is where things get interesting but also confusing. Some tools just do not work well with others.

In this open repository, we have tried to simplify the process of setting up a scientific workflow for research. We have described the interrelations between popular citation and reference managers, search engines and systematic review software. Additionally, we have gathered [relevant datasets](Datasets/) to show capabilities of each tool more specifically.

## Usage
This project is meant to serve as a guide in the field of scientific research, namely dealing with systematic reviews and related software solutions. Or you can check it out for inspiration and learning about said software!

### File Formats
Below, most commonly used file formats in dealing with systematic review are described.

#### CSV
A comma-separated values (CSV) file is a delimited text file that uses a comma to separate values. Each line of the file is a data record. Each record consists of one or more fields, separated by commas. The use of the comma as a field separator is the source of the name for this file format. A CSV file typically stores tabular data (numbers and text) in plain text, in which case each line will have the same number of fields.

*The CSV file format is not fully standardized.*

Learn more about [CSV at Wikipedia](https://en.wikipedia.org/wiki/Comma-separated_values).

#### RIS
RIS is a standardized tag format developed by Research Information Systems, Incorporated (the format name refers to the company) to enable citation programs to exchange data. The RIS file format — two letters, two spaces and a hyphen — is a tagged format for expressing bibliographic citations. According to the specifications, the lines must end with the ASCII carriage return and line feed characters. Multiple citation records can be present in a single RIS file. A record ends with an "end record" tag ER - with no additional blank lines between records.

*The RIS file format is standardized but sometimes improperly implemented.*

Learn more about [RIS at Wikipedia](https://en.wikipedia.org/wiki/RIS_(file_format)).

#### TSV
A tab-separated values (TSV) file is a simple text format for storing data in a tabular structure, e.g., a database table or spreadsheet data, and a way of exchanging information between databases. Each record in the table is one line of the text file. Each field value of a record is separated from the next by a tab character. The TSV format is thus a type of the more general delimiter-separated values format.
TSV is an alternative to the common comma-separated values (CSV) format, which often causes difficulties because of the need to escape commas – literal commas are very common in text data, but literal tab stops are infrequent in running text. The IANA standard for TSV achieves simplicity by simply disallowing tabs within fields.

*The TSV file format is not fully standardized.*

Learn more about [TSV at Wikipedia](https://en.wikipedia.org/wiki/Tab-separated_values).

#### XLSX
The Office Open XML Workbook (XLSX) file is part of a set of file formats that can be used to represent electronic office documents. While this specific format is dedicated to spreadsheets, there are other formats dedicated for word processing documents, presentations as well as specific formats for material such as mathematical formulae, graphics, bibliographies etc.

*The XLSX file format is standardized.*

Learn more about [XLSX at Wikipedia](https://en.wikipedia.org/wiki/Office_Open_XML).

### Citation and Reference Managers
Below, most commonly used citation and reference managers are listed.
- [Citavi](https://www.citavi.com/en)
- [Endnote](https://endnote.com)
- [Mendeley](https://www.mendeley.com)
- [Refworks](https://www.refworks.com/)
- [Zotero](https://www.zotero.org)

### Search Engines
Below, most commonly used search engines are listed.
- [CINAHL Database](https://guides.library.uab.edu/CINAHL)
- [Cochrane](https://www.cochrane.org/search/)
- [Embase](https://www.embase.com)
- [Google Scholar](https://scholar.google.com)
- [Google Scholar Button for Chrome](https://chrome.google.com/webstore/detail/google-scholar-button/ldipcbpaocekfooobnbcddclnhejkcpn)
- [ERIC Ovid®](https://www.wolterskluwer.com/en/solutions/ovid/85)
- [Psycinfo Ovid®](https://www.wolterskluwer.com/en/solutions/ovid/139)
- [Pubmed](https://pubmed.ncbi.nlm.nih.gov)
- [ResearchGate](https://researcgate.net)
- [Scopus](https://www.scopusjournals.com)
- [Web of Science](https://apps.webofknowledge.com/)

### Systematic Review software
Below, most commonly used search engines are listed.
- [abstrackr](http://abstrackr.cebm.brown.edu/account/login)
- [ASReview](https://asreview.nl)
- [Covidence](https://www.covidence.org)
- [DistillerSR](https://www.evidencepartners.com/products/distillersr-systematic-review-software)
- [Eppi-Reviewer](http://eppi.ioe.ac.uk/cms/Default.aspx?alias=eppi.ioe.ac.uk/cms/er4)
- [Rayyan](https://www.rayyan.ai)
- [RobotReviewer](https://www.robotreviewer.net)

Describe the relations between formats and software.
Describe open/closed source?

### Compatibility
Below, the software and tools have been described from the user's perspective, namely concerning the whole workflow of systematic review. This workflow usually consists of using multiple solutions and tools which have to work together but often do not or do barely so. The compatibility matrices should give you a better idea what works and what doesn't.

#### Supported Formats Per Software
Below, you can find a table outlining import/export capabilities of previously described software. Namely, different file formats commonly used within the field of scientific referencing are described.

Guide for using the table:
* Search for the software (e.g **ASReview**) you are interested in;
* Follow the line, until you find the file format(e.g **.ris**) you are interested in;
* Within the file format field, *Import from ...* is indicated on the left side, *Export to ...* on the right side;
* :green_square: indicates success and :red_square: indicates failure;

> Example: :green_square::red_square:
> 
> Meaning: Software can import from but not export to the given file format.

 | Software                | **.ris**  | **.tsv** | **.csv** | **.xlsx**|
 | --- | --- | --- | --- | --- |
 |                         |           |          |          |          |
 | **ASReview**\*          | :red_square: | :green_square: | :green_square: | :green_square: |
 | **Abstrackr**           | :green_square::red_square:   | :green_square::green_square: | :green_square::red_square:   | :green_square::red_square:   |
 | **Covidence**\*         | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: |
 | **Distiller**           | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: |
 |**EPPI-reviewer**        | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: |
 | **Rayyan**              | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: |
 |**Robotreviewer**        | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: |
 |**Swift Active Screener**| :green_square::green_square: | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: |
 |**Sysrev**               | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: |
 |**SR accelerator**       | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: | :green_square::green_square: |

#### Systematic Review Workflow (Example)
Below, an example workflow pipeline has been described from the perspective of ASRevie

 | Input From ... | >   | >   | >   | >    | ASReview | >   | >   | >   | >    | Output To ...|
 |                | CSV | RIS | TSV | XLSX |          | CSV | RIS | TSV | XLSX |              |
 | --- | --- | --- | --- | ---  | --- | --- | --- | --- | ---  | --- |
 | Endnote        |:green_square:|:green_square:|:green_square:|:green_square:|:gray_circle:|:green_square:|:gray_square:|:green_square:|:green_square:| Endnote |

## Contributing
Details are described in the [contributing guide](https://github.com/asreview/citation-file-formatting/blob/main/CONTRIBUTING.md).

## Credits
//Include a section for credits in order to highlight and link to the authors of your project.//

## License
//Finally, include a section for the license of your project. For more information on choosing a license, check out GitHub’s licensing guide!//
