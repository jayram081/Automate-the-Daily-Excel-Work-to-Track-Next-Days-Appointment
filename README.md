# 📅 `Automate the Daily Excel Work to Track Medical Appointment` :  
> My objective here is to **completely Automate the manual Excel Work** to Track the Next Day Medical Appointment and complete it next day in **PPMC (Pre-Policy Medical Check-Up)** so that we can reduce the **20 Minutes of manual work to 1 Minute** on daily basis for 25 Account Managers.


## 🔰 `Introduction` :
>**PPMC :** In the context of insurance, PPMC stands for Pre-Policy Medical Check-Up. This is a set of medical examinations and tests that a prospective policyholder must undergo before an insurance company approves their policy application. Here's a brief overview:

>**What is a Pre-Policy Medical Check-Up (PPMC) ?** <br>
A PPMC consists of various medical tests to assess the applicant's health status. These tests help the insurer determine the applicant's medical fitness and identify any pre-existing conditions. The results of these tests can influence the premium rates and coverage terms of the policy.

>**Importance of PPMC:** <br>
>1. Assessing Health Status: It provides a baseline health assessment for the policyholder.
>2. Identifying Pre-Existing Conditions: Helps insurers understand if there are any existing medical conditions that need to be considered.
>3. Determining Premiums: The results can affect the premium rates, ensuring they are appropriate for the individual's health status.
>4. Smooth Claim Settlement: The medical reports from the PPMC can be crucial during the claim settlement process.

>**Who Needs to Undergo PPMC ?** <br>
Typically, policyholders above a certain age (often 40 or 45 years) are required to undergo a PPMC. However, this can vary depending on the insurance company and the type of policy.


## 📊 `The Source Data` :
> Account manageers extract csv file from CRM in evening to prepare the next day appointment. This file have 185 Columns and usually lakhs of rows based on their insurer volumes. They use the following columns to prepare the next day appointment tracker :
>- **CorporateName :** Insurer Name
>- **PatientName :** Name of Insured who will go under the medicals.
>- **ApplicationId :** Insured Application Number
>- **ContactNo :** Insured Mobile Number
>- **PackageName :** Name of the Medical Tests
>- **AppointmentDate :** Medical Tests Date
>- **ApptTime :** Medical Tests Time
>- **VisitType :** Home Visit or Diagnostic Center Visit
>- **ProviderName :** Diagnostic Centre Name
>- **ProviderState :** Diagnostic Centre State
>- **ProviderCity :** Diagnostic Centre City
>- **AppointmentStatus :** Current starus of Appointment


# ⭐ `Let's Do it in Python` :
>We will first build the logic and will explain and make the program. And after the we will make a function to repeat this daily task, make it simple for the account manager who is not well verse with python and save the time.
>1. In first python notbook we will explain the entire process.
>2. In second we will make a function to repeat this daily task, make it simple for the account manager who is not well verse with python and save the time.
