---
lab:
    title: 'Lab: Create and configure a new company'
    module: 'Module 2: Application Setup'
---

# Create and configure a new company

## Exercise 1: Create a new company

### Scenario

You are a functional consultant assigned to a new project, where you are
responsible for the analysis of your customers business processes. Your customer
is Contoso Inc., situated in Redmond Washington. They will start to use
Microsoft Dynamics 365 Business Central as of their new fiscal year, January 1st
2021.

You initiate the process by creating a new company within the customers
database, including some predefined setup information but without any business
data.

### Tasks

1.  Create a new company.

2.  Complete the Company Setup wizard.

### Steps

1.  Create a new company.

   1.  In the **Companies** page, select **New** and then, **Create New
        Company**

   2.  The **Create New Company** wizard opens.

   3.  Click **Next**.

   4.  As the company name, enter Contoso ‘*student name*’ Inc. (Replace
        ‘*student name’* with your name so that each student has its own company
        within the training database.)

   5.  Select the option **Production – Setup Data Only**.

   6.  Click **Next**.

   7.  Skip the **Manage Users** option by clicking **Next**.

   8.  Click **Finish** to create the company.

2.  Complete the **Company Setup** wizard.

   1.  To open the new company, go to the **My Settings** page.

   2.  Open the assist edit button to the right of the **Company** textbox.

   3.  In the window that opens, select “Contoso ‘*student name*’ Inc.” and
        click **OK**.

   4.  Click **OK**.

   5.  The new company opens and the **Company Setup** wizard automatically
        opens.

   6.  Click **Next**.

   7.  Fill in the company’s address information.

   8.  Click **Next**.

   9.  Specify the company’s contact details.

   10. Click **Next**.

   11. Disable the **Use a bank feed service** option.

   12. Click **Next**.

   13. Skip the company’s bank information by clicking **Next**.

   14. In the **Fiscal Year Start Date** field, enter 1/1/2021.

   15. Click **Next**.

   16. Leave the costing method set to the default value ‘FIFO’.

   17. Click **Next**.

   18. Click **Finish** to start using the company.

## Exercise 2: Configure a new company

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

   1.  Open the **Configuration Worksheet** page.

   2.  At the bottom of the worksheet, enter a new line.

   3.  In the **Line Type** field, select **Group.**

   4.  In the **Name** field, enter ‘General Setup’.

   5.  Enter a new line.

   6.  In the **Line Type** field, select **Table**.

   7.  Open the assist edit button to the right of the **Table ID** field.

   8.  Search for ‘ZIP Code’, select table 225 and click **OK** to enter the ID
        in the **Table ID** field.

   9.  Repeat steps e. to h. to enter table 10 Shipment Method.

2.  Copy data from another database company.

   1.  In the menu on the **Configuration Worksheet** page, select **Actions**,
        then **Tools** and then **Copy Data from Company**.

   2.  Open the assist edit button to the right of the **Copy from** field.

   3.  Select ‘Cronus USA Inc.’ and click **OK** to enter the company in the
        **Copy from** field.

   4.  Select the lines with the tables for ZIP codes and shipment methods.

   5.  In the menu select **Copy Data**.

   6.  The data is now copied in the new company.
