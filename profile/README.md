# Legacy Fantasy Football

Deployed : https://legacyfantasyfootball.vercel.app/

## Origin Story

12 years ago my friends and I began playing Fantasy Football. Within the first season, it completley took over our lives. We live, breathe and talk football. 
Throughout the years, many memorable things have happened. 

The term most commonly known as a "sleeper" was coined a "foster" in my league, due to the emmergence of Arian Foster in 2010. My brother, won 3 championships in the first six years of our league. One member won on autodraft and with Mark Sanchez at the quarterback position! One member talked all summer about "the superstar he was going to draft in the first round" and then drafted David Montgomery his rookie year. I drafted and kept Josh Gordon, over and over and over again, no matter how many times he let me down. 

There are endless stories from the 12 years of my league, and I know every Fantasy League that exists has their own similiar but also hilariously unique stories. 

### The Problem

I have always felt like the modern systems that we play Fantasy in, ESPN, Yahoo, CBS are missing the user experience of fantasy. As Jeff Schaffer says, Fantasy Football is about the quest for individual acheivement and all that goes into it. The endless up and downs, feelings of hope and despair, the friendly banter that sometimes goes too far, and the relationships with players and with league. But our modern systems don't track these stories, and offer very little in memory. They care about the current NFL stats. And every year, Owner's hard sweat and tears from the past year are deleted and removed from the narrative.  

>Fantasy football is actually an amazing American pastime, because it takes the ultimate team sport, NFL and football, and turns it into the quest for individual achievement. - Jeff Schaffer

### The Solution

I set out to create an application that helps Fantasy Football Leagues retell the narrative of the league. I wanted users to have info and stats from their league at the end of their fingertips. I wanted to broaden the fight for individual achievement from one mere year, to a everlasting quest to be crowned the best in your league. The legacy points system that I created allows fantasy football leagues to be looked at over the longhaul.  Fantasy Football is not going away, and it is time to start thinking of leagues as long term battles for glory rather than an annual rise and fall. 

## User Story

- Users can create a league in LFF, by importing their ESPN Fantasy Football League Id, and Authorization cookies (Espn_s2, and SWID)
- League members can search for a league once it is created in LFF. 
- Users can see a chart displaying the ammount of wins each owner has over the course of the league. 
- Users can see a chart displaying the ammount of points each owner has over the course of the league. 
- Users can see a sortable table that displays the trophy room. Which shows how many playoffs,finals appearences, and championships owners have. 
- Users can see a table that shows each year's standings and records. 

Now these stats are nice, and help paint the league picture. But what was really needed was a finitive way to rank leagues owners. 

- Users can see the Legacy Ranking board, which shows the legacy points each owner has. 

## Technology Used

- Python
- Django
- React 
- HTML 
- CSS 
- Bootstrap

## ERD

<img width="890" alt="Screen Shot 2022-08-01 at 6 53 07 PM" src="https://user-images.githubusercontent.com/75767764/182258823-5b1fcf1a-c4c1-44c1-8b65-80645ab66805.png">

## IceBox 
- NFL player Legacy Rankings based on players league success, including real time stats but also fantasy stats (Championships, 40+ fantasy point games etc)
- Gamify Fantasy Football: 
  - Real Time Updating of Fantasy Legacy Points
  - League Rivalries; at the beginning of the season each member picks a rival. If you beat your rival you get X ammount of legacy points, but if you lose you lose X points. If your rival marks you as their rival, the rivalry becomes a SUPER RIVAlRY leading to more points, 
  - In App currency earned by real time fantasy results, which can be used to purchase in app cusomisation, including: 
      -Player background images. 
      -creative popups you can purchase that you can purchase to appear on other user's screens when they log in. 
      -even player jerseys etc. 
      
- Adding more stats to the Legacy Points Ranking algorithm. 
- League custom Fantasy Legacy Points weights. Allow leagues to decide what stats are most important to them for the legacy ranking. 
- More interactive graphs. 
- Draft Stories
- Waiver Stats

