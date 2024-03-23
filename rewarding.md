---
icon: credit-card
label: Rewarding
order: 1700
---

# Reward Allocation Algorithm

Through the use of rewarding mechanism, users at different levels (CAS, ADV, and PRO) are motivated to take part in various activities inside the application. Our goal is promoting environmental sustainability and community participation. Rewards are allocated to user as $DEPIN tokens based on CO2 credit price and users's TIER and geolocation after 45/30/7 days of use. Activities include answering carbon-related and ESG questions, using the DePIN device (available only to Pro users), completing behavioural challenges, and recommending the app to others to create community. 

## Algorithms 

We use a methodical process to reward each user's based on their actions within the app. The algorithm's high-level summary is as follows:
- we Identify and define the activities that users can take to get rewards. These include but not limited to learing and completing ESG related information and tasks, Carbon, using DePIN hardware(PRO users), behavioral actions, and referrals. 
- we assign amount of CO2 credit to each action based on its importance or contribution to our company's goals. These values are predefined and configurable based on importance, user base, and objectives 
- we then calculate total CO2 credit collected by each user 
- we then allocate Rewards in $DEPIN token to each user based on location and users total CO2 credits collected

## Define User Tiers and Tasks:
- CAS, ADV, and PRO users are able to do 20 ESG questions every month and 10 quizzes pertaining to carbon.
- The DePIN hardware is only accessible to PRO users in order to measure monthly Kwatt use. 
- Up to five people can be referred by CAS users each month. 
- ADV users have a monthly referral limit of 25 people. 
- Each month, PRO users can recommend up to 100 people. 
- Behavioral tasks are available to all tiers. 

## 	Assign CO2 Scoring Values:

Assign CO2 scoring values to each action category based on user tiers:

| category    | CAS            | ADV                | PRO                |
|-------------|----------------|--------------------|--------------------|
| ESG         | 5 KG           | 10 KG              | 10 KG              |
| Carbon      | 7 KG           | 14 KG              | 14 KG              |
| DePIN       | 0              | 0                  | 10 KG per 100 Kwat|
| Behavioral  | 7 KG           | 14 KG              | 14 KG              |
| CC          | 5 KG           | 5 KG + 5% of refs  | 5 KG + 5% of refs  |

*EAAS.GLOBAL has the right to modify scores in its own discreation*



## Total CO2 Credits Earned by User i** 

*T𝒊=𝑬𝒊∗𝑬𝑺𝑮𝒊+𝑪𝒊 ∗𝑪𝑨𝑹𝑩𝑶𝑵𝒊+(𝟏𝟎∗𝑫𝑬𝑷𝑰𝑵𝒊)/(𝟏𝟎𝟎 𝒌𝑾𝑨𝑻)+𝑩𝒊 ∗𝑩𝑬𝑯𝑨𝑽𝑰𝑶𝑹𝑨𝑳𝒊+𝑪𝑪𝒊∗𝑪𝑴𝑪𝒊*


**Where:**
- Ti​: Total CO2 credits earned by user i
- Ei​,Ci​,Di​,Bi​,CCi​: CO2 scoring values for ESG, Carbon, DePIN, Behavioral, and CC categories, respectively in KG of CO2 credit.
- ESGi​,Carboni​,DePINi​,Behaviorali​,CMCi​: Number of actions completed by user i in each category
---

**Reward in $DEPIN Tokens for User i:**

<img src="/src/headers/algorithm_math.jpg" width="300">

**Where:**
- Ri: Reward in $DEPIN tokens for user i
- CO2_credit_price(GEO): Price of CO2 credit at the user's geolocation (per ton)
- $DEPIN_token_price: Price of $DEPIN token in Blockchain


## To sum up... 

By offering rewards to users who engage in ESG activities, reduce carbon emissions, and build communities, we foster a sustainable and conscientious culture among our user base. ⁤ The algorithm we use for reward distribution encourages user participation and helps our company to achieve its goals of community involvement and environmental sustainability. 

By continuously modifying and evaluating the algorithm, we want to boost user engagement, encourage good behavioral changes, and significantly impact the shift to a more sustainable and environmentally friendly future. 

Our referral program, which offers rewards for successful referrals, aims to foster a green and forward-thinking community and contribute significantly to the platform.



 