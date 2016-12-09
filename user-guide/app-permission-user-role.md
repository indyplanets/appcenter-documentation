The combination of user role, app permission settings, and job results privacy settings determines the apps and features available to a user. For example:
<ul><li>An app may be private, but the user who created it can add other Managers to the app. All designated Managers can view, edit, or delete an app. </li><li>An app may be public, but have private job results. In this case, you can access the app, but see only the list of job runs; this includes other Managers who were added to the app. If the user who created the app addes you as a Private user to the job results, you will be able to see the list of job runs and the actual results of those job runs.</li><li>An app may be private, but have public job results. In this case, a designated app Manager would need to add you as Private user to the app so you could see the public job results.</li></ul>

## User Roles

| Role| Privileges |
| ------------- | ------------- |
| **Users and Admins**  | <ul><li>Create (or author) public or private apps.</li><li>Grant specific users access to the private apps they created.</li><li>Edit and delete apps they created.</li><li>Add other Managers to apps they created, or to apps for which they have been added as a Manager</li><li>View job results for the apps they created.</li><li>Share job results for the apps they created with all, selected, or no other users.</li><li>View shared job results for public apps other users created.</li><li>View shared job results for private apps other users created, if added as a Private User.</li><li>View the list of job runs for public apps with private job results that other users created, if added as a Private User for job results.</li></ul> |
| **Admins Only**  | <ul><li>Access the Admin Dashboard to view app, author, job, and other statistics.</li><li>Edit and delete apps other users created. <li>View System Logs and Audit Logs.</li></ul>|
| **Admins and Root Users**  | <ul><li>Promote users to and demote users from Admin status.</li></ul>|
| **Root Users Only**  | <ul><li>Create and edit Teradata, Aster, or Presto systems.</li><li>View, create, edit, and delete LDAP or Active Directory setttings.</li></ul>|

## App Permissions

App permission settings determine who has access to the apps. These permissions are available at the bottom of the **Create/Edit App** view. App permission settings are separate from job results privacy. For more information about job results privacy settings, see [Share Job Results Permissions](#share-job-results-permissions).

| App Permission| Description |
| ------------- | ------------- |
| **Managers**  | When you create an app, AppCenter automatically makes you the first Manager. As a Manager, you can do the following: <ul><li>Add and remove additional Managers.</li><li>Edit or delete the app.</li></ul>|
| **Privacy**  | When you create an app, AppCenter automatically makes it private, which means only Managers, Admins, or designated Private Users can see the app. Managers and Admins can turn privacy off to make the app public, which makes it visible to all users. |
| **Private users** | Can do the following: <ul><li>View the app in the Dashboard or **Manage Apps** view.</li><li>Run the app.</li><li>View the read-only list of job results.</li><li>View private job results if granted shared access.</li></ul>|


##Job Results Permissions

The **Share job results** settings determine who can see the app's actual job results, in addition to the list of job runs. Job results are available under **Recent Activity**. By default, privacy is off. Job results privacy is separate from app privacy. For more information about app privacy settings, see [App Permissions](#app-permissions).

| Job Results Permission| Description |
| ------------- | ------------- |
| **Privacy off**  | Provides the following access to job results: <ul><li>For public apps, job results are available to all users who have the direct link.</li><li> For private apps, job results are available to the Manager who created the app and the app's Private users.</li></ul> |
| **Privacy On**  | Provides restricted access to all or individual job results. For public and private apps, job results are available to the Manager who created the app and to only those users who have been granted shared access to an individual result or all results. |
