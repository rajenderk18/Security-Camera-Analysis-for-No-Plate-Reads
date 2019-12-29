# Security-Camera-Analysis-for-No-Plate-Reads

**Goal:** To identify the “NOPLATE” read from the data of security center Camera.

**Data Extraction:** We get all the data from the security center Camera, Merge them into one file using merge-csv.com and give it a significant name based on their location, date and time.

**Data Transform:** All the correction like duplicate header, null values, missing data are corrected in this phase.

**Data Load:** We connect the csv file to Tableau for further analysis of the data.

**Analysis:** We use the “Tableau” for analyzing the percentage of plate reads and no reads for one week data.

 

## **Final Analysis results**

Here are all the results for week 2 Dec- 6 Dec 2019

### Number of no plate reads vs Plate Reads for 1 week (2-6 Dec)

![Number of no plate reads vs Plate Reads for 1 week (2-6 Dec) NIGHT Only (6pm-6am)](https://user-images.githubusercontent.com/35782113/71551918-5339a300-29bf-11ea-8807-975d28121945.png)

 

### **Number of no plate reads vs Plate Reads for 1 week (2-6 Dec) NIGHT Only (6pm-6am)**



![Number of no plate reads vs Plate Reads for 1 week (2-6 Dec)](https://user-images.githubusercontent.com/35782113/71551919-5339a300-29bf-11ea-946c-083c5046b143.png)
[Security Camera Number Plate Analysis.docx](https://github.com/rajenderk18/Panther-Calculator/files/4007717/Security.Camera.Number.Plate.Analysis.docx)
![All Data for one week in tabular form](https://user-images.githubusercontent.com/35782113/71551920-53d23980-29bf-11ea-8397-8c3cbb3e78b2.png)
![All Data for one week in tabular formpercentage](https://user-images.githubusercontent.com/35782113/71551921-53d23980-29bf-11ea-8e25-5971641a325e.png)

 

### How busy Each Garages is? (Based on one week data)

PG5(39.3K)>PG3(29.8K)>PG1(29K)>PG6(26.6K)>PG2(18K)>PG4(15.8)

 ![How busy Each Garages is(Based on one week data)](https://user-images.githubusercontent.com/35782113/71551917-5339a300-29bf-11ea-8341-5f83e5b3505c.png)



### How busy Each Device is? (Based on one week data)

![How busy Each Device is (Based on one week data)](https://user-images.githubusercontent.com/35782113/71551922-53d23980-29bf-11ea-9f44-de753a91ca6f.png)

 

## **Final Insights**

 

### **Very Bad (% of No Plate Read>10%)**

- PG3 South East      Exit(41%),
-  PG4      South East Exit (23%),
-  PG3      North East Entry (22%),
- PG4 East Entry      (14.5%),
-  Pg1 East      Entry (13.5%),
-  Pg2 SE      Entry (13%)

 

### **Very Good (% of no plate Read)<2%**

- PG4 West Entry      (0%)
- PG4 West Exit      (0%)
- PG5 West Entry      (1.1%)
- PG6 East Entry      (1.5%)
- PG6 East Exit      (1.6%)
- PG6 West Entry      (1.6%)

 

 