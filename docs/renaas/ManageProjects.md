 ![Logo EZ2Cloud](../images/ez2cloud2.png)
<hr>

## Projects
<div style='text-align: justify;'> 
<p>
Click the menu option <img src="./images/Projects/menuProject.png"> to access the Manage Projects Window. As depicted in the image where you can find all funcionalities that allows to manage and access projects configuration settings and project file structure meta data.
<img src="./images/Projects/ProjectsOverview.png">
Located in the upper area of the window you will find button that triggers the label managment actions. Also a table with the labels showed in the select language. Each line at this table is a label where is indicated:
</p>
</div>

## Configure Projects
<div style='text-align: justify;'> 
<p>
As shown above, projects are presented in two different groups. The running projects are in fact those that are being used as a work base. On the other hand projects whose work on them is finished are in Archived Projects. The configuration of a project is therefore done to define everything that is required to have a project that can be opened in File Explorer.
</p>
</div>

1. **Add Project**  <p>Click button <img style="border: 1px solid black" src="../images/admin/projects/AddIcon.png"> to create and set a new project. After that a modal window is displayed as depicted in the following image <img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="../images/admin/projects/NewProject0.svg"></p><p>The data required to create a new project are:
      * Project Name - project identification that must be a unique string of alphabetic characters and possible numbers. 
      * Local Network Path - Path to the Shared Network folder in a on-premise server which the content is bouded with the project
      * Internal user - If need, defined a user to authenticate and gain access to the Shared network folder indicated in Local Network Path
      * Internal password -If need, the password for the previous indicated user 
      * Project description - A paragraph to describe the project. 
      * End date - estimated date for completion of work on the project
      * End date alert - indicates how many days before the end date the notification of the end of the project must be presented.
      * Sattelite Server - Which Sattelite Server will be used to connect to Ez2Cloud.</p>

2. **Define Semantic Labels** <p> After filling the fields you can click Save button and the project will be created. Yet it will not be ready to be used in the Colaborative Work area because it is not full defined. To complete the definition it is required to Assign the Semantic and Ownership labels for the projects.</p><p>These are the tags available in the Collaborative working area and are set by click in plus sign after Assign Label or Assign Users. <img style="margin-top: 10p; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/Projects/FilledProject.png">The previous image depicted a project being created. In order to define the Semantic Labels click the plus sign icon after Assign Labels. The windown will be extended showing where to select the Semantic Label as depicted next. To assign a label just drag and drop from the label list on left to the defined label area. Colapse the window extended part by click the minus icon. 
<img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/Projects/AssignLabel.png"></p>

3. **Define Ownership Labels** <p>In order to define the Ownership Labels:  
    + click the plus sign icon after Assign Users. 
    + The windown will be extended showing where to select the Ownership labels as depicted next. 
    + Drag and drop from the label list on left to the defined label area. 
    + Colapse the window extended part by click the minus icon. 
<img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/Projects/AssignUsers.png"></p>

4. **Edit Project** <p>Click button <img style="border: 1px solid black" src="../images/admin/projects/EditIcon.png"> to edit an existing project. A modal window is displayed as depicted in the following image <img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/Projects/editProject.png">. Here you can change the fiedls description, End date, End date Alert and Sattelite Server. It's not possible to change the fields Local Network Path if the Project has not yet a connection with a on-premise Sattelite Server active.   
  
5.  **Archive Project**  <p>From the project table select rows that represents the project you want to disable and then click button <img src="../images/admin/projects/ArchiveIcon.png">. You will see the following dialog prompting to confirm where you must click the button Archive button to confirm. If you select multiple projects the confirmation dialog will be show  <img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/Projects/ArchiveProjects.png"></p>

## Projects in Ez2Cloud
<div style='text-align: justify;'> 
<p>
There is a set of data that result from the work carried out on the projects. In other words, the projects are being used in the collaborative workspace and there will be access to the project content or metadata of the shared folder linked to the project. Also for analysys and troubleshooting it is possible to access to the log data.
</p>
</div>

1. Project Content - At the project table, go to line corresponding to the project click <img src="./images/Projects/exploreFiles.png"> link  in the column File Structure. On click the link a new window will open displaying the EZ2Cloud Colaborative workspace with the project content as the example in the following image shows <img style="margin-top: 10px; margin-bottom: 10px; padding: 10px;" src="./images/Projects/FileStructure2.png">
2. Reports - in the line corresponding to the project click <img src="./images/Projects/ShowLogs.png"> link in the column Reports.




