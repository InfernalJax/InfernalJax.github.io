## Welcome

*This is currently in development*

This is a website for one of Western Washington University's CSCI 436/536 Technology for Social Good class projects.
This is Group #4's "Healthy Eats" app, which started development Winter Quarter of 2021 with Dr. Shameem Ahmed.

Students:
- Jeremy Hummel (hummelj3@wwu.edu)
- Taichen Rose (rosej25@wwu.edu)
- Simone Sawyer (sawyery@wwu.edu)
- Jax Rounds (roundsj@wwu.edu)





### Background

#### What is the problem and why is it important? 

The problem we are addressing is improper dietary habits across the globe. Data from the World Health Organization show that 1.1 billion people don't get enough calories in their diet and another 1.1 billion get too many calories [1]. Lower-income households compared to households of higher income have lower quality, non-diverse diets. These lower-income households often take in fewer fruits and vegetables, and consume more sugar-sweetened drinks and highly processed foods, resulting in a lower quality diet which directly impacts their health and wellbeing.  

This is an important problem because there are many individuals globally who do not maintain a healthy and nutritious diet. For so many individuals or families who are living on a tight budget, buying healthy food simply isn’t considered. To many individuals, a healthier option can appear more expensive or it’s a challenge to know what recipes to use that fit within their budget. Other individuals tend to reach out to highly processed foods or sweetened beverages out of ease and budget.  

In 1987, 2.1 million Americans died, and it was later found that a poor diet was a primary cause of two-thirds of those who died[1]. Research also shows that diet is involved in one-third of cancers (digestive organs)[3]. As addressed previously, many individuals understand the importance of a healthy diet, but many don’t know where to start or are aware that they can still make healthy meals with a fixed budget. Fixing this problem would help to reduce the consumption of highly processed foods and sweet beverages and increase the household count of having nutritious and affordable meals. We want to give individuals a choice to get on track to a healthier diet, and also become a role model for their children in the importance of healthy meals.  


#### Who are the target users? Why should they care? 

Our target users are people who have access to mobile devices and aren’t currently consuming healthy nutritious meals; but specifically, we are targeting users who are interested in cooking quality meals within their budget, but are unsure of where to start learning. These users care about the problem because improper dietary habits can not only impact the individual in the long run but could potentially also affect their children’s dietary habits. By using our application, they can turn their eating habits around, potentially avoiding health issues down the road.

#### What is our solution? 

Our solution to this problem is to give users an application, Healthy Eats, which will generate healthy meals for themselves and their families based on their budget and the ingredients they already have. By having this application display this information, individuals and their families can benefit from a healthier diet, which in the long run can lead to a healthier life. We are planning to achieve SDG goal three, “Good Health and Wellbeing.” This goal will be achieved since we are directly impacting the user and their family in eating a healthier and nutritious meal. 

We developed our application using Android Studio, as it was one of the most easily accessible technologies for mobile development and allowed us to reach most mobile users due to the popularity of Android systems.

#### How is your solution different than the existing solutions?

The vast majority of similar solutions all have their best features locked behind a paywall. This came in the form of either a one-time purchase, or a monthly subscription charge. Considering that our target user is on a budget, we want to strive to create an app that is free-to-use with budgeting options at the forefront.

We also recognize that many of our users will be new to cooking their own food, and unlike the other solutions who assume a level of cooking expertise, we want to be able to cater to those with less cooking knowledge with our app. While other apps don’t have a way to show improvement in the cooking skills of the user, we hope to accomplish this by adding a leveling system, like other skills-based apps such as Duolingo, so that our users will feel a sense of accomplishment as they progress through each recipe.


#### References
1. http://encyclopedia.uia.org/en/problem/133563
2. https://www.healthypeople.gov/2020/topics-objectives/topic/social-determinants-health/interventions-resources/food-insecurity 
3. https://www.betterhealth.vic.gov.au/health/ConditionsAndTreatments/cancer-and-food#:~:text=Diet%20is%20just%20one%20of,can%20cause%20or%20cure%20cancer.


### Research Methodology

#### Systematic Literature Review

In preperation for designing our first prototype of the app, our team conducted a brief literature review to try learn about what other reseachers have found are most important when designing solutions that encourage healthy eating.

We reviewed 8 papers in total on the subject of promoting healthy eating via some ICT implementation or with specific constrains, such as a budget.  

Overall, we noticed a couple of main points that we wanted to address:
- Inequality in nutrition - Lower income houeholds tend to eat less healthy than higher income households due to time/money constraints
- Gamification is key - Providing incentives to eat healthier has shown fantastic results in changing targetted behavior and to keep users engaged with the ICT
- Everyone is different - healthy proposals promising a "one size fits all solution" are going to fail, plans need to be adjustable
- Knowledge is power - while strict budgets make healthy eating more difficult, it is possible with proper educational resources on the subject

After our literature review we knew that when designing our app we need it to be targetted towards lower-income households, and to provide them with basic education about how to succesfully eat healthy on a budget. We also needed to find a way to keep our users engaged and coming back to the app, so some form of gamification elements should be included.

#### Initial Prototype

![Prototype 1 Collection](/Proto1 Collection.png)

#### System Analysis

Along with our systematic literature review, we also conducted some systems analysis to explore what other software developers have tried, and what worked really well and what features seemed to fall short.

We analyzed 12 existing ICT's aimed at promoting healthy eating, some of which are still being maintained and supported, like "MyFitnessPal", and others that have died out and are no longer accessible, like "Food On The Table".

Overall we found that a lot of the apps were designed with one particular aspect of healthy eating in mind. MyFitnessPal for instance has a lot of awesome features pertaining to calorie counting, and ensuring that the user is consuming their recommended macro's each day, and are on track to reach their weight goals in the future. Other apps had budgeting as the main focus, or perhaps were simply focused with providing a lot of healthy recipes. Other solutions prioritized easy to make recipes, for example. And so our app was designed to be a fusion of all the necessary components to eat cheap and healthy.

Many of the systems we looked at also included some form of social media element, allowing the user to interact with their friends so they could share recipes or compete in fitness challenges. A lot of these implementations felt very, "tacked on" to the underlying existing system, and so we decided to not implement any similar social media feature in our design.

#### Updated Prototype 2

![Prototype 2 Collection 1](/Proto2 Collection1.png)

![Prototype 2 Collection 2](/Proto2 Collection2.png)


#### User Study

After we had version 2 of our prototype designed, it was time to conduct a user study to get feedback about our app's design. As a team we came up with a questionnaire that would provide us with feedback on our prototype, what the user likes, doesn't like, how they would change things, and what their experience has been with similar apps of this nature in the past. 

We ended up conducting 4 interviews, with each one providing us valuable insight as to how we should move forward with the development of Healthy Eats.

Luckily all of our interviewees were rather content with our prototype. There was one underlying trend however, and that was that each person wanted more customization and control over their version of the app. One interviewee wanted more filtering options so they could search for recipies by "high protein" for example, and another wanted to be able to customize the homescreen so it would have widgets that they might find more useful. 

The ability to rate each recipe after cooking it was also very well recieved, the simplicity of the rating system comprising of "unhappy faces, meh faces, and happy faces" was appealing to our interviewees. There was also an expressed interest in the "leveling system" feature of our app, even though the specifics were yet to be worked out.
 

#### Updated Protoype 3

![Prototype 3 Collection](/Proto3 Collection.png)


### Final Build

Discuss in detail the final prototype (every feature); Give pictures as needed.
Discuss all the technologies/software/API you used.
Provide the link of your code repository (e.g., GitHub)

### Video Walkthrough
Upload a short demo video (what you already submitted for this course)

### Future Work
How could your work be extended and why would that be useful?
