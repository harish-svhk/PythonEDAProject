# Breast cancer

### IMPACT ANALYSIS OF Lymph Nodes on Cancer
<p align="center">
  <img width="400" height="300" src="images/BreastCancer.jpg">
</p>

## INTRODUCTION
Breast cancer is cancer that develops from breast tissue. Signs of breast cancer may include a lump in the breast, a change in breast shape, dimpling of the skin, fluid coming from the nipple, a newly inverted nipple, or a red or scaly patch of skin.

Symptoms: Lump in a breast, change in breast etc.,
Risk factors: Female, obesity, lack of exercise etc.,
Treatment: Surgery, radiation therapy, chemot etc.,
Diagnostic method: Tissue biopsy

Lymph Nodes are small clumps of immune cells that act as filters for the lymphatic system. The lymphatic system runs throughout the body (like the circulatory (blood) system) and carries fluid and cells.If breast cancer spreads, the lymph nodes in the underarm (the axillary lymph nodes) are the first place it’s likely to go.The number of axillary lymph nodes can vary from person to person, ranging from 5 nodes to more than 30.Lymph node status is highly related to prognosis.

Lymph Node-negative means the axillary lymph nodes do not contain cancer.
Lymph Node-positive means the axillary lymph nodes contain cancer.


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


## PROJECT ANALYSIS
| Description | Analysis |
| --- | --- |
| Channels_Data.head | ![image.png](images/PrimaryMasterData.png) |
| Sample_Data | ![image.png](images/SampleUsers.png) |


### CONCLUSION

- From the analysis done it is deduced that the average cost would be around 340 Rs ( for an average of 28 paid channels selected with a Genre distribution of GEC (36%) ,Movies (14%) ,News (13%) ,Music (11%) ,Kids (12%) ,Infotainment (10%) ,Sports (3%) and Lifestyle (1%)).And keeping an variance of +/- 20% variance to get the range as __301.40 Rs to 370.40 Rs__.

- This indicates that the users will be seeing an increase in the cost of cable fees in the range of __50 Rs to 120 Rs__ when he is comparing it with his benchmark of __250 Rs__
 
- Below 2 options are suggested to help reduce this cost further.
   - Option 1 : As prescribed by TRAI – try to keep the channel list around 50. Filter out the list channels which are only absolutely needed and discard the ones which we seldom or rarely watch. This if done wisely can reduce the cost by 5-10 %. which means the 185 can be further reduced in the range of  __165 Rs__ (10%) to __175 Rs__(5%).

   - Option 2 : Use the pyPackRecommendation tool to achieve the benefits of using packs which offer lesser cost and try to reduce the cost by 10 to 20%. __140 Rs__(assuming a 20% reduction) to __158 Rs__(assuming a 10% reduction)__
The above 2 recommendations if implemented correctly would bring down the cost in the range of __295 Rs to 312 Rs__.  But, this is still an increase of 45 Rs to 60 Rs when compared with consumers benchmark of 250 Rs. 

- The final conclusion is that even after following TRAI's recommendation of keeping the channel count under 50 and using optimization tools such as pyPackRecommendation the user will still see an __increase cost of cable fees__ when he compares it with his benchmark of 250 Rs. However, it __will not increase 2-3 times more__ as feared if they follow TRAIs recommendation of chosing the right count of channels(around 50) and use the optimisation tools to further reduce the cost through Pack/Bouquet selections.

### FUTURE CONSIDERATIONS
Below are few impacts we see in future and study to conduct.

  - The cost is going to be playing a major role in customers choice of staying with a particular DTH or cable operator and once consumers realise the power of "Packs" and its benefits there will be natural migration to those DTH/Cable operator who offer wide variety (across languages and genre). One of the DTH operator who leads in the race is TataSky 
  - The consumers will also migrate to new DTH(Airtel,Tatasky etc ) if they dont provide transparency and ease of transactions. The worst affected will be the local cable operators as they are currently doing everything manual and this process takes a lot of time in implementing the new plans which is causing a heart burn among consumers. 
  - The above study was considered for south region, would like to do the same for north to see if there are major deviations which currently it is assumed to be none.
