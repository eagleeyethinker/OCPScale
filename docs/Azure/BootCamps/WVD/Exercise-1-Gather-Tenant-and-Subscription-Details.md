Exercise 1: Gather Tenant & Subscriptions ID
---------------------------------------------------
---
To deploy Windows Virtual Desktop we need to gather some information from the customers or our own lab environment. Some of this information includes the Azure Active Directory Tenant ID of the Environment we are deploying WVD, as well as the Subscription ID we plan to provision the WVD Service under.

---
# Gather Tenant & Subscription IDs

## Gather your Azure Active Directory Tenant ID from the Azure portal

1. Go to the [Azure portal](https://portal.azure.com), search for and select **Azure Active Directory**.

   ![image.png](/.attachments/image-b6077052-fb44-4a80-bcb7-ea2f38358cb8.png)

1. Find **Properties** then find **Directory ID**, click on the clipboard icon. Paste it in a handy location so you can use it later as the **Azure Active Directory ID** value.

   ![image.png](/.attachments/image-baadac51-bd9c-42d6-b0f0-bb859ea4c871.png)

## Gather your Subscription ID from the Azure portal

1. In the same [Azure portal](https://portal.azure.com) session, search for and select **Subscriptions**.
   
   ![image.png](/.attachments/image-cd64054a-0e8d-453f-9af3-d1c05ec228a4.png)


2. Select the Azure subscription you want to use.
3. Look for **Subscription ID**, and then hover over the value until a clipboard icon appears. Click on the clipboard icon and paste the value in a handy location so you can use it later as the **Azure Subscription ID** value.

   ![image.png](/.attachments/image-c20d07a8-7ba3-49e8-93b1-3983608be656.png)

