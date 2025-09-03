# Tips and Advice for Implementing the DSECOP Modules in the Physics Classroom

## Where to Implement Modules in a Course
Though the modules can be used as the student's first exposure to a concept, they work best to reinforce students' knowledge of physics while teaching them essential computational concepts from data science. The best place to insert a module into the course will depend on the course design, schedule, and professor, but below are a few recommendations:
* The modules (or parts of the modules) can be assigned as a homework assignment or part of a homework assignment, especially when new concepts are being introduced in a course, and the amount of content-specific homework is low.
* If you will be absent for a conference or other reason, then the modules could be done by students in place of class for the day(s) lecture will be missing.
* For courses with a lab component (general physics, modern physics, etc.), more extended modules could be completed in one entire lab period, and the shorter modules could be used in conjunction with a quick experiment to take the whole lab period. Some modules, such as the "Introduction to Data Science Libraries" module could be modified to work with data collected in the lab instead of the data supplied with the module.
* Finally, the modules could be used after exams to give students a brief break before learning more content. The shorter modules could be finished in 1-2 class periods or started in one class period and finished for homework.

## How to Implement Modules
The modules are meant to be self-contained, with coding exercises interspersed with text explanations and coding examples. Thus, the modules can be given to students without any accompanying lecture or explanation. However, these can be implemented as well if desired. Additionally, depending on the students's prior knowledge, it may be beneficial to provide either resources or a walkthrough on how to import the modules into Google Colab and how to use Google Colab.

## How to Distribute the Modules
As discussed earlier, the easiest way to distribute the modules to the students is to use Google's link-sharing system. When providing students with a link to a Google Colab notebook stored in your Google Drive account, ensure the access level is set to "Anyone with the link" and the link is for viewer only (not editor access). The link can then be emailed to students or posted on a classroom management system or course website. 

The data files can also be distributed similarly. However, there are two options for these files. You can use the data file uploaded on your Google Drive account with link sharing to distribute the file (right-clicking on any file on Google Drive will provide a link-sharing option). However, most data files are small and could be distributed via email or a classroom management system.

As a second option, you can give students the link to the module on the DSECOP GitHub repository and have them copy the notebooks into their Google Drive accounts and download the data files from there. This method works best if you want to use the modules unmodified but does not work if you're going to modify the modules to suit the needs of your students better.

## How to Have Students Turn in Modules
Depending on what you want to see, there are a few options for having students turn in their completed modules. The easiest method would be to have students submit a share link for their completed notebooks with editor access so you can run the code. This does mean that students could edit the files after submitting the links, but Google Colab does store its revision history (File then Revision history) so you can check and see when the last changes were made to the file. If students do not set the permissions appropriately however, then you will not be able to see their assignment until the permissions are changed.

Second, students can print and submit a PDF file of their notebooks. Note that the quality of this PDF is dependent on the aspect ratio of the students' devices, and these PDFs can sometimes have overlapping graphs and text. Setting the scale to 75% when printing sometimes fixes these issues, but know that if you want students to submit a PDF file, it may be hard to read parts of it.

Third, you can have students download their Google Colab notebook as a Jupyter notebook (File, Download as, .ipynb) and submit this file. However, the downside is that most classroom management systems will allow students to submit Jupyter notebooks, but you must download them to view them. This can increase the amount of time it takes to grade the modules.

Finally, you can create a worksheet for students to submit where they can answer questions about the code or data interpretation and attach the code they wrote and the graphs they have created. This can be submitted in person or through a classroom management system as a PDF. This may make grading the assignments easier as you can reduce a very long notebook to just a couple of pages of questions, code snippets, and graphs.
