# CIS 1051 Final Project Fall 2020

# Title: 2017 Hurricane Season Simulator

# Created By Meet Patel & Shou Li


### Project Overview:

For our project, my partner and I expanded upon the hurricane tracker lab. We added simulations for all the hurricanes in the Starter File we recieved for the hurricae tracker lab and researched information about each of the hurricanes, which displays after a hurricane path is simulated. We also added different sounds to all the hurricanes and changed the gif image of the hurricane(s) to Donald Trump. When you run the program, some instructions pop up and you are then prompted to enter the name of the hurricane you would like to see the simulation for. Furthermore, by entering "total" instead of a hurricane name, information about the whole 2017 hurricane season is displayed and entering "done" kills the program, displaying a small "exited program" message to let you know the program has finished executing.  


### Obstacles/Challenges We Faced:

One of the main ostacles my partner Shou and I faced was figuring out how to add sound to the hurricane siulations. We browsed the internet and decided on using the "playsound" module to add sound(s) to the hurricane simulations. In order to install the playsound module, we needed to install pip, a python package manager, which was a real pain to download. there were simply too many ways you could download pip and some dowload methods only worked for Wndows while other worled for Mac OS which further complicated things as my partner is on Windows and I am on Mac OS. We boh figured out how to download pip and my partner Shou was successfully able download and use the playsound module to add sound to the hurricane simulations. For me, the playsound module wouldn't work and I kept on getting a "module not found" error message so I ended up using the buil-in module "subprocess" to add sound to the hurricane simulations on Mac OS. Adding sound to the simulations was further complicated as the sound files we wanted to use were too large and wouldnt work so it took numerous guess and check attempts to shorten the files tp the right size. 

Originally we wanted to implement a feature so if you enter "1" on the keyboard it would simulate the first hurricane of the 2017 hurricane season and entering "2" would simulate the second one that occured and so on but were unsuccessful. We tried using the "keyboard" module, which also needs to be installed using pip, but were unable to figure out to properly use it so we resorted to prompting the user to enter the name of the hurricane they would like to be simulated. 

### Things We learned: 

We learned many problem solving strategies throghout the creaton of our final project. We learned that there are multiple ways to aceive the same result as I used the subprocess module to add sound and my partner Shou used the playsound module from pip to implemt sound to the hurricane simulations. We also learned how to install things onto our computers using terminal (on mac) and command prompt (on Windows). We used terminal/command prompt to install pip on our computers and used pip from within terminal and command prompt to install different modules. 


### What We Enjoyed: 
Throughout our final project journey, we both enjoyed collaborating together via zoom. We formed a great friendship and were able to accomplish everything we wanted to, besides the entering "1" on the keyboard to simulate the first hurriacne mechanism, on our final project. Overall, we had a great time!
