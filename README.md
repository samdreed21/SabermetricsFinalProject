# Samuel Reed Sabermetrics Final Project
                
## Situational Pitching Behavior – Explanation    ##         
<p>
Situational Pitching Behavior (SPB) is a new statistical tool that offers users the ability to analyze a pitcher’s performance in a variety of situations. This statistic allows a user to enter the name of a pitcher and the current situation that pitcher is in (in regards to how many runners are on base). The application will then analyze how that pitcher has performed in that situation in the past and will present the user with the data generated. This data includes the frequency of different types of pitches that pitcher throws in the specific situation, the pitcher’s rate of balls/strikes/hits in that situation, and the location over the plate that the pitcher is most likely to throw the ball in that specific situation.    
	</p>
	<p>
	SPB is different from traditional statistics in the fact that it analyzes very specific situations and has more dynamic applications. Some of the applications of this statistic could include evaluating a lineup of batters based on how a pitcher will behave in the situations those batters are likely to generate. It could also be useful to determine if a pitcher typically falters under pressure in certain situations and could allow managers to have the pitcher take a certain action such as intentionally walking someone or throwing a specific pitch based off of their success rate in that situation.       
	</p>
	<p>Currently there are not any statistics that allow a user to evaluate a pitcher’s performance in specific situations like SPB. In fact, the traditional statistic that comes closest conceptually to SPB are the various evaluations of what makes a batter a “clutch hitter”. This statistic focuses on specific situations and how batters perform in those situations instead of the statistics that are made up of data compiled from the entire career of the batter. This is very similar to SPB, but for batters. SPB could evaluate how a pitcher performs in a situation such as where the bases are loaded and a pitcher needs to be able to handle the immense change in win potential that would come with a batter getting a hit. Statistics such as ERA and WAR provide a sound understanding of the player’s overall performance, but if a pitcher needs to be subbed in a very specific situation, SPB could be incredibly useful. On the other side of the inning SPB could also be very useful for batters. If a batter has a deep understanding of how the pitcher is likely to perform throughout the course of the at-bat, that batter will be more equipped to swing in the proper area or try to force a walk out of the pitcher.  </p>    
	<p>
	As mentioned above, comparing SPB to traditional baseball statistics is not very straightforward. For my statistical comparison in this project I decided to look at mlb.com’s ranking of the most clutch pitchers of all time (https://www.mlb.com/news/best-clutch-pitchers-in-mlb-history-c298312438). I then pulled out certain examples of these “clutch” pitchers and put them into my SPB application in various situations that would intuitively require “clutchness”. From this I took the data of how they behaved in various clutch situations and processed that data to get the rate of how many strikes they threw compared to balls and hits they threw in these clutch situations. I also compared some traditionally rated clutch pitchers to other traditionally rated clutch pitchers. All of these demonstrates can be found in the code base or my video submission. 
	</p>
	<p>
	The evaluation of how pitchers perform in high pressure situations also provides very useful insight to batters in the way mentioned above. Batters can use this data to have a confident understanding of how their plate appearance will go while facing a certain pitcher in a specific situation. 
	</p>

## Repository Contents ##
	- SPB_Explanation.docx: this is the 2-3 page explanation of my project, also found in README
	- SPB_Final_Video.mp4: MP4 File of final video submission
	- Sabermetrics_Final_Presentation.ppx: Powerpoint presentation used in final video
	- Samuel_Reed_FP_Part1.dox: Short writeup of idea for part 1
	- Samuel_Reed_Situational_Pitching_Behavior.ipynb: Jupyter notebook with entire codebase
	- final_pitching_data.zip: zip of all of the data used in the Jupyter notebook.


## How To Run ##    
  1) Download and unpack the most final_pitching_data.csv into the working directory
  2) Run the latest version of Samuel_Reed_Situational_Pitching_Behavior.ipynb (Do not run the statcast query if you unpacked the zip). Scroll down to see the driver code to run the main project. All cells must be compiled, but running the statcast query cell will take a very long time.
  

## Youtube Link For Video Submission #
 https://www.youtube.com/watch?v=qVnlKPYElo4&feature=youtu.be
