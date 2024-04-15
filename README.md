### UiPath RPA Challenge
# Coronavirus Stat-Alert Bot

[![GitHub](https://badgen.net/badge/icon/GitHub?icon=github&color=black&label)](https://github.com/MaxineXiong)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform - UiPath RPA](https://img.shields.io/badge/Platform-UiPath_RPA-fa4616)](https://www.uipath.com)

<br/>

This repository hosts an automation solution designed to address the challenge outlined in the requirements below.

**Objective**

Develop a **Coronavirus stat-alert bot** capable of **scraping Coronavirus statistics** (**Total Cases**, **Total Deaths**, and **Total Recovered**) from a user-inputted country on the website https://www.worldometers.info/coronavirus/. The bot will then **send an update email** containing the scraped data to specified friends or family members.

**Instructions**

1. Prompt the user to input a country using an Input Dialog and store the value in a String variable.
2. Utilize the Table Extraction Wizard to extract the table into a DataTable variable.
3. Implement a For Each Row activity to iterate through the data table, applying an if condition within the loop to filter the data table and retain statistics for the user-inputted country.
4. Save the Total Cases, Total Deaths, and Total Recovered values in separate String variables.
5. Employ a For Each activity to iterate through an array of email addresses and dispatch an email containing the scraped statistics to each address using the Send Outlook Mail Message activity.

_You can check out the **automation demo video for the solution** below_:

https://github.com/MaxineXiong/Coronavirus-Stat-Alert-Bot-RPA/assets/55864839/9eb4e889-7d70-4766-b81f-1c30ddb7d349





<br/>


## **Installation**

Before installing **UiPath Softwares**, please make sure your system meets the hardware and software requirements outlined in the **[UiPath documentation](https://docs.uipath.com/studio/standalone/2022.10/user-guide/hardware-and-software-requirements)**.

The **Uipath Platform** includes the following tools:

- **UiPath Studio**
- **UiPath Assistant**
- **UiPath Automation Cloud, including UiPath Orchestrator**

<details>  
<summary> To run this project successfully, please follow these steps to install UiPath Studio:
</summary>

***

Step 1 : Visit [uipath.com](https://www.uipath.com/) and click **Try UiPath Free** button.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_1.png">
</p>

Step 2: **Sign up** for a personal account.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_2.png">
</p>  

Step 3: **Verify** your account in email.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_3.png">
</p>  

Step 4: **Log into** the **UiPath Automation Cloud** using your account, and click the **Download Uipath Studio** button.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_4.png">
</p>   

Step 5: Click **Sign in**.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_5.png">
</p>    

Step 6: Select **UiPath Studio Pro**.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_6.png">
</p>  

Step 7: Follow the system instructions to complete the installation of **UiPath Studio Pro**.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_7.png">
</p> 

</details> 

<br/>

## **Usage**

To run the RPA workflow on your local machine, follow these steps:

1. Either **download** this repository to your local machine or **clone** it directly within your UiPath Studio.
2. Open the **UiPath Studio** software on your machine.
3. Locate and **open** the **Main.xaml** file from the downloaded repository in **UiPath Studio**.
4. **Run** the **Main.xaml** file to start the RPA process.

<br/>

## **Acknowledgement**

I would like to express my gratitude to the **[UiPath community](https://community.uipath.com/)** for providing resources, tutorials, and a platform for automation enthusiasts to learn and collaborate.

<br/>

## **License**

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/), which means you're free to modify, distribute, and use the code in your own projects.
