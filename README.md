# F1-Data-Analysis
Accessing Formula -1 Race's 🏎 historical data using Python  . Analyzing the 2021 Abu Dhabi Grand Prix with the Fast F1 library
The 73rd season of the Formula One World Championship or F1 commenced in Bahrain on 20th March 2022.
Fierce battles are being witnessed between the ten teams for the ultimate title. Nevertheless, the races are not without their fair share of drama, anticipation, sweat, tears, and emotions.
It is what makes Formula 1 the most exciting as well as the most popular motor racing competition.
If you follow Formula1, you already know this, but what if it is the other way around? Should you even read further? Definitely! That's because the Formula 1 cars generate a tremendous amount of data, and where there is data, there are data scientists 😃.
This article will look at a Python library that enables you to access F1 historical timing data and telemetry very easily. 
This extracted data can then be utilized to perform various sorts of analysis. As an example, we'll look at the Abu Dhabi Grand Prix 2021. The race was pretty special on many accounts. Firstly, it was the season's final race, and most importantly, it was to decide the new F1 World Champion.
The two leading contenders — Max Verstappen and Lewis Hamilton- had 369.5 points coming into the race, and this race was going to decide who would ultimately take the crown. In a way, the race was what could be called the most intense title fight in years.


A quick guide to Formula 1
While this article is more focused on the data analysis part, I believe it will be worthwhile to introduce a few terms related to Formula 1 briefly.
However, you can skip over to the next section if you are well versed in the sport.
What is Formula 1?
Formula 1, also known as F1, is an international auto racing for single-seater formula racing cars. Formula 1 cars are the fastest road-course racing cars in the world. 
It is governed by the FIA — Fédération Internationale de l'Automobile or the International Automobile Federation. Ten teams consisting of twenty drivers compete every season for two Championship awards based on the points scored in the season.
The series of races conducted in a season together constitute the Grands Prix. The awards are as follows:
Drivers' Championship Award

World Drivers’ Championship standings before the Abu Dhabi Grand Prix| Image created by Author using free designs by Freepik
The driver with the most points at the end of a season is awarded the Drivers' Championship Award. Max Verstappen was ahead of Lewis Hamilton even though they had the same points because he had won more races (nine compared to eight).
Constructors' Championship Award

World Constructors' Championship standings before the Abu Dhabi Grand Prix | Image created by Author using free designs by Freepik
This award is for the constructors. According to FIA regulations,
"the constructor of an engine or chassis is the person (including any corporate or unincorporated body) which owns the intellectual rights to such engine or chassis."
Teams and drivers
The following table shows the current participating teams and drivers. Usually, there are 20 drivers, two per team.

Participating teams and drivers in 2021 Formula 1 Season | Table reproduced by Author from Wikipedia
Circuit
Circuits are the tracks that are built for conducting the races.

A circuit layout | Car vector created by macrovector — www.freepik.com
Lap
Lap refers to one complete circuit in a race, i.e., one trip around the entire track.
Race Weekend
A Formula One Grand Prix takes place over a weekend, and the various sessions are distributed as follows:

Race weekend schedule | Image by Author

Analyzing the 2021 Abu Dhabi Grand Prix data with Python

Python + Formula 1 | Image by Author using free designs by Freepik
Link to the Code notebook: https://bit.ly/3D0orp7
As mentioned earlier, the F1 race weekends generate a lot of data. Every car has 150 to 300 sensors on average, with the engine alone having close to 50 sensors. It is estimated that around 300GB of data per car is generated each Grand Prix weekend. This mind-boggling data contains immense valuable information. Careful analysis of this data can provide a competitive advantage to teams over others even before the car hits the track. What worked and did not in the past dictates future decisions like car design and other team strategies. The data is used to run hundreds of simulations to optimize the car setup. While managing the live data will not be possible with our humble infrastructure, post-race data can be downloaded and analyzed easily, thanks to a Python library called Fast F1.
