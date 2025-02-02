To troubleshoot any issues that you might face during the export and import, do the following:

- During the import of the data in the target organization, if you see yellow warning symbols, we recommend that you verify the logs in the Configuration Migration Tool for network errors.
    
    To troubleshoot errors and warnings, see [Troubleshoot configuration data migration issues using log files](/power-platform/admin/manage-configuration-data#troubleshoot-configuration-data-migration-issues-using-log-files).

    If the logs contain network errors, redo the import step. You can proceed with the next steps if no network errors are indicated in the logs.

    :::image type="content" source="../customer-service/media/yellow-warnings-in-data-import.png" alt-text="Yellow warnings that indicate errors during data import.":::

    An example of a network error is as follows.
    ```
    Time: 11:46:09 PM
    Error: There was no endpoint listening at `https://www.contoso.com/XRMServices/2011/Organization.svc/web?SDKClientVersion=9.2.46.5279` that could accept the message. This is often caused by an incorrect address or SOAP action. See InnerException, if present, for more details.
    Stack Trace: Service stack trace:
    ```