# Running DSECOP Modules with Google Colab

## Opening a Module in Google Colab
At the top of every notebook in the DSECOP GitHub repository is a small icon which says "Open in Colab". Clicking this link opens the notebook in Google Colab and allows you to edit the notebook and execute the code.

![Colab Symbol](https://github.com/butler-julie/TheProfessorsModule/blob/main/Colab%20symbol.png?raw=true)

However, note that the notebook is currently in "Playground" mode. You can edit the notebook and run the code, but none of your changes will be saved. To save the changes you need to create a copy of the notebook in your Google Drive. There is a button in the top toolbar called "Copy to Drive", which will create a copy of the  notebook in your Google Drive account that you can edit and save your changes. Note that this requires you to have a Google Drive account and thus a Gmail address. If your school email does not have an attached Google account then you can make a Gmail account for free.

Once you click the button you should get a pop-up to open the copy in a new tab. This copy can now be edited, changed, and saved to your Google Drive account and moved around your Google Drive account just like any other file.

The below video walks you through the process of taking a modules from the DSECOP GitHub website and creating an editable copy which will save your work on your Google Drive account.

![Opening Module In Google Colab](DSECOP_Colab.mp4)

## Porting the Data to Your Google Drive Account

Most of the modules come with a data file that is needed by the notebooks. For example, the Introduction to Data Science Libraries module has one data file, nuclear_data.tsv, which is used in the module's notebook. This file needs to be downloaded from GitHub and then uploaded to your Google Drive account in order be used by the Colab notebook.

To download a single data file from GitHub, the easiest way is to click on the data file in the GitHub file explorer (described on the GitHub page of this website), and use the three dots menu at the top of the data file preview to download the file, shown in the below image.

![Download Data File](https://github.com/butler-julie/TheProfessorsModule/blob/main/DownloadDataFile.png?raw=true)

Once the data file is downloaded you can upload it to Google Drive using the "New" button in the top left corner and the "File upload" option. In the Colab notebook you will have to change a code cell to tell the notebook where to find the data file. For example, in the Introduction to Data Science Libraries notebook, the code to change to find the data file looks like this.

![Data File Location](https://github.com/butler-julie/TheProfessorsModule/blob/main/ColabImports.png?raw=true)

As it is currently written, the code looks for the data file in the main Google Drive folder (/content/gdrive/My Drive/), which is the folder your see first when you go to [Google Drive](https://drive.google.com/drive/u/0/my-drive). If you placed the data file in a sub-folder, you can edit this line of code by adding the names of the sub-folder(s) after the last /. Thus the code could become:

```python
data_dir = '/content/gdrive/My Drive/SubFolder1/SubFolder2/'
```

The below video walks through the process of downloading the data file from GitHub, uploading it to Drive, and changing the Colab notebook to reflect where the data file is located.

![Uploading a Data File](DataFile.mp4)

## Distributing the Module to Students

In terms of distributing the modules to students, there are to main options. First, the DSECOP GitHub page is publically avaliable. You could direct students to the specific module you wish to implement and give the students directions similar to the ones provided on this website in order to get the modules running on their Google accounts. This method works well if you wish to run the module as is with no changes. 

Alternatively, once you have the module on your Google account you can use Google's link sharing system to provide a link to students. Clicking the "Share" button in the upper right corner of the Colab screen will bring up a pop-up with link sharing options. First, you need to change access from "Restricted" to "Anyone with the link" so you do not have to individually share the notebook with every student.

![Colab Share Menu 1](https://github.com/butler-julie/TheProfessorsModule/blob/main/Google%20Share%201.png?raw=true)

Next, you want to make sure the access level is set to "Viewer" so the students cannot change your copy of the notebook. This is the default but its good to make sure.

![Colab Share Menu 2](https://github.com/butler-julie/TheProfessorsModule/blob/main/Google%20Share%202.png?raw=true)

Students can then create a copy of the notebook in their own Google Drive account to edit. The data files can be distributed through email, a virtual classroom management system, or through Google link sharing as well. This method of sharing works well if you want to change the modules to better reflect your class and learning goals.