The combination of user role, app permission settings, and job results privacy settings determines the apps and features available to the user.

## User Roles

The three user roles are as follows:

| User  Role| Description |
| ------------- | ------------- |
| **User** | Any logged-in user who is not an Admin or root user. A user can perform the following tasks:<ul><li>Create apps.</li><li>Manage apps they create (edit and delete apps).</li><li>View job results for the apps they create.</li><li>View job results for public apps with unrestricted job results.</li><li>View job results for private apps for which they have been designated as a Private user and granted shared access to designate them as a Private user and that grant them shared access to results.</li><li>Share job results for the apps they create.</li><li>View a list of job runs for apps they did not create but to which they have been added as a Private user.</li></ul>
| **Admin**  | An Admin can perform the following tasks:<ul><li>Create apps</li><li>Manage apps they, non-Admins, or other Admins create (edit and delete apps).</li><li>View job results for the apps they create.</li><li>View job results for apps with public job result.</li><li>View private job results for which they have been granted shared access.</li><li>Share app job results for the apps they create.</li><li>Access the Admin Dashboard for information about total apps, total authors, executed jobs, metrics, and more.</li><li>Manage users (promote users to and demote users from Admin status.</li><li>View System and Audit Logs.</li></ul>
| **Root**  | A root user can perform the following tasks:<ul><li>Manage systems (create and edit Teradata, Aster, or Presto systems). </li><li>Manage users (promote users to and demote users from Admin status).</li><li>View, create, edit, and delete LDAP domains.</li></ul>

## App Permissions

App permission settings determine who has access to the apps. These permissions are available at the bottom of the **Create/Edit App** view.

App permission settings are separate from job results privacy. For more information about job results privacy settings, see [Share Job Results Permissions](#share-job-results-permissions).

| App Permission| Description |
| ------------- | ------------- |
| **Managers**  | App Managers can can do the following: <ul><li>View the app</li><li>Run the app.</li><li>View app results</li><li>Manage the app (edit and delete the app)</li><li>Add or remove Managers</li></ul>|
| **Privacy**  | When you create an app, AppCenter automatically makes it private, which means only Managers, Admins, or designated Private Users can see the app. Managers and Admins can turn privacy off to make the app public, which makes it visible to all users. |
| **Private users** | Private users for an app can do the following: <ul><li>View the app in the Dashboard or **Manage Apps** view</li><li>Run the app.</li><li>View the list of app results.</li></ul>|

## Share Job Results Permissions

**Share job results** determines who can see the app's actual job results. By default, privacy is off.

Job results privacy is separate from app privacy. For more information about app privacy settings, see [App Permissions](#app-permissions).

| Job Results Permission| Description |
| ------------- | ------------- |
| **Privacy off**  | Provides the following access to job results: <ul><li>For public apps, job results are available to all users.</li><li> For private apps, job results are available to the Manager who created the app and the app's Private users.</li></ul> |
| **Privacy On**  | Provides restricted access to all or individual job results. For public and private apps, job results are available to the Manager who created the app and to only those users who have been granted shared access to an individual result or all results under **Share job results**. |


