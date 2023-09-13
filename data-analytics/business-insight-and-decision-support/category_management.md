<!-- dc-ref-arch-metadata : 
    {
        "id": "ref-arch-category-management",
        "name": "Category Management",
        "shortDescription": "Analyze category performance for digital/online sales by combining external source systems like Google Analytics and sales, discounts, and stock data from SAP systems.",
        "archDiagramLink": "https://github.com/SAP/sap-btp-reference-architectures/blob/main/data-analytics/business-insight-and-decision-support/images/CategoryManagement.png",
        "tags": "Data Analytics, Cross, Cloud",
        "category": "Data Analytics",
        "labels": "Data Analytics, Cross, Cloud"
    }
dc-ref-arch-metadata  -->
<!-- dc-ref-arch-detail-page-start -->
## **Category Management**

Use Case Category: **Business Insight & Decision Support**

Use Case Pattern: **Operational Performance Managment**

Specific Use Case: **Category Management**

### Description

Analyze category performance for digital/online sales by combining external source systems like Google Analytics and sales, discounts, and stock data from SAP systems. 

**Improve customer experience** by uncovering potential revenue growth on certain items and understand the trends of secific product categories in a holistic and user friendly manner. Historical and real-time product sales & discounts are integrated right from your e-commerce solution alongside product characteristics and inventory data. Perform self-service automated analysis of category performance to improve customer experience for your online sales by understanding your most critical performance KPIs as well as your most important sales factors.

**Increase sales and profitability** by exploring KPIs like Online traffic for products across different regions or times of the day. Understand real-time consumer sentiment analysis based on real-time social media feeds.

**Improve tactical decision-making** by perform live category analysis. Create data models  for self-service analysis of category performance for digital. A holistic view of category performance of live on the fly analysis spanning multiple real-time data sources increases sales and profitability
by understanding the customer journey and enhancing tactical decision making for category performance managers.

With a data federation architecture, customers can leave data in its source system and access it in one location without replication. With this architecture customers can combine their Google BigQuery and SAP data to derive new insights.



### Architecture

![BTP Solution Architecture](images/CategoryManagement.png)

---

:link: [BTP reference architecture (.drawio/diagrams.net) source file](architectures/CategoryManagement.drawio)
<!-- dc-ref-arch-detail-page-end -->

### BTP services / SAP solutions
<!-- dc-ref-arch-services-start -->
[SAP Analytics Cloud](https://discovery-center.cloud.sap/serviceCatalog/sap-analytics-cloud?region=all)

[SAP Datasphere](https://discovery-center.cloud.sap/protected/index.html#/serviceCatalog/sap-datasphere?region=all)
<!-- dc-ref-arch-services-start -->
<!-- dc-ref-arch-resources-start -->
[SAP Datasphere](https://www.sap.com/germany/products/technology-platform/datasphere.html)

[Google Cloud Platform BigQuery](https://cloud.google.com/bigquery)
<!-- dc-ref-arch-resources-end -->

### References
<!-- dc-ref-arch-related-missions-start -->
[Enable Category Management with BigQuery and SAP Datasphere | SAP Discovery Center](https://discovery-center.cloud.sap/missiondetail/3666/3709/)

[Integrate Google BigQuery and SAP Datasphere](https://discovery-center.cloud.sap/missiondetail/3409/3449/)
<!-- dc-ref-arch-related-missions-end -->