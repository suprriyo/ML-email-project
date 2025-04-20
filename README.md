Q. What percentage of users opened the email and what percentage clicked on the link within the email?

Ans:
The opened rate is 10.35% .
The clicked rate is 2.12% .

Q. The VP of marketing thinks that it is stupid to send emails in a random way. Based on all the information you have about the emails that were sent, can you build a model to optimize in future how to send emails to maximize the probability of users clicking on the link inside the email?

Ans:
Absolutely, it is nonsense to send emails randomly which leads to cost rise. We’ve trained a predictive random forest model to identify users most likely to click on links in our emails. After evaluating the model, we found that the optimal threshold for identifying clickers is 15%.
In other words, if the model predicts that a user has at least a 15% chance of clicking, we send them the mail, otherwise not.

Q. By how much do you think your model would improve click through rate (defined as # of users who click on the link/total users who receive the email). How would you test that?

Ans:
When we are sending emails randomly, the click rate was 2.12%. After we trained our model, we got a precision score of 26% when a thresold of 0.15 is choosed. Our Click through efficiency improves by 11 times after sending emails to predicted users , predicted by the random forest model rather than sending emails to people randomly.

Q. Did you find any interesting pattern on how the email campaign performed for different segments of users? Explain.

Ans:
Upon doing data analysis, I found that people used to click on link inside emails higher on Wednesday but tends to click in links low in Friday.
Also the one who opened up the email has and 0.42 correlation score with the one who clicked the link inside the email.
