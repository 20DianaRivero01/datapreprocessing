Diana Rivero

D3B
___ 
# DATA IMPORTANT RESUME

## Describing concepts

#### Data table concept
Data is complex, and all data is different. DataTables has a wealth of options which can be used to configure how it will obtain the data to display in the table, and how it processes that data.

#### Data types
  * **Categorial**:

Categorical data is a collection of information that is divided into groups. I.e, if an organisation or agency is trying to get a biodata of its employees, the                    resulting data is referred to as categorical. This data is called categorical because it may be grouped according to the variables present in the biodata                         such as sex, state of residence, etc.
Categorical data can take on numerical values (such as “1” indicating Yes and “2” indicating No), but those numbers don’t have mathematical meaning. One can                    neither add them together nor subtract them from each other.

* **Numerical**:

Numerical data is a data type expressed in numbers, rather than natural language description. Sometimes called quantitative data,numerical data is always                         collected in number form. Numerical data differentiates itself with other number form data types with its ability to carry out arithmetic operations with                     these numbers.

* **Boolean**: 

BOOLEAN can be used as a data type when defining a column in a table or a variable in a database procedure. Support for the BOOLEAN data type helps migrations                   from other database products.
Boolean columns accept as input the SQL literals FALSE and TRUE. In addition, due to automatic coercion rules, the strings 'FALSE' and 'TRUE' and the integers 0                 and 1 are also acceptable for use in a Boolean column or variable. Input is not case sensitive.
The IS Boolean operator can be used in expressions. IS TRUE is true for a BOOLEAN TRUE, IS FALSE is true for a BOOLEAN FALSE, IS UNKNOWN is true for an Unknown                   (NULL) value. IS UNKNOWN is a synonym for IS NULL when dealing with Boolean values.
order by boolean results in grouping rows in this order: FALSE, TRUE, NULL.
The CREATE INDEX statement allows an index to be created on BOOLEAN columns.
Terminal Monitor output for a BOOLEAN column shows the literals FALSE and TRUE as unquoted strings

### Common data 
* **CSV**: 

CSV (comma separated values) files are used to store tabular data in plain text format. Most often the fields in this data are separated by commas but                           other delimiters can be used such as |. TSV (tab separated values) files are similar but breaks are delimited by tabs. Both formats are widely supported                         and are often used to exchange data across multiple different computers and systems that support the format.
Most modern spreadsheet packages can open CSV/TSV files for viewing. To maintain formatting data you will want to save in a proprietary format like XLS                            (Microsoft Office Excel), ODS (Open Office spreadsheets) or .numbers (Apple Mac), depending on the software you use. A free tool for viewing csv and                              other spreadsheet formats online can be found here.

* **Json** : 

Json (javascript object notation) files are human-readable text files used to transport data in key/value pairs. It is a format widely used on the web and is often              the type of data returned from an API call.

*Whilst human readable, json is generally used by software as a data source. A useful free tool to view json in interesting ways can be found here.*

* **XML**: 

Extensible Markup Language (XML) is a markup language that defines a set of rules for encoding documents in a format that is both human-readable and machine-                     readable. The design goals of XML emphasize simplicity, generality, and usability across the Internet. Although the design of XML focuses on documents,                          the language is widely used for the representation of arbitrary data structures such as those used in web services.

*XML is generally more useful to developers and software systems. You can import them as tables into Excel or view using this free online tool.*

* **XLS**:

A file with the XLS file extension is a Microsoft Excel 97-2003 Worksheet file. Later versions of Excel save spreadsheet files in the XLSX format by default. XLS                 files store data in tables of rows and columns with support for formatted text, images, charts, and more.

**Open in Microsoft Excel. From there you can create charts, pivot tables and other formatting or visualisation tools. A free tool for viewing csv and other                       spreadsheet formats online can be found here.**


## Differentiate between local and remote repositories: url, apis.

A URL is like an address. It is used to identify a resource uniquely with the help of its location in a network of computers. Just like your house has an address which is unique and no other house in the world can have that address(unless there is a massive coincidence ), URL is the same in the Internet, hence the name Universal Resource Locator. It is used to locate a particular resource on the internet.__

Now comes the complex part, an API, is anything which helps you to write your code. It is nothing but a set of tools, which are already developed and can be used, so that you dont have to write the same code again. You can reuse the previously written code. In simple terms, imagine you have to cut meat and have a small vegetable knife. You friend on the other hand has a butchers knife. You can cut meat using your own knife but that will take a lot of time, so you use your friend’s butchers knife instead. This way you save time by not doing unnecessary things. So, anything you use thats developed by a third party, to ease your development, is called an API.__

## Secure File Transfer Protocol (SFTP).

Secure file transfer is data sharing via a secure, reliable delivery method. It is used to safeguard proprietary and personal data in transit and at rest. Most secure file sharing methods use standard protocols, including:

* **Secure File Transfer Protocol (SFTP)**: 

SFTP transfers files with the Secure Shell (SSH) connection – SFTP is an encrypted network protocol that can enable a remote login to operate over a network that lacks security. SFTP offers encryption of commands and data. It also prevents passwords and sensitive information from open transmission over the network.

* **File Transfer Protocol – Secure (FTPS)**: 

FTPS offers encryption and uses an application layer wrapper, known as Secure Sockets Layer (SSL) to enable secure and private communications across a network.

* **Hypertext Transfer Protocol – Secure (HTTPS)**: 

HTTPS secures websites when users are providing sensitive information like credit card numbers or other personal information. The protocol offers multiple layers of data protection including data integrity, encryption, and authentication.

* **Applicability Statement 2 (AS2)**:

AS2 is a standard used to transfer Electronic Data Interchange (EDI) messages and other data in real time. The AS2 protocol facilitates the ability to exchange AS2 EDI messages and other types of data over the HTTP or HTTPS protocol.

## Describe the procedures for data importing

Using the Define File-Based Data Import group of tasks that are available from the Setup and Maintenance work area, you can import a wide range of application data from text or XML files. Your import data can either create or update application records. 

Use the steps outlined in this topic as a guide. The import options and other details differ by the type of data that you're importing. Before importing, you must understand how the data in your file maps to the attributes in the application and what values are expected as described in the related topics.
