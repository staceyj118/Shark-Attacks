# Shark-Attacks

## Beginning
 - Clean up dates:  
    - Utilize Case ID to create a new Date column and reformat. All dates prior to 1975 was dropped along with rows with dates that could not be determined. 
 - Initital cleanup of Activities: 
    - Began to group similar activities together such as "Surfing." More detail cleaning saved for later.    
 - Export to new csv file to use for analysis 
 
## Analysis:

### Location Analysis:
Finalized cleaning of Location, Country, and Area columns, created bins for time periods. 

Questions: 
  - What location has the most shark attacks, focusing on USA? 
	
	![image](https://github.com/staceyj118/Shark-Attacks/blob/main/maps/shark_attack_coordmap.png?raw=true)

	![image](https://github.com/staceyj118/Shark-Attacks/blob/main/maps/shark_attack_heatmap.png?raw=true)
        

	As expected, coastal attacks on both coasts spanned from north to sourth in the US. Interestingly, there were a handful of attacks that happened inside of acquariums, whih accounts for the landlocked attacks. From an intensity of attack perspective, Florida had a much higher cluster of attacks than anywhere else in the United States. Further analysis should be conducted to determine whether population, tourism or other factors contribute to that higher cluster of attacks.
     	
  - Does the season of the year affect the likelihood of being attacked?

	![image](https://github.com/staceyj118/Shark-Attacks/blob/main/maps/seasonal_attacks.png?raw=true)
	
	The summer and the fall generated the highest number of attacks compared to winter and spring. Over time, the summer and fall appeared to grow at a greater proprortionate rate than expected compared to the other seasons. This could be due to changing weather conditions, changes in tourism or other factors. Further analysis could be conducted to determine why these seasons continue to grow at a higher rate.
	
  - What month of the year has the most shark attacks, focusing on USA?

	![image](https://github.com/staceyj118/Shark-Attacks/blob/main/maps/shark_attacks_by_month.png?raw=true)
	
	The summer months yielded the highest proportion of attacks compared to the average. On the surface this seems intuitive due to the nature of tourism and the desire for more people to "hit the beach when its hot". Further analysis could be done to undestand how temperature/weather impacts shark food supply locations.
        

### Victim Analysis: 
Finalized cleaning of Type, Activity, Sex, Age, and Fatal Columns. Reorganized Injury column to remark type of injury: Severe, Minor to Moderate, None. 
     
Questions: 
   - Which gender is attacked the most? 
     
![image](https://github.com/staceyj118/Shark-Attacks/blob/main/Male_vs_Female.png?raw=true)

	Males are attacked the most by a long-shot. The unknown is one individual where translation from the info within the data could not be made. 
 
   - Which activity results in the most shark attacks? 
     
![image](https://github.com/staceyj118/Shark-Attacks/blob/main/Activities.png?raw=true)

	Surfing and swimming are the most popular activity to be attacked by the shark. This makes sense as those are the activites most individuals participate in while at the beach. 

   - Which gender provokes attacks the most? 
   
![image](https://github.com/staceyj118/Shark-Attacks/blob/main/Gender_vs_Provoked.png?raw=true)

	Males do provoke sharks the most, which would explain why they were also the most attacked as seen above. 

   - Are there more injuries when attacks are provoked? 
     
![image](https://github.com/staceyj118/Shark-Attacks/blob/main/Fatality_vs_Provoked.png?raw=true)

	Surprisingly, most attacks are unprovoked. 

   - Are most attack injuries severe? 
     
![image](https://github.com/staceyj118/Shark-Attacks/blob/main/Injury.png?raw=true)

	Luckily, most attacks are minor to moderate severity. Ratings were assigned as follows: Severe - loss of life, broken bones, loss of limb, missing person; Mild to Moderate - all other injuries including scrapes, bumps, bites without broken bones or severed portions of the body; None - No injuries reported, conspiracy/speculation without proof; Unknown - section in report left blank.



### Shark Analysis:
Finalized cleaning of Species column. Utilized cleaned Fatal column and merged Fatal and Species 
     
Questions: 
   - What shark species attack the most? 
     
![image](https://user-images.githubusercontent.com/84548295/128611416-f34b6cdb-b4f0-4df0-b8f6-86a8ca66db77.png)

   - What shark types have the most fatality? 
     
![image](https://user-images.githubusercontent.com/84548295/128611424-6279d1aa-45fe-4af5-8ca6-c644aa59761d.png)

## Libraries Used
* Pandas
* Numpy
* Matplotlib
* Scipy
* gmaps API
* json

## Contributors 
* Andy: https://github.com/andyob715
* Jake: https://github.com/JakeRose689
* Stacey: https://github.com/staceyj118
