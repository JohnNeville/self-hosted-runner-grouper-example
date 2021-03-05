﻿# Self Hosted Runner Grouper Example
 
I used this example with a trial organization and it produced the correct results. 
 
## Organiztion Actions Self Hosted Runner Groups
Running the action manually using a workflow trigger produced the correct groups and added them if they didn't exist before. 

In order to test the `should-overwrite: false` option I manually added a few extra runners to the managed `test2-case-test` group and ensured they didn't removed. 

![Organization's Action Self Hosted Runner Groups after executing workflow](https://user-images.githubusercontent.com/11984108/110139868-80db6280-7da1-11eb-8505-dbbd13bcabf8.png)

### Test Run Repos Setup
For reference these are the repos that existed when the test was peformed:
![Organization's Repos during test run](https://user-images.githubusercontent.com/11984108/110139540-23dfac80-7da1-11eb-9adb-b5d2363ab2d6.png)

### Test Debug Logs
Turning on debug logging showcases some of the underlying logic it is doing:
![Github Actions debug logs](https://user-images.githubusercontent.com/11984108/110139905-89cc3400-7da1-11eb-8b0c-54096732da5b.png)
