The combination of user role, app permission settings, and job results privacy settings determines the apps and features available to the user.

## User Roles

The three AppCenter user roles are as follows:

* User
* Admin
* Root

Users and Admins can both do the following:

* Create (or author) public or private apps.
* Grant specific users access to private apps.
* Manage apps they create (edit and delete them).
* View job results for the apps they create.
* Share job results for the apps they create with all, selected, or no other users.

Admins only can do the following:

* Manage apps other users and Admins create (edit and delete them).
* Access the Admin Dashboard to view app, author, job, and other statistics.

Admins and Root users only can do the following:

* Manage users (promote users to and demote users from Admin status).

Root users only can do the following:

* Manage systems (create and edit Teradata, Aster, or Presto systems).
* View, create, edit, and delete LDAP domains.

## App Permissions

App permission settings determine who has access to the apps. These permissions are available at the bottom of the **Create/Edit App** view.

App permission settings are separate from job results privacy. For more information about job results privacy settings, see [Share Job Results Permissions](#share-job-results-permissions).

| App Permission| Description |
| ------------- | ------------- |
| **Managers**  | When you create an app, AppCenter automatically makes you the first Manager. You can add and remove additional Managers, and edit or delete an app for which you are a manager.|
| **Privacy**  | When you create an app, AppCenter automatically makes it private, which means only Managers, Admins, or designated Private Users can see the app. Managers and Admins can turn privacy off to make the app public, which makes it visible to all users. |
| **Private users** | Private users for an app can do the following: <ul><li>View the app in the Dashboard or **Manage Apps** view.</li><li>Run the app.</li><li>View the list of job runs.</li><li>View private job results if granted shared access.</li></ul>|

## Share Job Results Permissions

**Share job results** determines who can see the app's actual job results. By default, privacy is off.

Job results privacy is separate from app privacy. For more information about app privacy settings, see [App Permissions](#app-permissions).

| Job Results Permission| Description |
| ------------- | ------------- |
| **Privacy off**  | Provides the following access to job results: <ul><li>For public apps, job results are available to all users.</li><li> For private apps, job results are available to the Manager who created the app and the app's Private users.</li></ul> |
| **Privacy On**  | Provides restricted access to all or individual job results. For public and private apps, job results are available to the Manager who created the app and to only those users who have been granted shared access to an individual result or all results under **Share job results**. |


