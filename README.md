# PythonQuestionDB

## File structure

questions/XXXX/YYYY/ZZ.json

where:
XXXX - subject id
YYYY - question id
ZZ - language in country ISO code

## Question (JSON) structure

M - Mandatory
O - Optional

```json
{
    "qid": "M str - unique - 8 digit subject id + question id",
    "language": "M str - country ISO code",
    "type": "M one of predefined type bool/abcd/open",
    "question": "M str",
    "expected_answare": "M str",
    "answare": "O list of answares for abcd type",
    "img": "O bool",
    "code_in_file": "O bool"
}
```

Example:

```json
{
    "qid": "00010000",
    "language": "en",
    "type": "open",
    "question": "Whats the default file extension for python files",
    "expected_answare": ".py"
}
```


## Folder to subject

0000. Warm up questions
0001. Python
0002. Basic Syntax
0003. Variable Types
0004. Basic Operators
0005. Decision Making
0006. Loops
0007. Numbers
0008. Strings
0009. Lists
0010. Tuples
0011. Dictionary
0012. Date & Time
0013. Functions
0014. Modules
0015. Files I/O
0016. Exceptions
0017. Classes/Objects
0018. Reg Expressions
0019. Database Access
0020. Networking
0021. Sending Email
0022. Multithreading
0023. XML Processing
0024. GUI Programming
0025. Introduction
0026. Built-in Functions
0027. Binary Data Services
0028. Data Types
0029. Numeric and Mathematical Modules
0030. Functional Programming Modules
0031. File and Directory Access
0032. Data Persistence
0033. Data Compression and Archiving
0034. File Formats
0035. Cryptographic Services
0036. Generic Operating System Services
0037. Concurrent Execution
0038. Interprocess Communication and Networking
0039. Internet Data Handling
0040. Structured Markup Processing Tools
0041. Internet Protocols and Support
0042. Multimedia Services
0043. Internationalization
0044. Program Frameworks
0045. Development Tools
0046. Debugging and Profiling
0047. Software Packaging and Distribution
0048. Python Runtime Services
0049. Custom Python Interpreters
0050. Importing Modules
0051. Python Language Services
0052. Miscellaneous Services
0053. MS Windows Specific Services
0054. Unix Specific Services
0055. Superseded Modules
0056. Undocumented Modules