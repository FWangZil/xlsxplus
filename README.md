# xlsxPlus A go extension library that can handle both xls and xlsx

## Project Introduction

At work, I often encounter some businesses that need to process Excel files, such as common data import and export. Although the common Excel files are basically in xlsx format, but because of some historical issues or the office/wps used by the docking client Because of the version, I occasionally encounter situations that require handling xls. But at present, there does not seem to be a go library that can process files in both formats at the same time.

When I encountered this situation in the previous development process, I often needed to write two sets of business logic at the same time to call different Excel processing libraries to adapt to different file formats, which naturally introduced excessively high maintenance for the project later. The complexity, so I thought if I could try to be compatible with the old and new formats under some simple logic based on the achievements of my predecessors, so I tried this project.

The project starts at
tealeg/xlsx [https://github.com/tealeg/xlsx] v3.2.0
extrame/xls [https://github.com/extrame/xls] 6fdb969 8fb5669

## Version maintenance history

## function points

## Note

This project does not guarantee the stability of the production environment. It is just an attempt. My ability is limited. Please pass by cautiously.
