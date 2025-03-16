# Overview : Lab 13 Understanding Tickets Using Spiceworks
This repository documents my home lab focused on Understanding Tickets Using Spiceworks within a VirtualBox environment. The lab aims to explore how Spiceworks can be used to manage IT tickets, track service requests, and streamline support workflows.

## Objectives
- Learn Spiceworks Ticketing System: Set up and configure Spiceworks to create, manage, and track IT support tickets.
- Ticket Management: Understand how to categorize, prioritize, and assign tickets to team members within a virtualized network environment.
- Reporting and Analysis: Learn how to generate reports on ticket resolution times, trends, and overall support performance.

## Documentation
In this lab, we will focus on Spiceworks ticketing services, which is free to use, and explore how Remote Support can assist users.

To begin, we will create an account for Spiceworks using an email. After the account creation, we will set up a domain, which will be the same domain we've been using in our previous labs, tobifash.com. Once the account and domain are ready, we will launch the IT Cloud Helpdesk through the IT tools tab at the top of the Spiceworks interface.

From there, we will dive into the ticketing system to understand how it works and how we can use it for managing IT support requests.

<br> 

![Screenshot 2025-03-16 at 12 08 54 AM](https://github.com/user-attachments/assets/6ffa0cf1-47d6-4b5d-a1b5-ad9cc06ffdbc)

<br> 
1. Here on the Spiceworks dashboard, we have a centralized interface for IT professionals. It provides a clear overview of key metrics, including new, open, and unassigned tickets. Additionally, it displays network inventory, device health, and alerts, giving us a comprehensive snapshot of the IT environment and ongoing support activities.

<br> 

![Screenshot 2025-03-15 at 12 19 52 AM](https://github.com/user-attachments/assets/ac83f9bb-8456-4542-868d-900b51789c4e)

<br>

2. Let's take a look at creating a ticket and the properties involved in the process. Start by selecting the Ticket tab on the left-side panel, then click on the blue "New Ticket" button at the top right.

<br> 

![Screenshot 2025-03-16 at 12 11 00 AM](https://github.com/user-attachments/assets/7317533f-4deb-4754-b97e-9ac5d1de7de7)

<br> 

3. Let's break down each of the properties of a ticket:

- Organization: This refers to the domain or company that the helpdesk is working for, ensuring that tickets are associated with the correct organization.
- Contact: This is the person who is reporting the issue. It could be an employee, user, or external contact who is reaching out for assistance.
- Assignee: The person or group assigned to fix the issue. This is typically an IT support member or a specific team who will handle the resolution.
- Summary: A brief description of the issue, explaining the situation at hand. This provides a quick overview of the ticket for anyone reviewing it.
- Priority: This indicates the urgency of the issue. Depending on the situation, priority can range from low to high, helping to set expectations on when the issue will be addressed.
- Category: This classifies the ticket into a specific group, such as Email, Hardware, Network, Software, or other types. It helps to organize tickets by their nature and directs them to the right team for resolution.

  <br> 

  ![Screenshot 2025-03-15 at 12 22 30 AM](https://github.com/user-attachments/assets/71313001-0d4b-4a5e-8655-63029ec1930b)

<br> 

4. Let's simulate a helpdesk environment using Spiceworks' ticketing system. Our objective is to demonstrate efficient ticket management by creating, assigning, prioritizing, and resolving tickets, while properly documenting each step of the process.

To get started, we need to add a helpdesk technician who will be responsible for handling the tickets. Follow these steps:

1. Go to the Settings panel on the left side.
2. Select Employee Administration.
3. Click on Add Employee.
4. Assign the role of Tech to the new helpdesk technician to ensure they have limited access to tickets and settings.

   <br> 

   ![Screenshot 2025-03-15 at 12 22 30 AM](https://github.com/user-attachments/assets/c819b6b6-5a7a-4325-bb3e-bcceeb0c540e)
<br>

5. We will need to use a real email but creating email should be easy. Once we create an employee we then select “Add employee”.

<br> 

![Screenshot 2025-03-15 at 12 24 42 AM](https://github.com/user-attachments/assets/26e4c487-a686-4dac-ab31-cdc699662cf7)

<br>

6. Next, let's create a sample issue. In this scenario, a user named Bob is experiencing difficulty logging into his computer, Desktop2, because his account is locked out. To report the issue, Bob will send an email to our Helpdesk.

Bob should use the following email address to submit his request: help@tobifash.on.spiceworks.com. This email address can be found under the General tab, associated with the domain SimoTech.com.

Once we receive Bob’s email, we'll create a new ticket in the system to document and address his problem.

<br> 

![Screenshot 2025-03-16 at 12 16 25 AM](https://github.com/user-attachments/assets/efc34da3-4a31-4031-9bfa-fad58aca9664)

<br> 

7. In this step, I'll act as Bob and send an email to the domain's Helpdesk to report the issue. The email will be directed to the Helpdesk address, and we should now receive it in our Spiceworks ticketing system. Once the email arrives, it will automatically generate a new ticket that we can manage and resolve.

<br> 

![Screenshot 2025-03-15 at 12 27 20 AM](https://github.com/user-attachments/assets/b3288e62-b5b6-447d-9318-e72ddbe58107)

<br>

8. Now that our ticket has been issue, we can accept the ticket and assignee to our helpdesk tech “sam fasesin”.

<br> 

![Screenshot 2025-03-15 at 12 30 19 AM](https://github.com/user-attachments/assets/a9595be5-1c8a-4bfe-be6c-4d19ecc4de17)

<br> 

9. Once we receive the email, we'll click Accept to start working on the ticket. Next, we'll assign the ticket to our Helpdesk technician, sam fasesin. We'll set the Priority to High since the user cannot log in and is unable to perform any work. Additionally, we'll set a Due Date for the following day to ensure prompt resolution. For the Category, we'll leave it as "Other."

<br>

![Screenshot 2025-03-15 at 12 33 56 AM](https://github.com/user-attachments/assets/e8fcab98-0ee7-41ba-ba09-d8701501c2fa)

<br> 

10. We can also set up tasks to guide our Helpdesk technician. I've implemented three tasks for Kevin to assist him with the account lockout ticket. Additionally, we can track the time spent working on this issue by selecting the “+15m” option.

<br> 

![Screenshot 2025-03-16 at 12 20 49 AM](https://github.com/user-attachments/assets/a3a3874d-0963-46d1-ac8c-115a8e2679c1)

<br> 

11. Our helpdesk will contact Bob with issue being fix after everything is sorted then we can finally close the ticket.

<br> 

![Screenshot 2025-03-16 at 12 21 53 AM](https://github.com/user-attachments/assets/5b14c464-6cb9-47eb-bf15-f73595cd28af)

<br> 

12. We can check our past tickets by selecting the drop down on “Open” to “Closed”.

<br> 

![Screenshot 2025-03-15 at 12 34 38 AM](https://github.com/user-attachments/assets/8a6587c5-eb3d-47fa-a161-510eba1457ea)

<br> 

13. Spiceworks offers a unique feature that enables remote support for users in need of assistance. To access this feature, go to Tools and then select Remote Support.

<br> 

![Screenshot 2025-03-15 at 12 35 04 AM](https://github.com/user-attachments/assets/bdcb6e4d-961c-489f-80e0-504cc6801b2a)

<br> 

14. Next, select Start Remote Session, and a code will be generated. This code should be provided to the user so they can join the remote session.

<br> 

![Screenshot 2025-03-15 at 12 36 25 AM](https://github.com/user-attachments/assets/b40cb699-58ad-46ec-b2ae-57aa74e1fdea)

<br> 

15. Now, let's log into Bob’s account on Desktop2 VM to join the remote session. First, we need to connect to the internet since we're on a static IP. Follow these steps:

 1. Go to Devices → Network → Network Settings → then select NAT.

 2. Open the Control Panel → choose View Network Status and Tasks → then Change Adapter Settings.

 3. Right-click on Ethernet → select Properties.

 4. Double-click on Internet Protocol Version 4 (TCP/IPv4), then change the setting to Obtain an IP address automatically.

<br> 

![image](https://github.com/user-attachments/assets/eeae10bd-bfc1-4b5d-88f4-576961fa9d26)

<br>

16. Next, let's open Firefox, which we've already installed using PDQ Deploy. In the browser, navigate to https://join.zoho.com/145437173 and enter the session ID. Click on Agree and Download, then run the ZA_Connect.exe file to join the remote session.

![image](https://github.com/user-attachments/assets/3c79bbec-1b28-41c1-aa8a-b25bdaba4ed8)

<br> 

17. Now, back in our Spiceworks browser, we have full remote access to Desktop2 VM on Bob’s account.

<br> 

![image](https://github.com/user-attachments/assets/fb44e34b-c16e-4f7a-b6d9-3becc48a0360)

<br> 

18. With Remote Support, there are many tools at our disposal. One useful feature is the Chat option on the left side of the panel, which allows us to communicate directly with the user. The chat box will open on the right side of the screen.

<br> 

![image](https://github.com/user-attachments/assets/3864c760-3786-4a9e-9445-12235fb793a6)

<br> 

19. On our Desktop2 VM, we can see that the Chat feature is available for the user to communicate with the Helpdesk.

<br> 

![image](https://github.com/user-attachments/assets/be34b812-5637-4aee-9fbe-b69b70695f6d)

<br> 

20. For tools, we can launch different commands such as opening up command prompt.

<br> 

![image](https://github.com/user-attachments/assets/505c2221-e00c-430f-81d1-1945888d5f12)

<br> 

21. We can also open up Device Manager.

<br> 

![image](https://github.com/user-attachments/assets/e0ed4a6b-2f45-4646-9d9d-d7a426d30351)

<br> 

22. To elevate to Admin Mode, use your Administrator credentials. First, select the session on the left side panel, then click on Elevate to Admin Mode. For the user, enter Administrator@tobifash.com and provide the password.

<br> 

![image](https://github.com/user-attachments/assets/4d4f67fb-1450-4a14-a126-01497d28a453)

<br> 

23. With Admin Mode enabled, we can now use the session tool Send Alt+Ctrl+Del.

<br> 

![image](https://github.com/user-attachments/assets/bba64f3d-2e17-4c71-b06a-58ef7887001e)

<br> 

24. These are just a few of the many features Spiceworks Remote Support offers to assist Helpdesk teams in providing support to users. Now, we can exit the remote session on our Desktop2 VM and switch the network back to the static IP.

With that, we've successfully completed this home lab, gaining a solid understanding of how the Spiceworks Ticketing System and Remote Support Tool work. <br> 

👉 [Next Lab 14 : Delegate Control and Account Lockout Management](https://github.com/tobifash0/Delegate-Control-and-Account-Lockout-Management)
