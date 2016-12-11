AppCenter maintains a list of app runs. For each app run, there are multiple result records. User role, app permissions, and job results permissions determine who can see the list of app runs and who can access result records. 

## Viewing App Results

When an app run is completed, AppCenter automatically displays the results. You can view the app results at that time, or any time later.

1. Do one of the following:
  * If the app just finished running and you want to view the results immediately, click the ```Run #...``` line above the ![run successful checkmark](images/run-checkmark.png) at the top of the list. 
  * If you want to view results from a previous app run, click the app in the Dashboard or **Manage Apps**, and then click the ```Run #...``` line above the ![run successful checkmark](images/run-checkmark.png) for the run want.
2. Click any *View result data set...** link to view that particular result record. For visualization results, 
3. [Optional] Click **Logs** to view app run logs. The ```Run #" in the **Recent Activity** list is associated with the ```job id``` in the log record.  
  
**Note:** If the app run failed, AppCenter provides an associated error record under **Logs**.




3. [Optional] For text/html visualization result, do the following:
  * To change the background from light to dark, select **Dark** from the menu next to ![light-dark visualization](images/light-dark-vis.png).
  * To see the sequence and relationships in the visualization, hover your mouse over any part of the image.
  * To view details about any item in the visualization, click it.

## Viewing App Results Immediately

1. Under **Recent Activity**, at the top of the list if there is more than one result, click the ```Run #...``` line above the ![run successful checkmark](images/run-checkmark.png).


  2. Select a system, enter the credentials, and click **Continue**.
3. Do one of the following:
   * If you did not enter any parameters for this app, skip the **App Parameters** card.
   * If you entered required parameters for this app or optional parameters that you want to use for this job run, click the slider for the parameter(s), and click **Continue**.
   * If you entered optional parameters for this app that you want to ignore for this job run, click **Clear**.
5. Skip the **Schedule (Optional)** card.
6. Click **Run Now**.

## Running an App Automatically  

**Note:**  If you select a schedule to run the app automatically, you cannot remove or change the schedule after you submit it and run the app.

1. Do one of the following::
  *  At the bottom of the **Create/Edit App** view, click **Run App**.
  *  From the Dashboard or **Manage Apps**, click the app and then click **Execute App**. 
2. Select a system, enter the credentials and click **Continue**.
3. Do one of the following:
   * If you did not enter any parameters for this app, skip the **App Parameters** card.
   * If you entered required parameters for this app or optional parameters that you want to use for this job run, click the slider for the parameter(s), and click **Continue**.
   * If you entered optional parameters for this app that you want to ignore for this job run, click **Clear**.
4. select **Daily** or **Advanced**, specify the schedule options, and click **Continue**.
5. Review the Schedule options and click **Submit**.
6. Click **Run Now**.

## Related Topics

* [Viewing Results](viewing-results.md)
* [Sharing Results](sharing-results.md)
* [User Roles, App Permissions, and Job Results Permissions](app-permission-user-role.md)
