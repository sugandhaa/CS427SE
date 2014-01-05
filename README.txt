MP1.1 - Gooseberry Group
---------------------------------------------------------------------------------

This project is a library management system with book addition and removal capabilities.
For now, it does not have a user interface and can be accessed only through method calls.
The project has a single library containing one or more collections and/or books. Collections can further contain sub-collections or books.
XStream library has been used to serialize and deserialize objects, to be able to save the library to a file.
---------------------------------------------------------------------------------

Assumptions:

1. File to which the library is being written is updatable (not read-only).
2. A book can belong only to one collection.
3. Book names and collection names are unique.
4. A book is identified by a title and an author. Only one copy of any book is assumed to exist in the library.A book is assumed to have only a single author.
5. Any collection can belong to only one parent collection.
6. TestScenario8() in BookTest.Java must be run knowing that there already is a saved library and its name is known.
---------------------------------------------------------------------------------

Unit Testing Steps:

1. Import the project into eclipse from the following location: 
https://subversion.ews.illinois.edu/svn/fa12-cs427/_projects/Gooseberry/MP1/tags/MP1-1.1
2. Install a JUnit plug-in for eclipse
3. Under the folder test -> edu.illinois.cs427.mp1, right click on BookTest.java, select Run As -> JUnit Test.
Alternatively, expand the BookTest.java class and execute individual test methods as JUnit tests.
4. A green bar indicates successful execution of the test, whereas a red bar indicates error.
