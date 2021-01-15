# Root certificate

After you have deployed your SCEPman environment you have to create a root certificate.

If you want to use an intermediate certifacte (Enterprise Edition only) you can have a look at this guide: -- Link to Intermediate certfificate --

For a standard SCEPman setup we recommend to generate a new root certificate with the following steps:

## Create SCEPman root certificate

1. Navigate to **App Services**. 
2. Choose the SCEPman application and click on **Browse** to see the SCEPman website. 
3. When everything works as intended **Vault**, **Intune** and **Graph** are set as **connected**.

![](../../.gitbook/assets/scepman23.png)

4. The option **click here to start** creates the Azure Key Vault RootCA certificate. The initial root certificate should be created only once in a farm. 
5. Select **I have read the documentation** and click **Create First Node**.
6. After some minutes you can refresh the page. Now you should see that the root certificate is available.

-- Screenshot 1 --

| Back to Trial Guide | Back to Community Guide | ​[Back to Enterprise Guide](../../getting-started/enterprise-guide.md#step-4-deploy-storage-account-and-change-artifacts)​ |
| :--- | :--- | :--- |