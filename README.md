# MS_Fabric_LAB_4
# Ingest Data with a Pipeline in Microsoft Fabric

This project demonstrates how to ingest, transform, and load data into a lakehouse using **Microsoft Fabric**.  
We create a complete ETL pipeline combining **Copy Data** activities and **Apache Spark notebooks** within Fabric.

## 🚀 Project Steps
- **Create a Workspace**: Set up a new workspace with Fabric trial or premium capacity.
- **Create a Lakehouse**: Organize your data with proper structure.
- **Create a Pipeline**: 
  - Use Copy Data activities to fetch sales data from an HTTP source.
  - Save the file to the lakehouse under a designated folder.
- **Create a Notebook**:
  - Read the ingested CSV file using Spark.
  - Apply transformations (add `Year`, `Month`, split `CustomerName` into `FirstName` and `LastName`).
  - Save the cleaned data into a Delta table.
- **Enhance the Pipeline**:
  - Add a step to **delete old files** before ingesting new data.
  - Chain the notebook execution after the file ingestion.
  
## 🛠 Technologies Used
- Microsoft Fabric
- OneLake
- Apache Spark (PySpark)
- Delta Lake tables

## 🧹 Cleanup
After testing, remove the workspace to avoid unnecessary costs.

## 📎 Useful Links
- [Learn Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/)
- [Microsoft Fabric Trial Access](https://app.fabric.microsoft.com/home?experience=fabric)

---

✅ This lab exercise demonstrates building a modern, scalable ETL process inside Microsoft Fabric!

