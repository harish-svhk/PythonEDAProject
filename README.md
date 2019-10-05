# Breast cancer

### IMPACT ANALYSIS OF Lymph Nodes on Cancer
<p align="center">
  <img width="400" height="300" src="images/BreastCancer.jpg">
</p>

## INTRODUCTION
Breast cancer is cancer that develops from breast tissue. Signs of breast cancer may include a lump in the breast, a change in breast shape, dimpling of the skin, fluid coming from the nipple, a newly inverted nipple, or a red or scaly patch of skin.

__TNM staging system__ The most commonly used tool that doctors use to describe the stage of the cancer. Doctors use the results from diagnostic tests and scans to answer these questions:<br/>

  __Tumor (T):__ How large is the primary tumor? Where is it located?
  __Node (N):__ Has the tumor spread to the lymph nodes? If so, where and how many?
  __Metastasis (M):__ Has the cancer spread to other parts of the body? If so, where and how much?
   The __“N”__ in the __TNM staging system__ stands for __lymph nodes__.<br/>
  
  __Clinical staging:__ Evaluates the lymph nodes __before the surgery__, based on other tests and/or a physical examination.
  __Pathologic staging:__ Evaluates the lymph nodes __after the surgery__, which is a more accurate assessment.
  
      - NX: The lymph nodes were not evaluated.
      - N0: Either No cancer was found in the lymph nodes or Only areas of cancer smaller than 0.2 mm are in the lymph nodes.
      - N1: The cancer has spread to 1 to 3 axillary lymph nodes and/or the internal mammary lymph nodes.
      - N2: The cancer has spread to 4 to 9 axillary lymph nodes. Or it has spread to the internal mammary lymph nodes, but not the     axillary lymph nodes.
      - N3: The cancer has spread to 10 or more axillary lymph nodes. Or it has spread to the lymph nodes located under 
      
__Problem Statment :__ 
- How many survived after 5 years and how many died before 5 years?
- How the Positive axillary nodes (Pathologic staging) and survivals are related?
- How Survivals and Age and Axillary nodes are related?
- How the survivals and year of operation related?

## DATA
| Column Name             | Description                                                                                             |
| -------------------     |:-------------                                                                                           | 
| __Age__                 | Age of patient at time of operation (numerical)                                                         | 
| __Years_of_operation__  | Patient's year of operation (year - 1900, numerical)                                                    |  
| __Pos_axillary_nodes__  | Number of positive axillary nodes detected (numerical)                                                  | 
| __Status__              | Surival status (class attribute) (1=patient survived 5 years or longer,2=patient died within 5 year)    |     
## Data Profiling
- In the upcoming sections we will first __understand our dataset__ using various pandas functionalities.
- Then with the help of __pandas profiling__ we will find which columns of our dataset need preprocessing.
- In __preprocessing__ we will deal with erronous and missing values of columns. 
- Again we will do __pandas profiling__ to see how preprocessing have transformed our dataset.

## Data preparation
- There is no discrepancies found in the data 
- Year of operation is of two digits
- Found __44.4% zeros__ of __Pos_axillary_nodes__, but these are also __valid__ data, which indicates early stages of cancer – Either No cancer was found in the lymph nodes or only areas of cancer smaller than 0.2 mm are in the lymph nodes.
- Converted two digits year of operation to four digits
- Create a function to categorize different pathological stages of cancer depedning on Positive Axillary Nodes
<p align="left">
  <img width="400" height="150" src="images/Data.PNG">
</p>
### CONCLUSION

