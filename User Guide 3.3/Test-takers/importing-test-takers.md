<!--
created_at: 2016-12-15
authors:         
    - "Catherine Pease"
--> 

# Importing Test-takers

>[Test-taker](../appendix/glossary.md#test-taker) metadata files can be taken from any computer and imported onto any other computer which also has access to TAO. This is done using an operation called *Import*.


**1.**  Click on the Test-takers icon on the [Assessment Builder Bar](../appendix/glossary.md#assessment-builder-bar).

This will take you to the [Test-taker Library](../appendix/glossary.md#test-taker-library), which you will see on the left.

**2.**  Click on the Test-taker class (folder) in the library in which you wish to import the new test-taker profile.

**3.**  Click on *Import* in the button bank below the library.

This opens a dialog box which asks you to select the format of the incoming test-taker metadata. The supported formats are RDF (Resource Description Framework) or CSV (Comma-Separated Values).  

![Importing Test-takers](../resources/backend/test-takers/import-3.png)

**4.** Click the blue *Browse* button to find the file intended for import (alternatively, the file may be dragged and dropped into the box below the button).

**5.** Once the file is selected, click on the blue *Import* button if importing an RDF. If you are importing a CSV file, click on the blue *Next* button.

![Selecting CSV](../resources/backend/test-takers/import1tt.png)

When importing a CSV file, you will need to map the properties to the CSV columns. If you don’t have a Language column in your CSV file, you can choose a default value for the interface language for all test-takers by choosing a language in *Define the default values Interface Language*. Then click on the blue *Import* button.

![Mapping Columns](../resources/backend/test-takers/import2tt.png)

This will import the test-taker's profile into the test-taker library, after which he can receive [Tests](../deliveries/create-a-new-delivery.md).

## Structure of a CSV File

By default, the CSV file should have the following structure:

Value separator: Semicolon
Row separator: Newline

```
label;First Name;Last Name;Interface Language;Login;Mail;password;Group
TAO Erica;Erica;Last;http://www.tao.lu/Ontologies/TAO.rdf#Langen-US;qwerty4700;Laste@example.lu;123456789@Qq;https://abc.local/tao.rdf#i15677754915441105
TAO Lenny;Lenny;Name;http://www.tao.lu/Ontologies/TAO.rdf#Langen-US;qwerty5600;Name@example.lu;123456789@Qq;https://abc.local/tao.rdf#i15677754915070106

```

In this example, we have seven columns. The first line is the header, and the following lines are values.

The required columns are:

- **Label**: a label for the test-taker (this value is used by the BackOffice).
- **Login**: the login of the test-taker
- **Password**: the password of the test-taker
- **Group**: the ID of the group

Additional columns are:

- **Interface Language**: A language of interface of test-taker. If this column does not exist, then you should choose a default language during the import process. 
- **Mail**: the email of the test-taker
- **First Name/Last Name**: the first and last names of the test-taker.
