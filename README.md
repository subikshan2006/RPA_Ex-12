# RPA_Ex-12

# Ex-12-Automate-an-unattended-Robot-using-Orchestrator

~~~
Name : PRAKASH.C
Reg.No : 212223240122
~~~

## Aim
To automate and execute an unattended Robot in UiPath Orchestrator by publishing a project from UiPath Studio, creating necessary assets and triggers, and running the process remotely.

## Materials Required
UiPath Studio (connected to Orchestrator)

UiPath Orchestrator Account (Cloud or Enterprise)

UiPath Assistant

Robot provisioned and licensed in Orchestrator

Stable internet connection

## Procedure

### Step 1: Create and Publish a Project
Open UiPath Studio and create a sample project (e.g., a Message Box or any automation).
Save the project and click "Publish" to upload it to Orchestrator (Tenant Processes Feed).

### Step 2: Log in to UiPath Orchestrator

Go to https://cloud.uipath.com and log in.
Choose your Orchestrator tenant.

### Step 3: Provision Robot and Machine
Go to Tenant > Machines: Add a Standard Machine with the same name as your device (check in Studio via Help > License Details).
Under Tenant > Folders > Manage Access, ensure your user is assigned with proper roles (e.g., Robot role).
Go to Tenant > Robots and create a Unattended Robot:
Link it to the correct machine and user.
Assign it to your folder.

### Step 4: Create Process in Orchestrator

In Automation > Processes, click Add Process.
Select the published package from the dropdown.
Choose version, folder, and display name.
Click Create.

### Step 5: Create Trigger to Schedule the Robot
Go to Automation > Triggers.
Click Add Trigger:
Select your process.
Set Trigger Type to Time.
Choose the time, frequency (Once, Daily, etc.).
Click Create.

### Step 6: Monitor Execution
In Jobs, you can monitor the status (Pending, Running, Success, Faulted).
View logs, time stamps, and robot execution details.

## OUTPUT:
A process, published from UiPath Studio, is executed automatically without manual intervention via an unattended robot in Orchestrator.

![12-1](https://github.com/user-attachments/assets/8bfaf22c-1f4a-43a8-b4cc-5d718f0e740d)

![12-2](https://github.com/user-attachments/assets/4ab9faa8-bb76-41de-a1b4-04af648bb859)

![12-3](https://github.com/user-attachments/assets/062f9232-f369-4478-a557-9226857c993b)

![12-4](https://github.com/user-attachments/assets/879eae72-9a71-498c-a664-a0a63ca2e96c)

![12-5](https://github.com/user-attachments/assets/a30e439d-567a-44c2-a493-b0d138ec76f9)

![12-6](https://github.com/user-attachments/assets/4f018f9a-632a-4eab-bec3-eb7f9e0b72b6)

![12-7](https://github.com/user-attachments/assets/4224026a-dad4-472c-971f-a4861a63f9b1)

![12-8](https://github.com/user-attachments/assets/0f3e312e-0f07-4f75-91b2-826602f3f927)


## Result
The automation process was successfully published, triggered, and executed as an unattended job using UiPath Orchestrator. This setup ensures automation can run without human presence at scheduled times.
