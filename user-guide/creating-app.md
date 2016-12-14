You can create SQL, BTEQ, or Java apps from the Dashboard or [Manage Apps](managing-apps.md) view. 

If you have not created any apps yet, AppCenter displays quickstart buttons at the top of the Dashboard for a guided approach with your first app, including sample SQL, Java, and BTEQ script files you can download. One you create apps, you can access the quickstart options by clicking ![app quickstart buttons](images/app-question.png) in the top-right corner.

1. From the **Dashboard** or **Manage Apps** view, click ![create app button](images/add-orange.png). 
2. In the **App Info** card, complete the entries with the following considerations:
  * Once you save the **App Info** card, you cannot change the **App Type**.
  * Use the default **Memory**, **Processors**, and **CPUs** values, unless you encounter errors that indicate resources are limited after running the app.
3. Click **Save** to proceed to the **App Code** card.
4. In the **App Code** card, do one of the following:
  * Click **Choose a File**, select the code file, and when the name of the file appears on the button, click it.
  * Drag the code file on top of the **Choose a File button**, and when the name of the file appears on the button, click the button.
5. [Optional] In the **App Configurations** card, do the following to pass parameters to the app:
  6. Click **Add Field**, click **(text field)**, and complete the entries. 
  7. If you want this field to be required when the app runs, which means the app will fail if this information is not present, click the slider next to **Required**. Click it again to remove the requirement.
  8. Repeat these steps to add additional parameters.
  9. Click **Save & Continue**.

   **Note**:  To skip this section, click either **AppResults Configurations** or **App Permissions**.
   
10. [Optional] In the **App Results Configurations** card, do the following to generate a visualization for this app:
   11. Click **Add Field**, click **(name)**, and complete the settings. 
   12. Repeat these steps to add additional settings.
   13. Click **Save & Continue**. 
 
  **Note**:  To skip this section, click **App Permissions**.

14. [Optional] In the **App Permissions** card, do the following to change the defaults:
   15. To add additional Managers, begin typing the user name, click it, and then press **Enter**. Repeat this step for each additional user you want to be a Manager for the app.
   16. To make this app public instead of private, click ![privacy off button](images/slider-off.png). Click it again to make this app private again.
   17. To add additional users to a private app, click the line below **Private users**, type the name of the user, and then press **Enter**. Repeat this step for each additional user you want to be a Private user.
18. Click **Save & Continue**.
19. Do one of the following:
   * To run the app now, do the following:
      20. Click **Run App**.
      21. Select a system and enter the credentials.
      22. If you entered parameters for this app, click **Continue** to use them for this job run, or click **Clear** if they are not required parameters and you don't want to use them for this run.
      23. [Optional] Select the **Schedule** options, and select **Daily** or **Advanced** run times.
      24. Click **Run Now**.
   * To review the app, click **View App** and then click ![edit button](images/edit-app.png).

## Related Topics
* [Dashboard](overview.md)
* [App Results Configurations Formats and Types](app-results-configuration-formats.md)
* [Running an App](running-app.md)
* [User Roles, App Permissions, and Job Results Permissions](app-permission-user-role.md)
