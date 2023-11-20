[Back to Portfolio](./)

HTML Parser and Crawler
===============

-   **Class:** CSCI 315
-   **Grade:** D
-   **Language(s):** C++
-   **Source Code Repository:** [WalkerPoston/CSCI-315-Project-2](https://github.com/WalkerPoston/CSCI-315-Project-2)  
    (Please [email me](mailto:walkerposton@gmail.com?subject=GitHub%20Access) to request access.)

## Project description

This project reads HTML files line by line and parses out the input in order to determine if the file is balanced, meaning every opening tag has a closing tag and that those tags are in the correct HTML file structure. Once the files have been parsed, the program will then determine the number of unique pages that can be visited from a certain page.

## How to compile and run the project

How to compile and run the project with all files.

```
make run
```

How to run individual files.

```
./html-test pages/file-name.html
```


## UI Design

Once the program is executed, the results will be displayed on the screen (see Fig 1). You will see in the output that the program parsed all of the files that were included in the code. Then, below that, there will be a table with three columns that have the page, whether the page is balanced, and the number of pages that can be visited from that page. Figure 2 is an example of the program running with only two files as input.

![screenshot](images/Project2-AllFiles.png)  
Fig 1. Program output with all files as input

![screenshot](images/Project2-2Files.png)  
Fig 2. Program output with two files as input

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
