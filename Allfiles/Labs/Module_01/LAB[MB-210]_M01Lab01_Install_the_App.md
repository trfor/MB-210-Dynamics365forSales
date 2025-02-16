Module 1: Sales Overview
========================

## Practice Lab 1 – Install the app

Scenario
--------

World Wide Importers (WWI) is looking to formalize their sales process to
increase revenue and the give leadership stronger forecasting abilities. You are
a functional consultant configuring Dynamics 365 for Sales for World Wide
Importers. In this lab, you will install the Sales application and install
sample data.

**Important Note:** This lab will provide you with an actual Dynamics 365 tenant
and licenses for the Power Platform applications you will be using in this
course. You will only be provided with one tenant for the practice labs in this
course. The settings and actions you take within this tenant do not roll-back or
reset, whereas the virtual machine you are provided with does reset each time
you close the lab session. Please be aware that Dynamics 365 is evolving all the time. The
instructions in this document may be different from what you experience in your
actual Dynamics 365 tenant. It is also possible to experience a delay of several
minutes before the virtual machine has network connectivity to begin the labs.

Exercise 1 - Acquire Tenant Information and Connect
---------------------------------------------------

**Note:** If you have already completed a practice recently, the virtual machine
might pickup where you left off and you will not need to login again.  In that
case you can skip ahead to exercise two and resume.

### Task 1 – Connect to the Power platform administration portal

1.  On Virtual machine MB200-Dynamics_Lab, sign in as Admin with the password
    Pa55w.rd if you are not already logged in.

2.  Outside the VM in the online lab interface click Files and choose D365
    Credentials. This will allocate an Office 365 tenant for you to use in these
    labs.  It will display the admin email and password for your tenant.  You
    should copy this information to notepad or similar for your reference.

3.  In MB200-Dynamics_Lab launch Microsoft Edge from the taskbar. By default,
    the browser opens Office 365. Use the O365 credentials you just acquired in
    the previous step to login.

4.  Navigate in the browser to the Power platform admin portal at
    [https://admin.Powerplatform.microsoft.com](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fadmin.Powerplatform.microsoft.com&data=02%7C01%7Cv-juya%40microsoft.com%7C4be5a28c6f1e41eefee808d687ae2dc7%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636845580068684293&sdata=cLrD%2FhTDb5sRbajtFR9RrztfyTDCo0xGS4k8FSxTaIc%3D&reserved=0)

Exercise 2 – Install Dynamics 365 Sales Application
---------------------------------------------------

In this exercise, you will install the Dynamics 365 Sales Application and then
install sample data.

### Task 1 – Install Sales Application

1.  Navigate to <https://admin.powerplatform.microsoft.com>

2.  Expand **Admin Center** and click **Dynamics 365**.

3.  Select the check box for: **None of these. Don’t customize my
    organization.** When it finishes close the window.

4.  Navigate to <https://admin.powerplatform.microsoft.com>

5.  Expand **Admin Center** and click **Dynamics 365**.

6.  Select your instance and click edit **Solutions**. There are two edit
    buttons; one for editing the instance and another for managing your
    solutions, click on the one next to the Solutions.

7.  Locate and select **Dynamics 365 Sales Application**.

8.  Click **Install**.

9.  Read the terms of service and click **Install**.

10. Wait for the installation to complete. The status column will change to
    Installed when completed. This may take several minutes to complete.

### Task 2 – Install Sample Data

The Dynamics 365 Sales Application installation must complete before starting
this task.

1.  Navigate to <https://admin.powerplatform.microsoft.com>

2.  Expand **Admin Center** and click **Dynamics 365**.

3.  Select your instance and click **Open**.

4.  Navigate to **Settings** and select **Data Management**.

5.  Click **Sample Data**.

6.  Click **Install Sample Data**.

7.  Wait for the sample data installation to start and click **Close**. The
    sample data installation process will run in the background for a few
    minutes before you will see results.

8.  Navigate to **Sales** and select **Dashboards**.

9.  Your dashboard should now show some data. You may have to refresh the page
    before you can see the data.
