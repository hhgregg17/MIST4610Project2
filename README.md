# MIST4610Project1

## Team Name: 
Correlated Subquery 

## Team Members:

1. Spencer Fox [@hhgregg17](https://www.github.com/hhgregg17)
2. Farzaan Hemani [@Frh53839](https://github.com/Frh53839)
3. Samuel Park [@samuelpark8713](https://github.com/samuelpark8713)
4. Eshaan Jain [@ej46122](https://github.com/ej46122)
5. Rhea Kakkad [@rhea415 ](https://github.com/rhea415) 

## Overview:

Below are 5 queries, 3 visualizations, and a data model covering the many aspects of the NBA. This includes but is not limited to Teams, Players, Statistics, and Transactions. This also includes other relevant infomation about teams and players such as injuries and awards.

## Data Model

Data model explination:

This data model is designed in a way to easily pull statistics from teams, players, and their respective games as well as keeping track of transactions.

The first two entities 'Player' and 'Team' have almost the same aspects. They both have many-to-many relationships to 'Game' via their respective weak entities 'TeamStats' and 'PlayerStats'. Both having two identitfying relationships. Both PlayerStats and TeamStats have many attributes looking into the statistics of singular players and team performance.

Player and Team also have another many-to-many relationship with 'Transactions' though, not identifying. There are two one-to-many relationships with team to keep track of the team the player transfers from and the team they transfer to. 

Player and Team ALSO has a direct one to many relationship. This is to list the players that have never been involved in a transaction.

Player has another two relationships with 'Injury' and 'Awards' (non-identifying) that are one to many. An award/injury can have one player but a player can have many different injuries/awards.

Game has a one-to-many relationship with 'Season' since a season can have many games but a specific game can only be involved with one season.

Lastly there is a many-to-many relationship between 'Coach' and 'Player' via weak entity 'CoachHistory'. A team can have many coaches in the past and a coach could have coached for many teams.

![image](https://github.com/user-attachments/assets/5fbbc790-2dfc-489e-94ae-d5eca6edc892)


## Data Dictionary:

![Screenshot 2024-10-04 135531](https://github.com/user-attachments/assets/dc18d126-08d0-4a3d-8f0c-502596c84b68)

![Screenshot 2024-10-04 135550](https://github.com/user-attachments/assets/57587976-4a84-4715-a228-f8838a289649)

![image](https://github.com/user-attachments/assets/881750a2-7427-4b4d-80ca-03ee63c1558e)

![Screenshot 2024-10-04 135624](https://github.com/user-attachments/assets/3b589769-26e1-46cf-bf54-eb759f81157c)

![Screenshot 2024-10-04 135656](https://github.com/user-attachments/assets/405a5cd1-385d-4cf5-91d4-768ba3d57463)

![image](https://github.com/user-attachments/assets/9a0a2d15-50f5-44c8-b8fa-7a6bf3cfacf7)

![Screenshot 2024-10-04 135724](https://github.com/user-attachments/assets/18385b42-f73d-4278-bf19-88183db5d559)

![Screenshot 2024-10-04 135740](https://github.com/user-attachments/assets/2eb3fc84-18bb-4154-a53e-1e6ed41c87ab)

![Screenshot 2024-10-04 135751](https://github.com/user-attachments/assets/dbe882b5-e87c-497f-a123-9e7c45347045)

![Screenshot 2024-10-04 135803](https://github.com/user-attachments/assets/d5a6aade-4e96-469a-a08d-7439a8bb0f12)

![Screenshot 2024-10-04 135819](https://github.com/user-attachments/assets/3b5d8265-f34b-410a-a78f-e9c97a5e8a80)

## Queries:



1. Query 1 placeholder.

![image](https://github.com/user-attachments/assets/df3ee306-d605-4d78-aea8-e7c02d3262b5)


![image](https://github.com/user-attachments/assets/b2f3d318-96dc-4be4-8632-ec360d1dda94)

Placeholder explanation

2. Query 2 Placeholder.

![image](https://github.com/user-attachments/assets/45207ccf-9980-4b86-aafc-4c0fb0136db3)

![image](https://github.com/user-attachments/assets/ac0c0ed9-2753-4d9a-8b4f-44183fa94a87)


Placeholder explanation

3. Query 3 Placeholder

![image](https://github.com/user-attachments/assets/b280ee80-3b62-4a82-bc86-5e7383b3b1a4)

![image](https://github.com/user-attachments/assets/06a3b400-2c75-418e-9d03-5c4755797705)


Placeholder explanation.

4. Query 4

![image](https://github.com/user-attachments/assets/e589ce43-9011-4542-964d-40180b6e7c54)

This query calculates the average points, rebounds, and assists per player for each team. It helps managers identify the top-performing teams based on player contributions.

5. Query 5 placeholder.

![image](https://github.com/user-attachments/assets/c63f0787-3e11-443b-9ae5-ee40f63bd09e)



Placeholder explanation.

## Views:

1.  Placeholder



Placeholder

2. Placeholder



Placeholder

3. Placeholder



Placeholder









