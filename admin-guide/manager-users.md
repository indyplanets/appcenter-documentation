Only root users and Admins will see **Manage Users** in the navigation panel.

## How Users are Added

When users who are part of an LDAP and Active Directory (configured by the root user) first log in, they are automatically added to the list of users. 

From the **Manage Users** view, you can perform the following tasks:

- View a list of all users
- Filter the list of users by administrative status
- Search for users
- Sort the list of users in descending or ascending order
- Hide the search bar
- - Promote a Non-Admin user to an Admin
- Demote an Admin user to a Non-Admin

**Note**: You can combine view and search options.

## Viewing the List of All Users

1. Log into AppCenter as a root user. AppCenter displays all users.

## Filtering Users by Administrative Status

1. Under **Users**, do any of the following:
 * To filter by Admins, click ![admin users button](/user-guide/images/admin-users.png).
 * To filter by non-administrative users, click ![non-admin users button](/user-guide/images/non-admin-users.png).
 * To clear the filter and view all users, click click ![clear search button](/user-guide/images/clear-search.png).

## Searching for Users

1. In the ![search users button](/user-guide/images/search.png) box, start typing any part of the user's name or email address. Listener automatically filters the list of sources as you type.
2. To clear this search and view all users, remove the characters you typed in the **Search by name** box.

## Sorting Users in Descending or Ascending Order

By default, Listener sorts the list of users in ascending order (A-Z).

1. In the **NAME** header, do one of the following:
 * To sort by descending order (Z-A), click the down arrow next to **NAME**.
 * To restore ascending order (A-Z), click the up arrow next to **NAME**.

## Editing Permissions for users

1. In the user list, click the pencil button.
2. To promote a user to an administrator or demote an administrative user, click the **Promote to admin** switch and click **CLOSE**. One of the following occurs:
 * If you promoted a user to an admin, an orange shield appears next to that user's name.
 * If you demoted a user, a gray shield appears next to that user's name.

## Related Topics
* [Managing Users](manage-users.md)
* [User Roles, App Permissions, and Job Results Permissions](/user-guide/app-permission-user-role.md)
