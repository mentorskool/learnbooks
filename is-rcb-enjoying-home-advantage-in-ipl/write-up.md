### <font color="019aff">Problem Statement</font> 

<hr style="height:1px;border-width:0;color:#cfcfcf;background-color:#cfcfcf">

**SportsWiz** is a **sports tech** startup which provides data driven analysis and strategic recommendations to IPL franchises to help them answer a number of questions related to team's performance, composition and strategy

You are a **Data Analyst** hired by **SportsWiz** and you'll be working with **Royal Challengers Bangalore** which is struggling at IPL for past few seasons

Your **job profile** consists of : 
* Devising questions, metrics, dimensions concerning the given problem statement
* Collect, clean and process the data and in the end build a dashboard which would help RCB to gather actionable insights which would in turn help them come up with strategies to form the best team, win against teams and hence add value to the franchise

* The batting coach of team RCB wants to understand whether their team is enjoying any home advantage in their matches or not? He has asked you the below question : 
  * Is the number of matches won by RCB is comparatively higher on home ground(Bengaluru) or away?
* He is looking for a simple table as shown below : 

<img src="http://drive.google.com/uc?export=view&id=1U8cgJ0ykoREXa-M2PhqtzEfhOUbmS-DH" width="200" height="150"></img>

* Perform the following tasks :  

  * In dataset **ipl_matches.xlsx**, For each of the columns **Team 1,Team 2, toss_winner and Winner**, fetch the team abbreviations from the **ipl_summary.xlsx** and save the new columns as **Team_1_Code,Team_2_Code,toss_winner_code and Winner_code**
  * Fetch the **Home_City** column from **ipl_teams.xlsx** into the dataset **ipl_matches.xlsx**
  * Create a new column called **ground_type**. This should have values **Home** and **Away** depending upon if the Winner of the match has won on its home ground or not
  * Now, prepare the table as expected by your batting coach

* Done? Not fully yet!
  * Your batting coach feels showing just the win numbers is not sufficient to assess whether the team is enjoying a home advantage or not. He would like to see **percentage of wins** under **Home** and **Away**. Please note, for this part you should use the dataset : **ipl_matches_long.xlsx**

    <font size="3" color="blue"><b>Psst...Think a while how you'll calculate the Win% here</b></font>

  * Below is the modified table which your batting coach is expecting :

<img src="http://drive.google.com/uc?export=view&id=1bZgxRB-QbIQC7dPrweYo5BDnygrGpPpQ" width="200" height="150"></img>

### <font color="019aff">Before you start</font> 
---------
Ensure you have the following items **ready** : 
* Access to **Microsoft Excel 2016 or above**
* Access to any screen recording software (**Zoom**, **Bandicam** etc.)
* Access to datasets required for this project. Download [here](https://msklbusinessdata.blob.core.windows.net/learnbooks-data/is-rcb-enjoying-home-advantage-in-ipl/data.zip)
* Access to the response sheet where you will be logging the outcomes of the project. Open [here](https://forms.gle/C1VcGKNx13Tb4A1m7)


### <font color="019aff">Skills to brush up</font> 

<hr style="height:1px;border-width:0;color:#cfcfcf;background-color:#cfcfcf">

Check the following references to quickly brush up the skills needed to solve the above stated problem : 
* Pivoting in Excel : [Here](https://www.youtube.com/watch?v=qu-AK0Hv0b4)
* Show value in Pivot : [Here](https://support.microsoft.com/en-us/office/show-different-calculations-in-pivottable-value-fields-014d2777-baaf-480b-a32b-98431f48bfec)
* Conditional statements in Excel : [Here](https://exceljet.net/excel-functions/excel-if-function)

What other questions you would ask the data to better address the problem statement at hand? 

Wish to discuss the solution to this problem and solve more interesting problems?

Join us on [Slack](https://join.slack.com/t/mentorclass/shared_invite/zt-cridbd9y-FZxvAZo4fqV5l1YRA3C05A) today!


