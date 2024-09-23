# The National Structure Inventory (NSI) API in Python
Author: Mark Bauer

# 1. Introduction
This project is intended to demonstrate how to use the National Structure Inventory (NSI) API in Python. To learn more about the NSI API, please visit the [API Reference Guide](https://www.hec.usace.army.mil/confluence/nsi/technicalreferences/latest/api-reference-guide) and the [NSI Documentation](https://www.hec.usace.army.mil/confluence/nsi).

**About NSI:**    
The National Structure Inventory provides a publicly accessible point-based structure inventory with attribution for the structures of the United States. The NSI facilitates risk assessments and analysis by providing an initial estimate of the classification of the structures and their exposed population and property. The predominant usage of the NSI has been for analysis of flood hazards, but sufficient data exists on each structure to evaluate losses for other hazard types.

The base level NSI is generated from an analysis of building footprints, parcel datasets, Census data, and other sources. The points in the database are attributed with estimates describing the structure such as occupancy type, foundation type and height, number of stories, and exterior construction materials. Additionally, the structures include estimates of the population day and night over and under the age of 65 and the depreciated replacement costs of the structure and contents. Data has been generated of consistent quality for all 50 states and the District of Columbia.

The NSI was originally developed by the United States Army Corps of Engineers to aid its Dam and Levee Screening program. The data is frequently paired with consequence and risk models such as the Hydrologic Engineering Center's Flood Damage Analysis software or USACE's LifeSim software to generate annualized flood damages and life loss risk estimates. The NSI has been utilized to make estimates of the expected annual damages for each structure in the United States using products like the Fathom flood data as published in Nature Climate Change. The most recent version of the data is now publicly available and has since been integrated into FEMA's HAZUS database. The NSI has potential in a variety of use cases from multi-hazard risk assessments to risk communication among other applications.

Source: https://ui.adsabs.harvard.edu/abs/2022AGUFM.U53A..02R/abstract

# 2. Notebook
- Explore how to fetch NSI data via the API: [api-examples.ipynb](https://github.com/mebauer/national-structure-inventory-examples/blob/main/api-examples.ipynb).

# 3. Additional Resources
NSI API:  
- National Structure Inventory: https://www.hec.usace.army.mil/confluence/nsi/
- API Reference Guide: https://www.hec.usace.army.mil/confluence/nsi/technicalreferences/latest/api-reference-guide
- Technical Documentation: https://www.hec.usace.army.mil/confluence/nsi/technicalreferences/latest/technical-documentation
- NSI on GitHub: https://github.com/HydrologicEngineeringCenter/NSI

Community Resources:  
- National Structure Inventory: Cataloging the Built Environment for Natural Hazard Risk Assessments - AGU Fall Meeting 2022: https://ui.adsabs.harvard.edu/abs/2022AGUFM.U53A..02R/abstract
- Updates to the National Structure Inventory - HEC Newsletter (2022): https://www.hec.usace.army.mil/confluence/hecnews/spring-2022/updates-to-the-national-structure-inventory
- National Structure Inventory 2022 USACE - ArcGIS Online: https://www.arcgis.com/home/item.html?id=ae3dcb0fe38e4d3287ab9233a9d35c3e
- Google Earth Engine (GEE) Community Resources: https://gee-community-catalog.org/projects/nsi/

# 4. Say Hello!
Feel free to reach out for further discussions.
- LinkedIn: [markebauer](https://www.linkedin.com/in/markebauer/)  
- Portfolio: [mebauer.github.io](https://mebauer.github.io/)
- GitHub: [mebauer](https://github.com/mebauer) 
