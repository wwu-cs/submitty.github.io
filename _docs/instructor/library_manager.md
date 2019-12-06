---
title: Library Manager
category: Instructor
---

![](/images/library_manager_upload.png)

### Manage Your Homework Library

In the library management page, new gradeables can be uploaded 
by means of a .zip file or from a Git repo. To access this page, 
the user should choose the "Homework Library" button from the 
left sidebar of the Submitty homepage. 

![](/images/library_manager_submitty_homepage.png)

_NOTE: This is a feature reserved for users with admin priveleges._

### Uploading Gradeables

There are two ways of uploading new gradeables in the homework 
library manager: by .zip file or by Git repo.

**_Upload by Zip File:_** To upload a gradeable through a zipped 
file, the "Upload" tab should first be selected.  
    
When uploading using a .zip file, the gradeable should be inside 
of a folder, and that folder should be located in the root directory 
of the zipped file. The uploader identifies the details of a gradeable 
by means of a config json. An example file structure can be seen on
the upload page. Multiple gradeables can be included inside one 
upload, as long as it doesn't exceed the maximum upload size of 
10MB.

**_Upload by Git Repository:_** When the "Git" tab is selected, 
there will be a text box where a Git repo URL can be specified, 
as well as a field for specifying what you would like the source 
to be named. Leaving this name field blank will cause the source 
to have the same name as the Git repo. Hitting "Submit" will then 
pull the repo and any gradeables within to the library.

### Existing Source Management

![](/images/library_manager_viewall.png)

The "View All" tab is for managing previously uploaded gradeables, 
and is selected by default when the library manager is opened. From
here, a list of previously uploaded sources can be seen, along with
the option to refresh or delete each source. The View All page as well
as an example source can be seen in the image above.

Choosing "Delete" will remove the source from the library. Choosing 
"Refresh" for a source uploaded from a Git repo will pull any changes 
from the repo that was originally used to add the source. Note that the
Refresh button will not work for sources uploaded by means of a .zip 
file, and will generate an error.