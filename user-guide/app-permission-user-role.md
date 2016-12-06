The combination of app permission settings, job results privacy settings, and the role of the users logged in termines who can see the app, run the app, view app results, and edit and delete the app.

## App Permissions

**App Permissions** determines who has access to the apps. These permissions are available at the bottom of the **Create/Edit App** view.

| App Permission| Description |
| ------------- | ------------- |
| **Managers**  | App Managers can can do the following: <ul><li>View the app</li><li>View app results</li><li>Edit the app</li><li>Delete the app</li><li>Add or remove Managers</li></ul>|
| **Privacy**  | When you create an app, AppCenter automatically selects the **Privacy On** option, which means only Managers, Admins, or designated Private Users can see the app. Managers and Admins can turn privacy off to make the app public so everyone can see it. |
| **Private users** | Private users for the app can do the following: <ul><li>View the app in the Dashboard or **Manage Apps** view</li><li>View the list of app results.</li></ul>|

## Share job results Permissions

**Share job results** determines who can see the app's job results. By default, privacy is off, which means app Managers can see the actual results and Private users can see the app run history list without result details. **Share job results** settings are available under **Recent Activity**.

If you make results private, you can see them and then share all results or specific results with only the users you specify.  

| Job Results Permission| Description |
| ------------- | ------------- |
| **Privacy off**  | **Privacy off** is the default setting. <ul><li>For public apps, job results are available to all users.</li><li> For private apps, job results are available to the Manager who created the app and the app's Private users.</li></ul> |
| **Privacy On**  | For public and private apps, job results are available to the Manager who created the app and only those users who have been added under **Share job results**. |

## User Roles

User types include the following:

| User  Role| Description |
| ------------- | ------------- |
| **User** | Regular user who is not an Admin, Manager, or root user. A regular user can perform the following tasks:<ul><li>Create apps</li><li>View app results for the apps they create or for which they have been designated as a private user in **Share job results**</li><li>Share app results for the apps they create</li><li>Edit and delete apps they create</li>
| **Manager**  | When you create an app, AppCenter automatically adds you as a Manager. See [App Permissions](#app-permissions)

There are three primary user types:

* User
* Admin
* System Administrator

## User

As a user, you can do the following:
* View, run, and see results for public apps.
* Create public or private apps.
* View, run, edit, and delete apps you create. 
* View logs associated with apps you create. 
* Add other users as **Private users** to private apps you create.
* Add other users as **Managers** to the private or public apps you create, which enables them to run, edit, and delete the app.
* View private apps created by other users who added you as a **Private user**.
* View, run, edit, and delete apps created by other users who added you to **Managers**.
