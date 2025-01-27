---
lab:
    title: 'Lab: Validate lab environment'
    module: 'Module 0: Configure Dynamics 365 Customer Service'
---

# Practice Lab - Validate lab environment

## Scenario

In this Module 0 lab, you will validate that your classroom tenant is working as expected. You will access your individual credentials, record your "alias", and open the Dynamics 365 model-driven application that we will be using throughout the course.

**Important notice for instructors and students:** This lab will provide you with an actual Dynamics 365 tenant and licenses for the Power Platform applications you will be using in this course. Please be aware that the Power Platform is evolving all the time. The instructions in this document may be different from what you experience in your actual tenant. It is also possible to experience a delay of several minutes before the virtual machine has network connectivity to begin the labs.

## Exercise 1 - Access a trial environment

### Task 1 – Log into the Power Platform admin center

1. In a new browser tab, navigate to https://dynamics.microsoft.com/dynamics-365-free-trial. In the middle of the screen, you will see two buttons: one to see plans and pricing, the other to try for free. Select **Try for free.**
3. Locate Dynamic 365 Customer Service.
4. Select the **Try for free** button.
5. In the *Let's get started* screen, enter the credentials that were provided to you as part of your lab environment. Accept the license agreement. (If you are prompted to enter a phone number, you can enter 0123456789.)
6. Select **Start your free trial**.
7. (If prompted, select **Launch Trial** in the pop-up.
8. Your trial will launch. It may take a few minutes for your environment to open.
9. In the header, select **Service trial.** This will open your list of available apps. In this course, we will be working mostly in the **Customer Service Hub.** Select **Customer Service Hub** to open the application.
10. Feel free to take a few minutes to explore the application.

---
demo:
    title: 'Demo: Set up Customer Service environment'
    module: 'Module 1: Case management'
---

# Demo - Set up Customer Service environment

**Note:** This is a **required prerequisite** to the students completing Module 1, Lab 1, Creating Cases. You may choose to do this demo as a live demo, or you may complete this demo prior to the course starting. If your students are encountering errors finding the products and data in Module 1, Lab 1, please confirm that you have done these steps correctly. 

## Scenario 

In this demo, you will create one product and two case subjects. Students will use these records as their demo data for Module 1, Lab 1.

## Exercise 1: Create demo data

### Task 1: Create products

1. Navigate to the **Apps** section. Select **Sales Hub.**

2. When the app opens, navigate to the areas and switch to **Settings.**

3. Select **Products.** Click **New Product.**
    - For **Name,** enter **JBO Top D. Hifi.**
    - For **Product ID**, enter **12345.**
    - Choose **Default Unit** for **Unit Group.**
    - Choose **Primary Unit** for **Default Unit.**
    - Enter **0** for **Decimals Supported.**
 
4. Select **Save.**

5. Select **Publish.**

### Task 2: Create Case Subjects 

1. Select **Sales Hub** at the top of the screen to open the list of available applications.

2. Select the **Customer Service admin center.**

3. In the **Customer support** section, select **Case settings.**

4. Under **Subjects**, select **Manage.**

5. Under **Subject tree management**, select **+Add.**
    - Enter **Service** for **Title.**
    - Leave **Parent subject** blank. 
    - Select **Save and close.**

6. Select **+Add** again to add another subject.
    - Enter **Maintenance** for **Title.**
    - Select **Service** for **Parent subject.**
    - Select **Save and close.**

