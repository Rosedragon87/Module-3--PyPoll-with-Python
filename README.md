# Module-3--PyPoll-with-Python
Challenge 3 Homework

#Election Analysis

The purpose of this election audit is to help Seth and Tom figure out who the winner of the election will be and gathered the information requested from them in order to figure out the analysis. The election commission requested we find out which county had the highest turnout and who the top 3 candidates were and who has the most votes.

# Election Audit Results

![Election Results](https://github.com/Rosedragon87/Election_Analysis/blob/main/Election%20Results.png)

# Summary

The code written can be used for other elections if the commission would like to use it by modifying certain lines of the code for future elections. 

1. For example, if the results were written in a different file then it is recommended to update the filename listed in the code. 
  The code used was: "file_to_load = os.path.join("Resources", "election_results.csv")". 
  The "election_results.csv" was the file used to load relative data to establish our results. 

2. If the commission used the same file we used to same results, the results would not be what they expect if they use the code for future elections. Since we saved the results to the file named "election_analysis.txt" using the code "file_to_save = os.path.join("analysis", "election_analysis.txt")". It is recommended to change the last part of the code to whatever new text file name the commission would like to use for each year's election results. Also , be sure to create the text file prior to executing the code otherwise an error will occur. 

Overall, it will sort through the data and provide the necessary information like the results shown in the image above.





