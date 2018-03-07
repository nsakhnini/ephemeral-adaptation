# ephemeral-adaptation
Ephemeral adaptation experiment mockup prepared as a solution for the assignment RS1 for the Spring 2018 CS422 class at UIC. 
For the RS1 Assignment I chose the "Ephemeral Adaptation: The Use of Gradual Onset to Improve Menu Selection Performance." (link: https://dl.acm.org/citation.cfm?doid=1518701.1518956)
I chose the ephemeral adaptation experiment because I think it is interesting to explore, hands-on, how does the adaptation affects the performance.
I found the idea of fading-in for some of the items interesting and I wanted to explore it more.
In this experiment, the user use two types of menus: Traditional and Ephemeral. 
Traditional Menu is the usual menu everyone who deals with computers deals with. 
Ephemeral Menu is a menu where some of the items appear before the others based on recent and the frequency of items. 
In the experiment, the time between the appearance of first item and last item in a menu is 500ms (1/2 second). 
In the experiment, the user does 8 practice trials and 126 actual trials for each menu.

For this assignment, I have not discussed it with anyone. The code is completely my work by my own self. 
I used the Bootstrap library and the logging code given by the instructor in AS1.

The Video: https://youtu.be/gsGhEkgD6XI
The experiment representation: https://nsakhn2.people.uic.edu/ephemeral/
The Code Repo: https://github.com/nsakhnini/ephemeral-adaptation

In my experiment, I sequenced the tasks as follows:
1. The user starts with an introduction to the experiment.
2. The user starts a practice session for the control experiment (Traditional menu). This session consists of 8 trials.
3. The user starts the actual control experiment and completes 126 trials.
4. The user starts a practice session for the ephemeral experiment and completes 8 trials.
5. The user starts the actual ephemeral experiment and completes 126 trials.
6. The user completes a survey.

The experimental parameter for my experiment is the ephemeral time, or the time elapsed between the appearance of first item and last item in a menu.
The default for this experiment is 500ms. But, you can change that by changing the "fadeInTime" variable in experiment.html
Also, the number of trials can be changed by changing "taskTrialNum" and "practiceTrialNum" in experiment.html

In each trial, the data collected is as follows:
1. Time interval from between when the user opens the correct menu until he or she chooses the correct item in milliseconds.
2. The number of times the user clicks a wrong menu as an integer.
3. The number of times the user clicks a wrong item as an integer.

For the feedback collected from this experiment, it falls int two parts as follows:
1. Experiment-related feedback: 
	>7-point Likert scales to collect the users feedback on distinctiveness, helpfulness, distraction, difficulty, satisfaction, efficiency and frustration.
		Reason: To capture the user's experience and know what they think and how their experience was.
	>Comparative ranking of the two menu conditions
		Reason: To let the users give their opinion about their experience after comparing both menu styles.
2. Demographics:
	>Age and Gender:
		Reason: To capture interesting findings that might arise relating these two measures with the menu experiment.
	>Computer Experience:
		Reason: Because the experience of a novice user will different since he/she might not be familiar as much with the traditional menus comparing to an expert user.



