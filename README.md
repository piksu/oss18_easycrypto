# README #

JEasyCrypto is a library and a collection of related applications enabling encryption and decryption of text using different methdods.

The code here has been created for educational purposes, and the apps (probably) have no other value for anyone.

*(c) Antti Juustila, Degree Program of Information Processing Science, University of Oulu, Finland.*

### License ###

For the purpose of this course, all code is licensed under GPLv3, unless otherwise stated in a file.

### What is this repository for? ###

Repository includes four components: 

* **JEasyCryptoLib** which implements several crypto methods and is extensible with new methods.
* **JEasyCryptoConsole**, a console app which enables using the cryptographic methods of the Lib
* **JEasyCryptoServer**, which provides a way to use the Lib from internet, using UDP and JSON.
* **JEasyCryptoClient**, which uses the Server over network for en-/decryption of text.

Additionally, the code uses the **json-simple** library (see below).

You can also run the Client and Server on the same machine. When launching the client, give "localhost" as the server address in this case.

### How do I get set up? ###

1. Clone the project from bitbucket.
    * Dependencies
        * Uses https://code.google.com/archive/p/json-simple/ on Server and Client to create/parse JSON.
        * Download the json-simple-1.1.1.jar to project root directory before building and running the Client or Server.
2. Build the lib using build.sh, which exports it as a .jar file into the project root directory.
    * If on Windows, port the shell scripts or use a shell that understands shell scripts
3. Then build the server and client, using corresponding build.sh files for each. 
4. Use the provided start.sh files to start the client and server. Use Client and Server for cryption. 
    * Run Server in one console window, and the Client in another.
5. For testing the Lib without network, you can use the Console without the overhead of networking between the Client and Server.


### Contribution guidelines ###
Push only files that belong to the project, no OS specific files
Commit message should be in imperative mode and descriptive. It should be no more then 54 characters
Test your changes before pushing
Update branch often
Work in your local branch (git checkout -b mylocal) and push to the latest version of master

### Coding guidlines ###

The code has issues and features to be done. In order for the best experience for us and you, we have a simple list of guidelines that have to be followed.

First of all, please, use only TABS, no spaces. You can turn on the view of tabs and spaces in your preferred IDE.

Nested loops should be have equivalent to where the code is, for example, if 4 tabs have been used and you need to add something inside the loop, add one more tab.

Only one variable per declaration, declarations such as int a, b are incorrect.

Variables are named with non-capital letters and must make sense.

If two or more words need to be combined into one variable name, start second variable without spacing with capital letter, for example, cryptoMatrix

For everything else, Google Java guideline is preferred that can be found here
http://google.github.io/styleguide/javaguide.html


### Who do I talk to? ###

* Antti Juustila
* firstname.lastname@oulu.fi

The contributor team can be contacted through Slack, Emails
