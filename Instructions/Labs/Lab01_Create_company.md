Hands-on-Lab 1: Create and configure a new company
====================================================

Exercise 1: Sign into Dynamics 365 Business Central
---------------------------------------------------

1.  Open your browser and browse to the **Dynamics 365 Business Central**
    homepage using the link
    <https://dynamics.microsoft.com/en-us/business-central/overview/>

2.  Click **Try for free** tab on the **Dynamics 365 Business Central**
    homepage.

3.  Enter your **Office 365 tenant credentials** and click **Next**.   

4.  Click on **Sign In** and then enter the password provided to you.

5.  Click on **Sign in** and  select **Yes** to stay signed in.

6.  If prompted for contact information, leave the **Country/region** as the default value and enter 0123456789 for  **Business Phone number**.

7.  Click on **Get Started**.

8.  Click on **Skip & go to Dynamics 365 Business Central**.

9.  Click on **Get Started**.

10.  It may take up to 1-2 mins to set up the **Dynamics 365 Business Central**
    environment.

11.  If prompted, select **Skip survey**.

12.  You should now be able to see the **Dynamics 365 Business Central** portal.


Exercise 2: Create a new company
--------------------------------

### Scenario

You are a functional consultant assigned to a new project, where you are
responsible for the analysis of your customers business processes. Your customer
is Contoso Ltd, situated in Redmond Washington. They will start to use
Microsoft Dynamics 365 Business Central as of their new fiscal year, January 1st
2024.

You initiate the process by creating a new company within the customers
database, including some predefined setup information but without any business
data.

### Tasks

1.  Create a new company.

2.  Complete the Company Setup wizard.

### Steps

1.  Create a new company.

    1.  Select the Search icon in the top-right corner of the page,
        enter `Companies`, and then choose the related link.

    2.  In the **Companies** page, select **New** and then, **Create New
        Company**

    3.  The **Create New Company** wizard opens.

    4.  Click **Next**.

    5.  As the company name, enter **Contoso Ltd**.

    6.  Select the option **Production – Setup Data Only**.

    7.  Click **Next**.

    8.  Skip the **Manage Users** option by clicking **Next**.

    9.  Click **Finish** to create the company.

    10. Wait approximately 10 minutes for the company creation to complete.

    11. Refresh the **Companies** page to check the **Setup status**.

2.  Complete the **Company Setup** wizard.

    1.  Once the **Setup Status** is changed to **Completed**, go to the
        **Settings** icon on the top-right corner.

    2.  Select **My Settings**, to open the new company.

    3.  Open the assist edit button (…) to the right of the **Company** textbox.

    4.  In the window that opens, select **Contoso Ltd** and click **OK**.

    >> If prompted with 'Set up a company' wizard, select **Next**. Accept the Terms & Conditions and select **Get Started**

   
    5.  Select **My Settings** on the top-right corner, and then select
        **Company information**.

    6.  On the **Company Information** page, enter the following information on
        the **General** tab. Once completed, Click on the back arrow.

| Setting             | Value                 |
|---------------------|-----------------------|
| Name                | Contoso Ltd           |
| Address             | 1432, Hamilton Street |
| Address 2           | Westminster           |
| City                | Atlanta               |
| State               | GA                    |
| Zip Code            | 31772                 |
| Country/Region Code | US                    |
| Contact Name        | Alex Brown            |
| Phone Number        | \+14255550101         |

3.  Select the Search icon in the top-right corner of the page, enter
    `Accounting periods`, and then choose the related link.

4.  On the **Accounting Periods** page, select **Create Year**.

5.  On the **Create Fiscal Year** page, select **1/1/2022** in the **Starting
    Date** field.

6.  Click **OK**.

 Click on **Yes** if you receive a pop-up asking you to confirm.

7.  A new **Fiscal Year** will be displayed on the **Accounting Periods** page.

8.  Close all the pages.

Exercise 3: Configure a new company
-----------------------------------

### Scenario

Now that the company has been created, you will further complete the company
configuration, setup and business data.

You will start by copying the following data from the default CRONUS company:

-   Zip codes

-   Shipment methods

### Tasks

1.  Complete the configuration worksheet.

2.  Copy data from another database company.

### Steps

1.  Complete the configuration worksheet.

    1.  Select the Search icon in the top-right corner of the page,
        enter `Configuration Worksheet`and then choose the related link.

    2.  At the bottom of the worksheet, enter a new line.

    3.  In the **Line Type** field, select **Group.**

    4.  In the **Name** field, enter `General Setup`.

    5.  Enter a new line.

    6.  In the **Line Type** field, select **Table**.

    7.  Open the assist edit button to the right of the **Table ID** field.

    8.  Search for **ZIP Code**, select table 225 and click **OK** to enter the
        ID in the **Table ID** field.

    9.  Repeat steps e. to h. to enter table **10 Shipment Method**.

2.  Copy data from another database company.

    1.  In the menu on the **Configuration Worksheet** page, select **Prepare**
        and then **Copy Data from Company**.

    2.  Open the assist edit button (…) to the right of the **Copy from** field.

    3.  Select **Cronus USA Inc.** and click **OK** to enter the company in the
        **Copy from** field.

    4.  Select the lines with the tables for ZIP codes and shipment methods.

    5.  In the menu select **Copy Data**.

    6.  Click **Yes**.

    7.  The data is now copied to the **Contoso Ltd** company. Click **OK**.

Close the configuration worksheet
