# The Plan
This is the plan for my Intro to Code fantasy football app

## 1. Pitch

I'm building an app that tracks the performance of my fantasy football roster because I keep losing, I'm not sure where to make adjustments, and the ESPN app does not give me holistic data for my roster. 

## 2. Features

### Required Features

1.	Sign up and login. A new visitor can create their own account from inside your app, then log in and log out. Every account is a row in your users table. Each user sees only their own data.
	
2.	Data model. A users table plus at least 2 tables of your own, connected by a relationship (e.g., entries belong to categories).

3.	Create / read / update / delete.	Add an item, view the list, open one item's detail page, edit it, and delete it with an "are you sure?" confirmation.

4.	Validation.	Required fields can't be left blank. Show a friendly message if someone tries.

5.	Stars.	Users can star items and see a "starred" view. All stars live in one stars table (a junction table) where each row references a user and an item: "this user starred this item." One table for everyone, not one per user.

6.	Find things.	Search or filter, plus sort (e.g., newest first, highest rated).

7.	Dashboard.	At least one chart and 2–3 summary stats computed from your data (count, average, best month).
Real data: Your app must contain at least 5 real entries of your own data by the due date. No placeholder text.

### My Features

1. Highlight Underperforming Players. As a user, I want the app to highlight players that have underperformed **multiple weeks in a row (revisit the exact timeline)**, so that I can see if underperformance is a trend or an outlier.

2. Suggest Replacement Players. As a user, I want to be given options for replacements based on fantasy points trending upward, so that I can make adjustments to my roster. 

3. Track benched players on other teams. As a user, I want the app to tell me if a player has been sitting on an opponent's bench for multiple weeks in a row, so that I can request a trade.

| Planned Feature | Shipped / Changed / Cut | Status | Learning | What changed and why (one line) |
| --------------- | ----------------------- | ------ | -------- | ------------------------------- |
| Sign up, log in | 
