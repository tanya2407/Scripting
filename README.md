# Scripting
Basic scripting commands for reference


#### 'cat' command
- cat stands for concatenate
1. Display contents of a file: ```cat /development/project1 ```
2. Display contents of multiple files: ```cat project1 project1```
3. Create a file: ```cat >project1 ``` (ctrl+d to exit)


#### 'cut' command
- used to select portions of text from each line of a file
1. To get columns n to m: ```cat project.csv | cut -c n-m ```
2. Get the first field by mentioning the delimiter: ```cat project.csv | cut -d ',' -f 1 ```
