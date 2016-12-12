Only Admin users will see the **Logs** option in the navigation panel. From **Logs**, you can view System Logs and Audit Logs. 
System Logs are divided into two segments as illustrated here:

![logs toolbar](/user-guide/images/logs-toolbar.png)

For System Logs, you can perform the following tasks:

- View all logs from both segments
- Filter the logs in each segment
- Search for a log entry
- Specify the number of log rows to appear on a page

For Audit Logs, you can perform the following tasks:

- View all logs
- Search for a log entry

## Viewing System Logs

When you select Logs from the navigation panel, AppCenter displays all logs by default.

## Filtering System Logs

1. In each segment of the toolbar, click the desired filter.
2. To clear the filters, do the following:
  *  In the left segment of the toolbar, click ![all system logs button](/user-guide/images/filter-logs.png).
  *  In the right segment of the toolbar, click ![all services logs button](/user-guide/images/all-services.png).

## Searching for Logs

1. In the ![search logs box](/user-guide/images/search.png) box, start typing any part of the log entry. AppCenter filters the list of users as you type.
2. To clear this search filter and view all logs, click ![clear search button](/user-guide/images/clear-search.png).

**Tip**:  To hide the search filter box, click ![hide search filter](/user-guide/images/hide-search-filter.png).

## Sorting Users in Descending or Ascending Order

By default, AppCenter sorts the list of users in ascending order.

1. In the **User** header, do one of the following:
 * To sort by decending order (Z-A), click ![up arrow button](/user-guide/images/up-arrow.png).
 * To restore ascending order (A-Z), click ![down arrow button](/user-guide/images/down-arrow.png).

## Promoting and Demoting users

1. In the card for the user you to promote or demote, do one of the following:
 * To promote a non-Admin to an Admin, click ![promote to admin button](/user-guide/images/promote-admin.png).
 * To demote an Admin to a non-Admin, click ![demote from admin button](/user-guide/images/demote-admin.png).
1. In the **ADMIN** navigation panel, click **Logs**.
 
### Specifying the Number of Logs to Appear on a Page

The default setting for number of logs per page is 100. You can change this in the **USER AUDIT LOGS** and **SYSTEM ERROR LOGS** tabs. Listener maintains this setting while you are in the tab. When you leave the tab, Listener reverts to the default setting.

1. In the lower right of the **USER AUDIT LOGS** or **SYSTEM ERROR LOGS** page, in the **Per Page** list, select the number of logs you want to appear on the page while viewing that tab (**100**, **500**, **1000**, or **5000**).

## USER AUDIT LOGS

**USER AUDIT LOGS** is the default view and lists user activity on individual cards. Each card shows the user name, action taken, status of the action (**success** or **failed**), and a timestamp.

### Filtering the User Log by Action Type

1. In the **Filter by action** list, select one of the following filters:
 * **Add**: Lists only sources, systems, or targets added
 * **Update**: Lists only sources, systems, or targets updated
 * **Delete**: Lists only sources, systems, or targets deleted
 * **Star**: Lists only sources that have been starred
 * **Unstar**: Lists only sources that have been unstarred
 * **Login**: Lists only failed login attempts

2. To clear this filter, select the delete button next to the filter box.

### Filtering the User Log by User Name

1. In the **Filter by user** box, start typing any part of the user name.
2. When the desired user name appears under the box, click it.
3. To clear this filter and view logs for all users, delete the characters you typed in the **Filter by user** box.

### Filtering the User Log by Successful or Failed Actions

**All Actions** is the default filter.

1. In the action list, select one of the following filters:
 * **Successful**
 * **Failed**
2. To clear this filter, select **All Actions**.

## SYSTEM ERROR LOGS

**SYSTEM ERROR LOGS** lists all system error messages from Mesos and Zookeeper.

### Filtering the Error Log by Type

1. In the **Filter by type** list, select **Mesos** or **Zookeeper**.
2. To clear this filter and view logs for both types, select **All**.

## Searching for Errors by Term

1. In the **Search by term** box, start typing any part of the term. Listener automatically filters the list as you type.
2. To clear this search and view all errors, delete the characters you typed in the **Search by term** box.

## Exporting System Error Logs for Support

1. [Optional] Use the filter and search options to narrow the list of logs for export.
2. Next to **Search by term**, click the download arrow button. Listener displays the error logs in a new browser window. 
3. Use your browser's save feature to save the file to your system. 

**Tip:** If your browser does not suggest a specific file type when you attempt to save it, assign the json extension. For example: `error.json`


## Related Topics
* [Managing Users](manage-users.md)
* [User Roles, App Permissions, and Job Results Permissions](/user-guide/app-permission-user-role.md)
