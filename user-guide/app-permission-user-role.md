
The combination of the following settings determines who can see the app, run the app, view app results, and edit and delete the app:

* App permission settings
* Job results privacy setting
* Role of each user logged in
https://github.td.teradata.com/appcenter/documentation/settings
## App Permissions

**App Permissions** determine who has access to the apps and are available at the bottom of the **Create/Edit App** view.

| App Permission| Description |
| ------------- | ------------- |
| **Managers**  | When you create an app, AppCenter automatically adds you as a Manager. App Managers can can do the following: <ul><li>View app settings</li><li>View app results</li><li>Edit the app</li><li>Delete the app</li><li>Add or remove Managers</li></ul>|
| **Privacy**  | When you create an app, AppCenter automaticcally selects the **Privacy On** option, which means only Managers, Admins, or designated Private Users can see the app. Managers and Admins can turn privacy off to make the app public so everyone can see it. |
| **Private users** | Private users for the app can do the following: <ul><li>View the app n the Dashboard or **Manage Apps** view</li><li>View the list of app results.</li></ul>|

## App Job Results Permissions

**App Job Results Permissions** determine who has access to a specific job result or all job results. Job results are available under **Recent Activity**.

| Job Results Permission| Description |
| ------------- | ------------- |
| **Privacy off**  | **Privacy off** is the default setting. <ul><li>For public apps, job results are available to all users.</li><li> For private apps, job results are available to the Manager who created the app and the app's Private users.</li></ul> |
| **Privacy On**  | For public and private apps, job results are available to the Manager who created the app and only those users who have been added under **Share job results**. |

## User Roles

User types include the following:

| User  | Description |
| ------------- | ------------- |
| **User** | Regular user who is not an Admin, Manager, or root user. A regular user can perform the following tasks:<ul><li>Create apps</li><li>View app results for the apps they create or for which they have been designated as</li><li>Edit and delete the apps they create
| **Privacy**  | When you create an app, it is private by default. Managers and Admins can see private apps, turn privacy off, and  add or remove other private users. Added private users who are not managers or Admins, can view the app, run the app, and review app results.

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
