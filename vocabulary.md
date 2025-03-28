Here are the main terms used in this documentation and in the application.


| Term | Description
|---|---|
|Project|Actual unit of work, with a group of several client branches.|
|Client Branch|A cloned branch (in SCM way) of a given repository.|
|Version|A group of commits on a branch. For GIT type, versions are read from tags found on commits.|
|Repositories types|Different types of SCM. For now, Sunshine only handles GIT|
|Reference commit|Commit that was specifically set as reference because the user wants Sunshine to make sure it was reported on other branches|
|Reported commit|Commit identified as a report of a reference commit by Sunshine|