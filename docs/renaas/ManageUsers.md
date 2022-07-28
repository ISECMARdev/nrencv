 ![Logo EZ2Cloud](../images/ez2cloud2.png)
<hr>

## Users 

<div style='text-align: justify;'>
<p>User managment it is one of the mandatory configuration that is required as one of the primary task to be completed. Users account and their information will have a double perspective in EZ2Cloud. Indeed, user account are used in the authentication process and also to implement the Ownership Label concept. </p>
<p>All the functionalities needed to manage user will be available under the User Managment Menu View. After click in this option <img  src="./images/ButtonMenuUser.png">  from the Main window side menu, the User Management View will be shown as the following image:</p>
</div>

![Image of Sharelabelproject](./images/ManageUsersView.png)

<div style='text-align: justify;'>
<p>At the top of the User Management View there are multiple button that allows manage users: add, edit, disable, search users. Next you'll find more details on each of the available action. Note that these users are the ones managed by EZ2Cloud. In later version you can use users managed by Third part servies such On-premise AD ou Azure AD. </p>
</div>

![Image of Sharelabelproject](./images/ManageUserControl.png)


## Local User Managment
<div style='text-align: justify;'> 
<p>
The following section describe action to be performed on a single on a limited group of users. It is best suited to small group of users. 
</p>
</div>
All the local users accounts information are presented in a table as shown in the follwing image: <img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/UsersManagmentTable.png"><p>The user account information that is presented can be ordered by the fields: First Name, Last Name, Email. Just pass the mouse over the title corresponding to the field you want to sort and click on the button <img src="./images/IconSort.png"> to sort the account information in alphabetically ascending or descending order. <p>Also the information can be filtered by Departament, Role and Stauts. Do so by pass mouse over the title corresponding to the field you want to filter and click on the button <img src="./images/IconFilter.png"> then choose the values you want to filter by.
Additionaly you can navigate to different pages by click in one this arrows <img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/ButtonNav.png"> to move forward or backward. 

### User Status 
<div style='text-align: justify;'> 
<p>
The local users have a status that refers to the current state of the user regarding EZ2Cloud Plataform. The different status are: 
</p>
</div>

* <img src="./images/UserPending.png"> - After register user account an invitation email was sent and it waiting further user actions.  
* <img src="./images/UserActive.png"> - Account has been created and it is currently in use. After the user accepts the invitation and actually set up the account.
* <img src="./images/UserInactive.png "> - A user was disabled.


## Action on users
<div style='text-align: justify;'> 
<p> The actions to be performed on the information user account will always started by selecting one or multiple users from the table. Selecting a user by just click the check-box at the row of the corresponding user or just click on multiple check-box or select all the users by click the check-box on the table header. </p>
<p> The buttons will be disabled until one or more users is selected. Also the Add User button can be disable due to the fact that the Tenant has reach the maximum number of users the current subscripiton allows. In this case upon the Add icon you will see the <img src="./images/prohibition.png"> icon 
</div>

![Image of Sharelabelproject](./images/ManageUserControl.png)

1. **To Add User** ![Image of Sharelabelproject](./images/ButtonAdd.png) <p>Local users can be added one at a time by fill the fields showed in the following image. <img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/ManageUserAdd.png"></p><p>An invititation will be sent to the provided email address. In order to login the user must proceed to EZ2Cloud follow the invitation link embeded in the message and set his password and other provied other information that will be requested.</p>
2. **To Edit User** ![Image of Sharelabelproject](./images/ButtonEdit.png) <p>Local users can be Edit to change a User account. A user with the Role Administrator can change the values of the Users account, filling values in the fields as show in the form on the image <img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/ManageUserEdit.png">. It is not possible to change email address. </p>
3. **To Disable User** ![Image of Sharelabelproject](./images/ButtonDisable.png) <p>From the user table select rows that represents the ones you wnat to disable and then click button <img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/ButtonDisable.png">. You will see the following dialog 
<img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/ManageUserDisable.png"> where you must confirm to disable user. If you select multiple users the confirmation dialog will be show all the users selected <img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/ManageUserDisableMulti.png"></p>

4. **To Reset Password** ![Image of Sharelabelproject](./images/ButtonReset.png) <p>From the user table select rows that represents the ones you wnat to reset password and then click button <img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/ButtonReset.png">. You will see the following dialog 
  <img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/ManageUserReset.png"> where you must confirm the reset user operation. If you select multiple users the confirmation dialog will be show all the users selected 
     <img style="margin-top: 10px; margin-bottom: 10px; padding: 10px; border: 1px solid black" src="./images/ManageUserResetMulti.png"></p>

  
## Import Users
<div style='text-align: justify;'> 
<p>This is functionality to create users as a bulk process. Instead of creating users one each time the users are imported from a CSV file. The process only requires that you have a CSV file with all the data needed. For each user you want to create a line with the fields firstName, lastName, email and department separted by comma. </p>
<p>To start import user click on the button <img style="border: 1px solid black" src="./images/ButtonImport.png">. You will see the initial modal dialog Import user data, as the follwing image</p><img  style="float: left;margin:10px;padding: 10px;border: 1px solid black" src="./images/ImportUsers1.png">
<p>First you need to select the file containing the users data. Click Browse Files button. Then, from the File Chooser, select your account user data CSV file. Or just Drag and Drop  the CSV File in <img style="border: 1px solid black" src="./images/DragArea.png"> area. </p>
<p>After select the CSV file you will be next pass to the next step with the modal window showing the name of file that was select and a button Next. Click the button Next the next step it is select the roles for the users. The window used for set the users rles has two list. At the rigth side the roles selected or the roles that all the users will have. At the left side the list of all existing Tenant roles. You can select or deselect a role by click on the arrows. After select the roles and click Next you will view a summary of all the users that was read from file as show in the following image. 
<p>To confirm the user data and create the users just click on Sent Invitation button. </p> <img style="margin-top:10px;margin-bottom:10px;padding: 10px; border: 1px solid black" src="./images/ImportUsers5.png"></p>
</div>

### More about Import Users Process

1. Multiple file to import - It is possible to import as much users from file you want in the same file or separated by different files. 
2. Role user - At the step of select Roles of the import users process the selected roles will be applied to all users on the file.
3. Invitation - An email is send to the email address of each user on the file, the created account has Pending status. The Users will stay in Pending status until the account is actually confirmed. 
4. Users limit - The limit of users is defined by the Tenant plan. 



## Users Roles
<div style='text-align: justify;'> 
<img style="float: left;margin-right: 20px;margin-top: 10px; margin-bottom: 10px; padding: 10px;" src="./images/ManageRoles.png">
<p>User role define what each user is allowed to perform in EZ2Cloud. From the role of Administrator to User there are different predefined roles. It is up to the Administrator to assign one or more roles to each user. Let's look at the roles in a little more detail:</p>
</div>

1. **Administrator** - Users with this role has access to all features and functionalities. Can configure all the data required for a Tenant. Can change settings that impact all the Tenant users. Recommended for people who, in the context of a EZ2Cloud need full access to configure and setup the Tenant artifacts including sensitive and destructive actions like managing security or deleting data. 
2. **Project Admnistrator** - Users with this role can manage project. Create, Change settings, Archive, Setup and install Sattelite Service. 
3. **Label Administrator** - Users with this role will be responsible to manage the Labels. As the ownership labels are created from the user name the major concern of the users with this role is to actual manage the semantic labels. 
4. **User** - Users will be able to work at the colaborative working area from the End-user view.

<div style='text-align: justify;'> 
<p>
These are the predefined roles the ones that can be used to assign one or more roles to each user. However, this is a task that can only be performed by a user with the role of Administrator. Normally the give user one or more roles it is done when the user is being created. But it is possible at any time change the users in a specific role.</p> 
<p>From the role management window, (see image above) - click on the button
<img style="border: 1px solid black" src="./images/UsersInRolesButtonPeq.png"> in the row corresponding the role you want to change. For example if clicked in the row for Project Administrator role you will see all the users as show in the image <img style="float: left;margin-right: 20px;margin-top: 10px; margin-bottom: 10px; padding: 10px;width:80%; border: 1px solid black" src="./images/UsersInRoleProject.png" > that currently has this role. Here you can Add more users to this roles or Remove the ones you don't want to have this role anymore.</p> 
<p>There are no limits but  of course the role with access to functionalities that can affect all the Tenant users must be managed with care.</p>
</div>

## Add user(s) to Role
<div style='text-align: justify;'> 
<p>To add users to a Role you must be in that Role View as was explain in the Users Roles section. So when viewing the Role and all the users as shown in the image <img style="float: left;margin-right: 20px;margin-top: 10px; margin-bottom: 10px; padding: 10px;width:80%;border: 1px solid black" src="./images/AddUserToRole.png"> click the Button Add above the user information table.  After you must select, from the presented list of available users,  to add one or more users to the selected role.
</p>
</div>

## Dissassign user(s) from Role
<div style='text-align: justify;'> 
<p>At any time is is possible to Dissassign user(s) from a Role. To do this first you need to select the user of group of users you want to dissasign  as shown in the image <img style="float: left;margin-right: 20px;margin-top: 10px; margin-bottom: 10px; padding: 10px;width:80%;border: 1px solid black" src="./images/RemoveUsersFromRole.png"> click the Button Remove above the user information table. Next you will be prompted to confirm the procedure and remove the users from the role. So on the question Dissassignuser(s) from selected role? click the button Remove. If you click the button Cancel you will head back the Role View. 
</p>
<p>Of course, you must have at least one user with the Role Administrator.</p>
</div>



## Externally authenticated users
<div style='text-align: justify;'> 
<p>No yet implemented
</p>
</div>

