Homework Assignments
=================================================

These are the required template and test code for programming homework assignments in CS 212 Software Development at the University of San Francisco. Please note that the exact homework assigned may differ by semester.

## Spring 2014 ##

These are the assignments for Spring 2014. Please see the specific assignment for template code, test code, and any necessary input files. See below for general requirements and submission instructions.

| Homework ## | Homework Name                   | Deadline             |
|-------------|---------------------------------|:---------------------|
| Homework 01 | [Project Euler](ProjectEuler/)  | Fri Jan 31 @ 11:59pm |
| Homework 02 | [Word Parser](WordParser/)      | Fri Feb 07 @ 11:59pm |
| Homework 03 | Argument Parser                 | Fri Feb 14 @ 11:59pm |
| Homework 04 | Pending                         | Fri Feb 21 @ 11:59pm |
| Homework 05 | Pending                         | Fri Feb 28 @ 11:59pm |
| Homework 06 | Pending                         | Fri Mar 07 @ 11:59pm |
| Homework 07 | Custom Lock                     | Fri Mar 28 @ 11:59pm |
| Homework 08 | HREF Parser                     | Fri Apr 04 @ 11:59pm |
| Homework 09 | HTML Cleaner                    | Fri Apr 11 @ 11:59pm |
| Homework 10 | HTML Fetcher                    | Fri Apr 18 @ 11:59pm |

The deadlines may be out of date. Check the course website for the most recent information. In general, all homework is due the following Friday that it was assigned at 11:59pm. No late homework is accepted!

## Requirements ##

Fill in any method with the `// TODO` comment. Please remove the `// TODO` comments once you are finished filling in the missing code. When completing this homework, you may modify the following:

- You may modify any code within the `// TODO` methods, including the `return` statement.

- You may modify any code provided within the `main()` function for debugging.

- You may add additional members and methods as necessary.

However, you may **NOT** modify the following:

- Do **not** modify the name, parameters, or exceptions thrown for any of the provided methods (including the ones you must fill in).

- Do **not** modify the code for any of the fully provided methods.

- Do **not** modify the provided unit tests, including the exceptions expected or not expected by those unit tests.

You must pass all of the provided unit tests and pass code inspection by the teacher assistant to receive full credit on this homework assignment.

## Download ##

You may download any individual file by opening that file in GitHub, clicking the "Raw" button, and saving the file from your browser. You may also follow the steps in the [GitHub Help Guide](https://help.github.com/articles/downloading-files-from-the-command-line) for downloading individual files.

Alternatively, you may use the `svn export` command to download all of the required homework files in a subdirectory. Use the following command:

```
svn export https://github.com/cs212/homework/trunk/subdirectory
```

where `subdirectory` is the homework directory you wish to download. For example, the following will download all of the files for the [Project Euler](ProjectEuler/) assignment:

```
svn export https://github.com/cs212/homework/trunk/ProjectEuler
```

Please see the [CS Tutoring Center Resources](http://tutoringcenter.cs.usfca.edu/resources/) for help using SVN via the command-line.

## Submission ##

Submit your work to SVN at the following location:

```
https://www.cs.usfca.edu/svn/username/cs212/homework##/
```

where `username` is your CS username and `##` is the homework number you are submitting. If you submit correctly using Eclipse, your source files will be located in the `src` subdirectory.

For example, suppose username `sjengle` is submitting [Project Euler](ProjectEuler/) as Homework 01. Then the source code files should be located at:

```
https://www.cs.usfca.edu/svn/sjengle/cs212/homework01/src/ProjectEuler06.java
https://www.cs.usfca.edu/svn/sjengle/cs212/homework01/src/ProjectEuler06Test.java
```

We use scripts to test homework, so your SVN repository must follow the above guidelines exactly. Failure to submit your homework properly may result in a 0% score.
