# Shark-Attacks

## Beginning
 - Clean up dates:  
    - Utilize Case ID to create a new Date column and reformat. All dates prior to 1975 was dropped along with rows with dates that could not be determined. 
 - Initital cleanup of Activities: 
    - Began to group similar activities together such as "Surfing." More detail cleaning saved for later.    
 - Export to new csv file to use for analysis 
 
## Analysis:
   Location Analysis:
     - Finalized cleaning of Location, Country, and Area columns, created bins for time periods. 
     
     Questions: 
     - What location has the most shark attacks, focusing on USA? 
     
     ![image](https://user-images.githubusercontent.com/84548295/128611264-572bde1d-4af1-4e22-8676-d9c78027bd20.png)
     
     ![image](https://user-images.githubusercontent.com/84548295/128611271-519e4042-a6b9-4bf2-9c4e-e63a4f669d23.png)
       
     - Does the season of the year affect the likelihood of being attacked?
        
   Victim Analysis: 
     - Finalized cleaning of Type, Activity, Sex, Age, and Fatal Columns. Reorganized Injury column to remark type of injury: Severe, Minor to Moderate, None. 
     
     Questions: 
     - Which gender is attacked the most? 
     
     ![image](https://user-images.githubusercontent.com/84548295/128611331-2d7cf768-0a17-467a-9b22-a5f76d885cba.png)
 
     - Which activity results in the most shark attacks? 
     
     ![image](https://user-images.githubusercontent.com/84548295/128611368-0f5735e0-2727-43dc-a6d0-ea35a76a1b3d.png)

     - Which gender provokes attacks the most? 
     
     ![image](https://user-images.githubusercontent.com/84548295/128611372-3cec2c78-0356-45f2-8474-93e6086e9f9e.png)

     - Are there more injuries when attacks are provoked? 
     
     ![image](https://user-images.githubusercontent.com/84548295/128611376-0fdc5819-6882-413f-95be-43d046dd5baf.png)

     - Are most attack injuries severe? 
     
     ![image](https://user-images.githubusercontent.com/84548295/128611380-717938c7-d3bb-4542-be67-29f9745e1db8.png)

     - Which age group have the most fatalities? 



   Shark Analysis:
     - Finalized cleaning of Species column. Utilized cleaned Fatal column and merged Fatal and Species 
     
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
* API

## Contributors 
Andy: https://github.com/andyob715
Jake: https://github.com/JakeRose689
Stacey: https://github.com/staceyj118
