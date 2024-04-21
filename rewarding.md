---
icon: credit-card
label: Rewarding
order: 1700
---

# Reward Allocation Algorithm

Through the use of rewarding mechanism, users at different levels (CAS, ADV, and PRO) are motivated to take part in various activities inside the application. Our goal is promoting environmental sustainability and community participation. Rewards are allocated to user as $EAAS tokens based on CO2 credit price and users's TIER and geolocation after 45/30/7 days of use. Activities include answering carbon-related and ESG questions, using the DePIN device (available only to Pro users), completing behavioural challenges, and recommending the app to others to create community. 

## Algorithms 

We use a methodical process to reward each user's based on their actions within the app. The algorithm's high-level summary is as follows:
- we Identify and define the activities that users can take to get rewards. These include but not limited to learing and completing ESG related information and tasks, Carbon, using DePIN hardware(PRO users), behavioral actions, and referrals. 
- CO2 score values are assigned differently for each category (ESG, Carbon, Depin, Behavioral, and CC) according to the user's tier. The higher the tier - the more precise information about users sustainability practices eaas.global acquires which means these variables affect how many CO2 credits the user earns for performing actions in each category.
- We add total numbers of tasks performed by users in each category and multiply it by the CO2 score values determined by the user’s tier 
- Users are rewarded with $EAAS tokens (Ri) based on their total CO2 credits earned, multiplied by the CO2 credit price at their geolocation and divided by the $EAAS token price.

## Define User Tiers and Tasks:
- CAS, ADV, and PRO users are able to do 30 questions for ESG and Carbon categories
- The DePIN hardware is only accessible to PRO users in order to measure monthly Kwatt use. 
- CAS users have a monthly referral limit of 5 people. 
- ADV users have a monthly referral limit of 25 people. 
- PRO users have a monthly referral limit of up to 100 people. 
- Behavioral tasks are available to all tiers. 


## 	Assign CO2 Scoring Values:
<!--
Assign CO2 scoring values to each action category based on user tiers:

| category    | CAS            | ADV                | PRO                |
|-------------|----------------|--------------------|--------------------|
| ESG         | 5 KG           | 10 KG              | 10 KG              |
| Carbon      | 7 KG           | 14 KG              | 14 KG              |
| DePIN       | 0              | 0                  | 10 KG per 100 Kwat|
| Behavioral  | 7 KG           | 14 KG              | 14 KG              |
| CC          | 5 KG           | 5 KG + 5% of refs  | 5 KG + 5% of refs  |

-->
eaas.global assigns scores in each categories based on level of importance, sustainability and user Tier. Higher-Tier users receives more scores due to the accuracy and reliability of the information eaas.global acquires. 

*eaas.global has the right to modify scores in its own discreation*



## Total CO2 Credits Earned by User i** 

*T𝒊=𝑬𝒊∗𝑬𝑺𝑮𝒊+𝑪𝒊 ∗𝑪𝑨𝑹𝑩𝑶𝑵𝒊+(𝟏𝟎∗𝑫𝑬𝑷𝑰𝑵𝒊)/(𝟏𝟎𝟎 𝒌𝑾𝑨𝑻)+𝑩𝒊 ∗𝑩𝑬𝑯𝑨𝑽𝑰𝑶𝑹𝑨𝑳𝒊+𝑪𝑪𝒊∗𝑪𝑴𝑪𝒊*


**Where:**
- Ti​: Total CO2 credits earned by user i
- Ei​,Ci​,Di​,Bi​,CCi​: CO2 scoring values for ESG, Carbon, DePIN, Behavioral, and CC categories, respectively in KG of CO2 credit.
- ESGi​,Carboni​,DePINi​,Behaviorali​,CMCi​: Number of actions completed by user i in each category
---

**Reward in $EAAS Tokens for User i:**

<img src="/src/headers/algorithm_math.jpg" width="300">

**Where:**
- Ri: Reward in $EAAS tokens for user i
- CO2_credit_price(GEO): Price of CO2 credit at the user's geolocation (per ton)
- $EAAS_token_price: Price of $EAAS token in the market


## To sum up... 

By offering rewards to users who engage in ESG activities, reduce carbon emissions, and build communities, we foster a sustainable and conscientious culture among our user base. ⁤ The algorithm we use for reward distribution encourages user participation and helps our company to achieve its goals of community involvement and environmental sustainability. 

By continuously modifying and evaluating the algorithm, we want to boost user engagement, encourage good behavioral changes, and significantly impact the shift to a more sustainable and environmentally friendly future. 

Our referral program, which offers rewards for successful referrals, aims to foster a green and forward-thinking community and contribute significantly to the platform.