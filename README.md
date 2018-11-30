# JacocoHtmlTree
Generates jacoco reports with respect of subpackages.  
Android app directory is hardcoded in the current version in the task definition, but you can change the path approprietaly for you project or write it in a more flexible way.
# Instruction
1. Execute tests  
2. Generate Jacoco reports in XML **and** HTML formats 
3. Execute _renderHtmlTree_ gradle task. Change _JACOCO_REPORT_DIR_ constant in the task if required  
4. Gratulations! You can find the generated _index.html_ in the _htmlTree_ directory which is located next to Jacoco xml and html report directories.
