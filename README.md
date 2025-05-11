# Tableau-Based-Cloud-Pricing-Simulator

![image](https://github.com/user-attachments/assets/e1901c41-490c-4871-8a82-ef4ab5ef3059)
![image](https://github.com/user-attachments/assets/c5adca95-00d9-45c7-9b42-8f0847913018)


Porject Link: https://public.tableau.com/app/profile/tilak.jilka/viz/CloudPriceSimulator/CloudCostSimulator?publish=yes

This Tableau dashboard helps users simulate and compare estimated cloud service costs across **AWS**, **Azure**, and **GCP** based on selected configurations. It allows users to filter by provider, service, service type, region, and usage size (hours or GB) to view the breakdown and comparison of instance, storage, and transfer costs.

## 📊 Features

- 🔄 **Dynamic Filtering** – Choose from Cloud Provider, Service, Service Type, and Region set to Oregon US West for ease of calculation.
- 🧮 **Parameter-Based Cost Estimation** – View estimated cost based on input usage (hours or GB).
- 🧭 **Service Lookup Table** – Explore all available services and sub-options for each provider.
- 📉 **Cost Comparison Charts** – Instantly compare similar service types across providers.
- ⚠️ **Input Validation** – Displays custom error messages when invalid provider-service combinations are selected.

---
## 🚀 How to Use

1. **Open the Dashboard in Tableau Public/Desktop**  
   Import the `cloud_services.csv` data source and open the main dashboard file.
2. **Select Your Configuration**
   - Use the dropdowns at the top to select:
     - Cloud Provider (AWS, Azure, or GCP)
     - Service (e.g., EC2, Blob Storage, S3)
     - Service Type (e.g., t2.micro, Archive, etc.)
     - Region (e.g., US WEST OREGON)
   - Use the slider to input usage amount:
     - Hours for compute services
     - GB for storage or transfer services
3. **View Costs**
   - Instance, storage, and transfer costs appear in separate value sheets.
   - Compare your selected service with similar services across other cloud providers.
   - Lookup all services using the Service Lookup Table.

4. **Check for Errors**
   - If an invalid configuration is selected, an error message will appear prompting you to correct the input.
---

## 📁 Files

- `cloud_services.csv` – Core dataset with service types and unit costs.
- `Cloud_Cost_Simulator.twb` – Tableau workbook file with complete dashboard.

## 🛠️ Technologies

- Tableau (Desktop/Public)
- CSV Data Processing
- Parameter and Set Controls
- Calculated Fields & Logic
- Interactive Filters and Dynamic Sheets

## 📌 Note

This dashboard is designed as a simulation tool and does **not** reflect real-time or exact cloud pricing. It is intended for educational or estimation purposes only.

---

## 👤 Author

Tilak Jilka – [LinkedIn](https://www.linkedin.com/in/tilak-jilka/)  
Graduate Student in Computer Science | Data Visualization & Analytics Enthusiast

