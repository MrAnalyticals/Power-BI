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


Alternatively use the Microsoft Project Web App
The "Microsoft Project for the Web" Power BI template app is designed to connect Power BI to data stored in Dataverse for Project for the Web. However, if you're looking to connect Power BI to Project Online (formerly known as Project Web App), you should use the "Microsoft Project Web App" template app instead. This app allows you to import and analyze data from Project Web App in Power BI, providing insights to help manage projects, portfolios, and resources. ([appsource.microsoft.com](https://appsource.microsoft.com/en-us/product/power-bi-visuals/pbi_msprojectonline.pbi-microsoftprojectwebapp?utm_source=chatgpt.com))

To connect Power BI to Project Online using the "Microsoft Project Web App" template app, follow these steps:

1. **Install the App**:
   - In Power BI, navigate to the Apps section and select "Get apps" in the upper right corner.
   - In AppSource, search for "Microsoft Project Web App" and select "Get it now" to install.

2. **Connect to Your Data**:
   - After installation, open the app and select "Connect your data."
   - Enter your Project Web App (PWA) URL and site language.
   - Choose "oAuth2" as the authentication method and sign in with your PWA credentials.

Once connected, the app will import your data and provide a variety of visually rich report pages for portfolio, resource, and project overviews. ([learn.microsoft.com](https://learn.microsoft.com/en-us/power-bi/connect-data/service-connect-to-project-online?utm_source=chatgpt.com))

If you prefer to use Power BI Desktop, you can connect to Project Online data via the OData feed. This method involves entering your PWA OData feed URL into Power BI Desktop and authenticating with your organizational account. Detailed instructions are available in the Microsoft Learn documentation. ([learn.microsoft.com](https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-project-online-connect-to-data?utm_source=chatgpt.com))

In summary, to connect Power BI to Project Online, it's recommended to use the "Microsoft Project Web App" template app or connect via Power BI Desktop using the OData feed. 


![image](https://github.com/user-attachments/assets/e6a347c6-dbc9-4f79-853d-cc970a713a61)



![image](https://github.com/user-attachments/assets/3823456a-e9f6-4db3-a986-69ee7e5c8e12)


