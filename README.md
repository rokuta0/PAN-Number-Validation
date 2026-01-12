# PAN Number Validation

This project focuses on **cleaning and validating Indian PAN numbers** from a dataset. The goal is to ensure that each PAN number follows the **official format** and classify it as **Valid** or **Invalid**.

---

## **What I Did**

### **Data Cleaning**
- Handled missing PAN values  
- Removed duplicate records  
- Trimmed extra spaces  
- Converted PAN numbers to uppercase  

### **PAN Validation Rules**
- Must be exactly **10 characters long**  
- First **5 characters** are letters  
- Next **4 characters** are digits  
- Last character is a letter  
- No repeated adjacent characters  
- No complete alphabetical or numerical sequences  

### **Categorization**
- **Valid PAN**  
- **Invalid PAN**  

### **Summary Report Generated**
- Total records processed  
- Total valid PANs  
- Total invalid PANs  
- Total missing or incomplete PANs  

---

## **Tools & Technologies Used**
- **SQL** – for data cleaning and validation logic  
- **Excel** – input dataset  
