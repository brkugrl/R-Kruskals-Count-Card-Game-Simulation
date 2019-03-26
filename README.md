# R-Kruskals-Count-Card-Game-Simulation
#After changing the face value, I saw that the distribution changes. This game
#reaches the same card more often when the face values is smaller. For example when face value
#is 1 approximately %80 percentage of the trials end up in the same card 10 times,%5 percentage 
#of the trials end up in the same card 9 times. However, when face value is 9
#approximately %32 trials end up in the same card 10 times,approximately %12 trials end up in the same 
#card 9 times(These percentage values might change if we simulate 
#this program again). This means that, if we increase the number of jumps between cards, 
#this game tends to end up in the same card more often. Because the average step increase
#as we decrease the face value. The density of the average step(1/average step) 
#decreases as average step increases. So probability of hitting same card increases as density
#decreases. This means that if we decrease the face value, the probability of hitting same card
#increases. So our results are true.
#Same thing happen for 104 cards.If we have 104 cards, average number step is higher than the 
#previous case. Assume that number of step is 17. Assume that probability of hitting a 
#key card is 0.1. Probability of not hitting the key card is 0.9(key card is card that will end up
#int the same card). If we multiply 0.9 by 17 times, it will be very close to 0.
#This means that probability of miising a key card is nearly 0. We reach same card %98 percent 
#for the most cases. So our result is true.
