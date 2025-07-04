# university-database

# **World Universities Data by Country**

This repository contains a JSON file listing higher education institutions worldwide, organized by country.

## **Data Source**

The data for this project is sourced from the following GitHub repository:  
https://github.com/endSly/world-universities-csv

## **File: universities\_detailed\_by\_country.json**

This JSON file provides a structured list of universities, colleges, and other higher education institutions, grouped by their respective country codes.

### **JSON Structure**

The main JSON object contains country codes as keys. Each country code maps to an array of institution objects.

{  
  "COUNTRY\_CODE": \[  
    {  
      "name": "Institution Name",  
      "country": "COUNTRY\_CODE",  
      "city": null,  
      "type": null,  
      "ownership": null,  
      "accreditation\_status": null,  
      "website": "http://www.institution-website.edu/"  
    },  
    // ... more institutions for this country  
  \],  
  "ANOTHER\_COUNTRY\_CODE": \[  
    {  
      "name": "Another Institution Name",  
      "country": "ANOTHER\_COUNTRY\_CODE",  
      "city": null,  
      "type": null,  
      "ownership": null,  
      "accreditation\_status": null,  
      "website": "http://www.another-institution.edu/"  
    }  
  \]  
}

### **Field Descriptions**

* name: The official name of the higher education institution.  
* country: The two-letter ISO country code where the institution is located.  
* city: The city where the institution is located. **(Note: This field is currently null as the information was not available in the source CSV.)**  
* type: The type of institution (e.g., "University", "College", "Polytechnic"). **(Note: This field is currently null as the information was not available in the source CSV.)**  
* ownership: Whether the institution is "Public" or "Private". **(Note: This field is currently null as the information was not available in the source CSV.)**  
* accreditation\_status: The accreditation status of the institution. **(Note: This field is currently null as the information was not available in the source CSV.)**  
* website: The official website URL of the institution.

## **Usage**

You can use this JSON file for various purposes, such as:

* Building a directory of universities.  
* Data analysis related to global higher education.  
* Developing applications that require a list of educational institutions.

## **Limitations**

Please be aware that the city, type, ownership, and accreditation\_status fields are currently unpopulated (null) in this dataset because the original world-universities.csv file did not contain this specific information. To enrich the dataset with these details, additional data sources would be required.
