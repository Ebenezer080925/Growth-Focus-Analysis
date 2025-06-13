# Growth-Focus-Analysis

![](https://github.com/Ebenezer080925/Growth-Focus-Analysis/blob/main/Growth%20focus%20heading.png)

## Introduction 

 This report presents a comprehensive analysis of user and transaction data to assess the
growth performance of the company. It focuses on five key areas: User Analysis, KYC Status,
Transaction Patterns, Retention Trends, and Funnel Stages. The goal is to identify bottlenecks in
user engagement, highlight revenue opportunities, and provide strategic recommendations for
sustainable growth.

### Dataset Description:

- Users Table: Contains information about users, including registration details, KYC status, deactivation
status, and occupation.
- Transactions Table: Contains transaction details, including amounts, currency corridors, and
transaction dates.

![](https://github.com/Ebenezer080925/Growth-Focus-Analysis/blob/main/Screenshot%202025-05-13%20093514.png)

 The dashboard above is showing a summary of the main dashboard show us
the total amount of user we are having which is about 21,000+,resulting to over a
total of 165k+ transaction generating a revenue of $60.49M.

   ## There are have five main dashboard which are

1. User Analysis
2. KYC Status
3. Transaction Analysis
4. Retention
5. Funnel Stages.

## OBJECTIVE OF THE DASHBOARD:

1. To give a breakdown of the Data which has been done above and the subdashboards
2. Key explanation of the rate of users not verified, why KYC status have not been
   passed, checking the transaction country and analyzing the cause of low retention.
3. To monitor the KYC status performance to know increase the rate of transaction
   in other currency not only in Canadian dollars and to increase the retention rate of
   the customers.



# USER ANALYSIS

![](https://github.com/Ebenezer080925/Growth-Focus-Analysis/blob/main/Screenshot%202025-05-19%20154220.png)

The USER ANALYSIS is a sub-dashboard drill down of the users, talking
about the Users, Volume of users, Verified and non-verified, Age Distribution,
Location and their profession.
 We have about 21,670 users where about 20% (4333) are verified and 80%
(17332) un-verified users. A significant portion of users remain unverified,
especially in countries like Nigeria and Australia. Most unverified users fall within
the age group of 19 – 24, with a high concentration of students and traders.
 So I was able to deduce that lack of chance might be the cause of there
unverification probabaly school stress as a student so they might not put there mind
in the verification and lack of time for those in the other profession expecially the
traders who hardly have time.

### Recommendation: 

- Implement targeted in-app nudges and outreach campaigns focused on
   students and traders, addressing barriers such as lack of time and awareness



# KYC STATUS 

The KYC stands for Know Your Customer status. The sub-dashboard below gives us
each details about the status of the KYC, The total number customers which was about
22k and then the people which have been verified and those that have not been
verified. We also have a break down for the KYC.
Not Started = 13543(61.75%), Pending = 2120(9.68%), passed = 4354(19.9%), In
Review = 68(0.3%), Failed = 1816(8.29%)

![](https://github.com/Ebenezer080925/Growth-Focus-Analysis/blob/main/Screenshot%202025-05-14%20171634.png)

From the chart we have a lot of people who have not started there KYC status verification process which
lead to low amount of customer who has been verified, and we also have to check onthose who failed the process to have more verified people.

### Recommendation:

- Prioritize clearing users in Pending, Review, and Failed stages through direct support.
- Launch a simplified KYC collection process (e.g., embedded forms, mobile-first
   design).
- Increase awareness via personalized notifications and educational content.


# TRANSACTION ANALYSIS

This sub-dashboard deal majorly with the transactions history and the corridors

![](https://github.com/Ebenezer080925/Growth-Focus-Analysis/blob/main/Screenshot%202025-05-14%20172203_1.png)

From the charts we have total number of transaction which is 165,000 which gives us a total revenue of $60M+. We also denote the top corridor to be CAD – NGN and CAD -USD and the inactive corridors are EUR and INR (0.0 record).
CAD(Canadian Dollar), NGN(Nigerian Naira), USD(United State Dollar), AUD(AustralianDollar), GHS(Ghanaian Cedi), KES(Kenyan shilling), EUR(Eurozone), INR(Indian Rupee).
I guess there is an error in the data the total amount send should be the same that is entering or they should have been a miscalculation, it should have been 32bn going out same coming in or 33bn.
![](https://github.com/Ebenezer080925/Growth-Focus-Analysis/blob/main/Screenshot%202025-05-19%20160358.png)
This chart is concern with the currency corridors. With the above we can see that a lot of money was send into the Dollars region where a lot was also exchange from between the CAD - CAD and the NGN – CAD while non from the EUR and INR. The place we are having 0.0 we might be having no customers in those region that’s why we are having low amount of money there. The reason why we might be having low currency rate in from other currency to Nigeria may be due to currency exchange rate. Which we will need to introduce a direct payment mode from different currencies.

### Recommendation:

- Introduce localized pricing and direct payment gateways for underserved
regions.
- Investigate and resolve possible data or integration issues causing currency
mismatch.

# RETENTION ANALYSIS

![](https://github.com/Ebenezer080925/Growth-Focus-Analysis/blob/main/Screenshot%202025-05-18%20232012.png)
The Retention analysis tracks users that patronize the store often which we have a total of 2million users Daily and 122million users monthly. We then break the users into user segmentation by transaction volume into categories base on total number of transaction they've done.

- 0–3 transactions: Very Poor = 6,140
- 3–5 transactions: Poor = 2,428
- 5–10 transactions: Good = 3,325
- 10–20 transactions: Very Good = 2,166
- 20 transactions: Excellent = 958
Majority of users are in the 0–3 transaction segment, indicating low engagement.

### Recommendation:
- Create loyalty tiers or incentives to encourage repeat usage.
- Focus on converting “Poor” users to “Good” users through retargeting
  campaigns.

# FUNNEL ANALYSIS

![](https://github.com/Ebenezer080925/Growth-Focus-Analysis/blob/main/Screenshot%202025-05-15%20151210_1.png)

The funnel stage analysis shows the drop of rate according to each stages of movement from the Acquisition --> Complete Profile --> KYC verified --> Transaction which dropped from 100% to 75.1%. We also had a large drop off amount form the early stages which is from the Acquisition to the profile completed stage which is about 9005 users which is about -44.36%. And we can check further from the KPI to see other drop off rate.
![](https://github.com/Ebenezer080925/Growth-Focus-Analysis/blob/main/Screenshot%202025-05-19%20162131.png)
I added this chart to show increase in the KYC verification will increase the rate of profile that are completed, ones the profile rate is increased the KYC will also increase which will cause high rate of increase in the transactions.

### Recommendation:
- Simplify the onboarding flow.
- Offer real-time assistance or FAQs during signup.
- Improve follow-ups for incomplete profiles via email/SMS.

  # Final Recommendations:

1. Boost KYC Completion: Focus on pending and failed cases first; automate
    follow-ups.
2. Expand Currency Access: Enable direct payments and pricing in local
  currencies.
3. Retain More Users: Incentivize returning users; use segmentation to target
   low-engagement users.
4. Fix Data Issues: Investigate mismatches in currency data and correct
   inconsistencies.
5. Polish User Experience: Redesign onboarding, use friendly UI/UX and
   real-time support.

## Conclusion :
This growth-focused analysis reveals key gaps in user verification, engagement, and currency support. By addressing these bottlenecks with targeted product and communication strategies, the company can significantly improve user retention and revenue generation.

 # You can drill down the dashboard with the Pbit file

## Socials
[linkedin (http://www.linkedin.com/in/ebenezer-d-18675027a)]

[Github (https://github.com/Ebenezer080925)]








