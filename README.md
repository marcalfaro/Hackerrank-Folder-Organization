# Hackerrank-Folder-Organization

**Hacker Rank Coding Challenge: Folder Organization**

A web development project is being organized into several folders, and there are three rules that need to be followed:

1. Only one README file is allowed in each folder, and it cannot be the only file in the folder.
2. The number of CSS files and JS files can only exceed the number of the other file type by at most 1.
3. Only a certain number of files are allowed in each folder.

Given the types of files and the folder capacity, what is the minimum number of folders needed to organize the project?

For example, let's say cssFiles = 2, jsFiles = 1, and readMeFiles = 2.
The number of files in each folder cannot exceed capacity = 2. 
In this case, you would need a minimum of 3 folders. 
One possible solution is such: 1 CSS file and 1 README file, 1 CSS file and 1 README file, and 1 JS file. Therefore, the answer is 3.

Note: It is guaranteed that the answer always exists.

**Test Case 1:**
cssFiles: 1 | jsFiles: 1 | readMeFiles: 0 | capacity: 1
Expected Output: 2

**Test Case 2:**
cssFiles: 5 | jsFiles: 0 | readMeFiles: 2 | capacity: 2
Expected Output: 5

**Test Case 3:**
cssFiles: 0 | jsFiles: 13 | readMeFiles: 7 | capacity: 5
Expected Output: 13

**Test Case 4:**
cssFiles: 135 | jsFiles: 88 | readMeFiles: 127 | capacity: 5
Expected Output: 126
