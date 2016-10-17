# Debugging

When apps are not working as expected, it can be for a number of reasons. 

## Checking App Logs

The first thing to do is to check the app's logs to see if any errors or notices appear that might indicate the problem.

Currently the UI does not show the app logs, but you can access them through the API. You just need to know the app\_id and add it to the url like you see below.

```
curl https://appcenter-logging-service.example.com/logs?app_id={APP_ID}
```

