# ReadingNotes-301

**you will see all Classes here**

*Table of content*
 
 Read      |  Link
 ----------|--------------
 read:01   |  [read:01](https://amalmalmomani.github.io/ReadingNotes-301/read-01)
 read:02   |  [read:02](https://amalmalmomani.github.io/ReadingNotes-301/read-02)
 read:03   |  [read:03](https://amalmalmomani.github.io/ReadingNotes-301/read-03)
 read:04   |  [read:04](https://amalmalmomani.github.io/ReadingNotes-301/read-04)
 read:05   |  [read:05](https://amalmalmomani.github.io/ReadingNotes-301/read-05)
 read:06   |  [read:06](https://amalmalmomani.github.io/ReadingNotes-301/read-06)
 read:07   |  [read:07](https://amalmalmomani.github.io/ReadingNotes-301/read-07)
 read:08   |  [read:08](https://amalmalmomani.github.io/ReadingNotes-301/read-08)
 read:09   |  [read:09](https://amalmalmomani.github.io/ReadingNotes-301/read-09)
 read:10   |  [read:10](https://amalmalmomani.github.io/ReadingNotes-301/read-10)
 read:11   |  [read:11](https://amalmalmomani.github.io/ReadingNotes-301/read-11)
 read:12   |  [read:12](https://amalmalmomani.github.io/ReadingNotes-301/read-12)
 read:13   |  [read:13](https://amalmalmomani.github.io/ReadingNotes-301/read-13)
 read:14   |  [read:14](https://amalmalmomani.github.io/ReadingNotes-301/read-14)
 read:15   |  [read:15](https://amalmalmomani.github.io/ReadingNotes-301/read-15)



  - 1. Why would you want to run JavaScript code outside of a browser?
       - Running JavaScript without/outside a browser means you are using node.js technology to execute your JavaScript code. This type of usage of javascript typically refers to backend programming where your javascript code will interact with your database and can be used to create RESTful APIs.

 - 2. What is the difference between a module and a package?
       - "Java platform module system" 
         - A module is a named, self-describing collection of code and data. Its code is organized as a set of packages containing types, Java classes and interfaces; its data includes resources and other kinds of static information
         - A Java package is a technique for organizing Java classes into namespaces similar to the modules of Modula, providing modular programming in Java.

 - 3. What does the node package manager do?
       - Adapt packages of code for your apps, or incorporate packages as they are.
       - Download standalone tools you can use right away.
       - Run packages without downloading using npx.
       - Share code with any npm user, anywhere.
       - Restrict code to specific developers.
       - Create Orgs (organizations) to coordinate package maintenance, coding, and developers.
       - Form virtual teams by using Orgs.
       - Manage multiple versions of code and code dependencies.
       - Update applications easily when underlying code is updated.
       - Discover multiple ways to solve the same puzzle.
       - Find other developers who are working on similar problems and projects.

 - 4. Provide code snippets showing 3 different ways to export a function from a node module
       - module.exports = {
    method: function() {},
    otherMethod: function() {},
};    - exports.method = function() {};
exports.otherMethod = function() {};
