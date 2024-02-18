# Lloyds Product Research
## Life Insurance
https://www.lloydsbank.com/life-insurance.html
- Lloyds bank offers life insurance, life insurance premiums are determined by how health, age, sex, etc. 
- As we have access to peoples spending habits we can see how healthy they are acting based on the businesses they interact with. 
- We could then recommend these people life insurance.
##### Process
- Break down businesses by whether they make an individual a more or less appealing insurance candidate
- Give each of these businesses an interaction score either positive or negative
- Tally up each score for each business
- The users that are in the top nth percentile should be offered a no trouble quote
##### Notes
- Could extend to different forms of insurance, maybe a link between certain spending habits and better drivers

## Current Accounts
https://www.lloydsbank.com/current-accounts.html
### Classic
##### Account Offer
- Offers 15% on selected retailers
##### Process
- Create a count for users interacting with businesses
- When businesses are added to this list, the top nth percentile users should be made aware
### Club Lloyds
##### Account Offer
- £3 monthly fee, waived if spends over £2000
- Yearly Benefits Include:
	- 12 Months of Disney+
	- 6 x cinema tickets at ODEON or Vue cinemas
	- An annual Coffee Club and Gourmet Society membership
	- An annual magazine subscription
##### Process
- Build user profile focusing on total spending, spending on cinemas, café spending, and dining out
- If users routinely spend over £2000 then show the benefits users could get for free
- If could save money on any of the other services, calculate this out for users and show them
##### Notes
- The other accounts silver and platinum cover insurance, which isn't covered in this assignment

## Borrowing and Mortgages
##### Notes
- Preference towards ignoring this as it's too complicated and highly regulated

## Savings Accounts
https://www.lloydsbank.com/savings.html
### Club Lloyds Advantage Saver or ISA Saver
##### Account Offer
- 4% if you withdraw from the account 3 or less times
- 1.3% if you withdraw from the account sooner than that
##### Process
- Organize lloyds accounts by how active they are
- Advertise this service to the top nth percentile
### Clubs Lloyds Monthly Saver or Monthly Saver
##### Account Offer
- +5% for a year where you can save up to £250 a month
- The money can be withdrawn at any point, interest is paid out at the end of 12 month period
##### Process
- Organize lloyds accounts by how active they are
- Advertise this service to the top nth percentile
### Child Saver and Smart Start
##### Account Offer
- Gives a user with a child a savings account for the child that accrues interest
- At a set birthday, the account turns into an adult account and the child gains access
##### Process
- Identify users with kids based on spending history
- Then advertise these products to these consumers
### Investment / Share Dealing ISA
##### Account Offer
- Invest up to 20k per year with no capital gains tax
- The first just selects High, Medium, Low risk
- The second allows users to buy shares
##### Process
- Find users who are "good" with money
- The focus should be on identifying "money nerds"
##### Notes
- This will be harder to figure out than others

# Constructing Recommendation Engine
## Clustering Categories
##### Insurance:
- Healthy, Average Health, Unhealthy
##### Current Accounts
- Favourite businesses (Business deals)
- High business spenders (Classic)
- Cinema goer (Club lloyds)
- coffee drinker (Club lloyds)
- dining out eater (Club lloyds)
##### Savings Accounts
- Inactive user index, those with minimal tx's (Club Lloyds Advantage Saver or ISA Saver)
- Frugal spender user index, those with minimal spending (Clubs Lloyds Monthly Saver or Monthly Saver)
- Users likely to have kids index, those who spend in places and at times parents spend (Child Saver and Smart Start)
- Smart money users, leave this till last it will be the most vague (Investment / Share Dealing ISA)












