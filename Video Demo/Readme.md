#1.Introduction:
"Hi, I'm Satya, and my team member is Niharika.
This is our ServiceNow project titled 'Asset Management Portal', developed as part of our internship."

##2. Table & Fields
"We started by creating a custom table named u_asset_inventory.
Inside this table, we defined the following key fields:

Asset Name

Type (choice field: Laptop, Mobile, Monitor, etc.)

Status (choice field: Available, Assigned, Under Repair, etc.)

Purchase Date

Warranty Expire

Assigned To

Number

##3. Creating Asset Records
"Next, we added demo asset records to test our module.
Each asset has its name, type, warranty date, and assigned status.
This helps with record tracking and reports."

##4. UI Actions
"We implemented UI Actions like Mark as Lost, Send for Repair, and Assign Asset.
When we click on these actions, the Status field updates accordingly to show the current state of the asset."

##5. Scheduled Job
"We wrote a script in Scheduled Job to send alerts when a warranty is about to expire within 30 days.
We tested the script using Scripts – Background and confirmed the logs in the system logs."

##6. Reports
"We also created a Report by right-clicking the Status column and visualizing it as a pie chart.
This report helps understand the asset distribution and health."

##7. Closing
"Thank you for watching our project demonstration.
We hope this Asset Management Portal helps in improving efficiency and automation in asset handling."
