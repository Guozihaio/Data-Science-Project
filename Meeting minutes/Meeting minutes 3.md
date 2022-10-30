# Meeting Agenda and Minutes

Meeting Title: Project Kick-Off Meeting

Date: 30/03/2022

Time: 12:00-13:00

Attendees: Eunice Lee, Enes Makalic, Hamideh Anjomshoa, Kesha, Zihao,Xiaohan,Kexin,Sirui

______________________________________________________________________________________________________

**Item: Introductions**

**Allocated time: 10 minutes**

**Notes:**

Eunice: PhD in liver surgeon
A lot of research work has been looking at diffierent ways of allocating livers for transplantation and how to optimize that process
Enes:PhD in AI ML
work mostly as a statistician in various sort of medical or statistical genetics type problems

**Item: Project Scope/Overview**

**Allocated time: 10 minutes**

**Notes:**

- Donors - have different medical issues/liver quality etc
Pool of patients who need livers - different characteristics / boundary values / reasons for needing a transplant / age etc
- Match the donor to a recipient
- The point of this project is to look at different allocation policies: whether allocating according to the sickest patient or whether we're kind of allocating according to who's got the most benefit from transplant.
- looking at posttransplant outcomes, whether that's going to result in the most survival or whatever we're trying to maximize -- optimize his process
- In order to do that, we will create a simulation which is able to simulate the outcomes from different sorts of allocation policies.
- The idea behind the core is to take exsit sort of medical variables or measurements of patients and use them to predict the patient's **survival** in various ways. That sort of prediction model then becomes a score in terms of ranking patients for liver transplant .
The score is essentially more or less a prediction model based on various variables selected by whoever designed the score

**Item: Expected Deliverables/Outcomes**

**Allocated time: 10 minutes**

**Notes:**

- Predicting survival with uncomplete data(crucial part of the simulation of this project) -- statistical and data science or other type approaches -- useful tool(graphical) to simulate various transplant policies
- Shiny applet or a web app with user input boxes, button of running simulation, some  descriptive statistics, graphs, crfompare the scores etc. Want to see what happens when you change variables, values in the simulation.

**Item: Timelines**

**Allocated time: 10 minutes**

**Notes:**

- Start with fortnightly meetings, later on move to monthly.
- Next meeting do a little presentation on that we have learned on the transplant and some of the key issues

**Item: Communications**

**Allocated time: 10 minutes**

**Notes:**

**Kesh:** Is there a lot of work that's being done that studies the survival rate post the allocation? Because there could be data that we can use for how we can allocate our models?
**Eunice:** At the moment, we look at it just needs based so who's sick as patent first and that post transplant outcome isn't really considered in that. And certainly, it seems like a fair system if you can consider those transplant outcomes at the same time.

**Kesh:** we go into the project that for fixed variable. We can not change or add something new?
**Eunice:** we should keep it simple and just stick to what's out there and what's currently well validated and medical certainly as well validated. After that, we can start exploring different variables and adding in different scores and seeing what happnens.

**Zihao:** You mean we need to develop a software?
**Ans:** Shiny applet or a web app with user input boxes, button of running simulation, some  descriptive statistics, graphs, compare the scores etc.

**Zihao:** Do we just need MELD as the predictive model?
**Eunice:** We should start with MELD score and then gradually add other things if necessary

**Kesh:** One of our baseline approaches be to how compare each model and see how it works and what could be the best situation and we build on top of that, Or should we just like go on track and do our own data science perspective, and then come back and compare it?
**Eunice:** Both are important. start with what's out there first and see how it works might be easier. And after that, look at different ways that you can do things. So these scoring systems are all basically just prediction survival prediction models. We need a system to sort of discuss . You have to simulate  outcomes that may or may not have happened in real life. To be flexible in what you're doing to look at different models, different ways of simulating this image ones come up with what might be realistic outcomes.

**Supervisor:** So based on the data, you want students to go back and create a new survival analysis based on the data OR you want them to rely on whatever you have at the monment and look at the scenario based on the model? There are two things we need to do. Validate those ranks that you are mentioning survival rates, do you want them to go back and create new rank? Or you want to focus on those ranks and create those scenarios?

**Enes:** In both seem reasonable. Patient's survival is the sort of key metric that determines who getsa liver or who dosen't. You can use existing survival times to your simulation, but you can also kind of do a survival analysis to fit whatever model you like to the survival times and use the model
instead in your simulation.

**Item: Next Steps**

**Allocated time: 10 minutes**

**Notes:**

Go through literature -- come up with questions about the topic and the literature -- share data -- looking at some descriptive measures of the data, trying exploring an order -- come up some ideas
