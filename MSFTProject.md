**Linking to a Published Project**


To connect Microsoft Project Online to Power BI and build reports, follow these steps:  

### **Prerequisites**  
- Ensure you have a **Power BI Pro** license.  
- You must have access to **Project Online** (part of Microsoft Project for the Web).  
- Use **Power BI Desktop** for the initial connection and publishing.  

### **Steps to Connect Microsoft Project Online to Power BI**  

#### **1. Open Power BI Desktop**  
- Launch **Power BI Desktop** on your computer.  

#### **2. Get Data from Project Online**  
- Click **Home > Get Data**  
- In the search bar, type **OData Feed** and select it.  
- Click **Connect**  

#### **3. Enter the OData Feed URL**  
- Use the following format for your Project Online OData URL:  
  ```
  https://[YourTenant].sharepoint.com/sites/pwa/_api/ProjectData
  ```
  Replace `[YourTenant]` with your actual tenant name.  

- Click **OK**  

#### **4. Sign in with your Microsoft Account**  
- Select **Organizational Account** and sign in using your Office 365 credentials.  
- Click **Connect**  

#### **5. Select the Data Tables**  
- Power BI will load a list of available tables from **Project Online**.  
- Select the tables you need, such as:  
  - **Projects** (Project-level data)  
  - **Tasks** (Task-level details)  
  - **Assignments** (Resource assignments)  
  - **Resources** (People assigned to tasks)  

- Click **Load** to import the data.  

#### **6. Transform and Build Reports**  
- Use Power Query Editor to clean and transform the data if needed.  
- Create visualizations and dashboards based on your project data.  

#### **7. Publish to Power BI Service** (Optional)  
- Click **File > Publish > Publish to Power BI**  
- Choose a **workspace** in Power BI Service.  
- After publishing, set up a **scheduled refresh** in Power BI Service to keep the data up to date.  

---

### **Alternative: Use the Power BI Project Online Content Pack**  
If you want a pre-built dashboard:  
1. Go to [Power BI Service](https://app.powerbi.com)  
2. Click **Apps > Get Apps**  
3. Search for **Project Online Content Pack**  
4. Install it and configure the OData connection.

5. ![image](https://github.com/user-attachments/assets/a3efd61f-36e2-46d3-9636-a629a9cf2ac2)


Alternatively use the MSFT Project App

![image](https://github.com/user-attachments/assets/e6a347c6-dbc9-4f79-853d-cc970a713a61)



![image](https://github.com/user-attachments/assets/c4d7beb0-72e5-427b-ba67-f5e6b03e1105)

