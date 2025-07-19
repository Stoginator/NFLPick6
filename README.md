# NFL Pick 6
Description: An automated system for all participants in an NFL Pick 6 league

## Current Process: 
An NFL Pick 6 league is a season-long competition. Each week of the National Football League (NFL) season, the operator chooses 6 games and emails participants. Participants predict the winner of each game. Their weekly wins and losses are reproduced on a leaderboard. The season-end leaders win the competition. Pick 6 leagues are run by an operator, who recruits participants and manages league operations. Participants pay a monetary due to join the league.

## Automated MVP Process: 
All participants will create an account. Participants may request the creation of a league. If admins grant the request, the requesting participant will become that league's operator. Operators will invite more participants using pre-written text or email messages and sending from their own account. Operators will upload their payment QR code for participants to send their dues. After dues are collected, operators will confirm when a participant is eligible for game selection.

An automated system will manage league operations: choosing 6 games each week, communicating them to all participants, handling team selections each week by each participant, sending communication reminders, calculating a leaderboard, and sending a weekly summary by email. This cycle will repeat every week of the 18-week NFL season.

At the end of the season, the final leaderboard will be saved. The operator is responsible for paying out awards.

Must be a mobile-first website! No one will use this on desktop.

## Current User Experience
### Operator
1. Manage league membership by adding or removing participants
2. Collect dues
3. Pay out awards
4. Select 6 games for each week
5. Manage win-loss record
6. Manage weekly picks from participants
7. Track weekly picks in Excel
8. Communicate to entire group 4x or more a week
   1. Games selected
   2. Send reminder 24 hours before earliest kickoff
   3. Predicted winners chosen by each participant
   4. Final win-loss record after week end

### Participant
1. **Pay to play**: Pay dues to the operator at the beginning of the season
2. Send each pick by game kickoff each week
3. Confirms picks recorded by operator
4. Confirms win-loss record at the end of each week

## Requirements
### System
1. Manage win-loss record
2. Obtains weekly picks from participants before game kickoff
3. Present weekly picks for all participants
4. Present win-loss record for all participants
5. Send 1 reminder to all participants 24 hours before the earliest kickoff
6. Select 6 games each week with the lowest over-under prediction
7. Present PayPal/Venmo/Zelle/Apple Pay QR code on the website
8. Share button to easily recruit participants (pre-written text or email message)
   1. Consider social media templates?
   2. Operator provides their own phone number / email capabilities
9. Allow  

### Operator
1. Collect dues by submitting QR code on the website
2. Pay out awards
3. Manages league membership by adding or removing participants

### Participant
1. **Pay to play**: Pay dues to the operator at the beginning of the season
2. Make picks by game kickoff
3. Confirm the picks are represented as chosen

### Out-of-Scope
1. System collecting Dues
2. System paying out awards

### League Settings
1. Allow participants to vote on the games selected each week.
2. Customize reminders to be sent X hours before each kickoff. 
3. If you miss a game, you are ineligble for season-end pay-outs.
4. Predict the score, as well as the winner of the game.
5. Awards section: see the coolest weeks you predicted
6. Save Weeks: save predictions and results from a week you really liked
7. Small weekly payouts for special cases:
   1. Perfect Six: you pick the winners for all six games in one week
   2. Consecutive Perfect Sixes: you pick the winners for all six games in back-to-back weeks

### Legal Issues
1. Not allowed to use NFL team names or team logos --> don't think non-monetization will fix this

### Change Management for Future
1. Collecting Dues and Award Payments
   1. Current state: Operator receives dues from all participants and pays out at the end of the season.
   2. Future state: System receives dues from all participants and then pays out at the end of the season. 
