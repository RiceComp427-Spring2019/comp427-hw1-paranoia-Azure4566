# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Martin Zhang

_Student NetID_: xz45

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: {TSA}
- Assumptions:
  - The checkpoints are the only normal points of entry to the protected zone
- Assets:
  - The passengers travelling to and from the airport. This is the most important asset and the first thing that need to be protected.
  - The crew of the aircrafts, and the ground support staff.
  - The aircrafts. This includes aircrafts arriving and departing the airport, as well as planes parked in the hangars of the airfield. Aircrafts are expensive investments for the airlines, and are the most important pieces of equipments for the operation of the companies.
  - The infrastructure, like terminal building, tower, ATC radar, taxiways and runways. These are important for the normal operation of the airport.
  - The merchandise in the building and their assets, for example duty free shops or resturants.
- Threats:
  - Armed hijackers. This is a type of attack that have happened plenty of times in the past and caused a lot of casualties. The attackers might be one terriorist or a group, or sometimes some suicidal individual or even discontent an alirline employee. They maybe armed with firearms, bombs or knifes, even everyday sharpenals like a screw driver or a pair of scissors.
  - Bomb attacks. This is a type that attack that aims to destroy aircrafts or the infrastructure and hurt people, with an explosive device. The device might be concealed in luggages or carried by attackers, and it might be milltary spec or home-made, even improvised with seemingly harmless materials on board pass the checkpoint. The bomb might be timed, remote controlled or manually triggered by a sucidal attacker.
  - Arson or poisonous substance attack in terminal/cabin.
  - Robbery/theft of the stores and/or pax in the terminal.
  - Mischevous interference to the operation of the airport by pax.
- Countermeasures:
  - Through check of the luggage and belonging of each and every pax and crew members. Any weapon, volitile or hazardous chemicals, and materials that might be used to make an explosive device should not be allowed past the checkpoints. Lighters and devices that might be used to start a fire also should not be allowed. Devices that might be used to influence the normal operation of the airpoet such as high power laser pointers, emp devices should also be forbidden.
  - Cross checking of the identification and tickets of the passengers, making sure that no one will be able to get in with a valid ticket.
  - Armed guards to protect against bruteforce attacks.
  - Emergency plans to evacuate pax and staff in case of alarm for bomb or other attacks.

## Problem 2
- Scenario: {Grading}
- Assumptions:
  - No unauthorized external aid/ cooperation is allowed for this homework.
- Assets:
  - The fairness of grading among all students. Works with same level of correctness should receive similar grades.
  - The academic integrity requirements for the homework need to be enforced, that is any work that involved unauthorized aid need to be identified.
- Threats:
  - Students might be referencing publicly avaliable solutions to problems. For a coding assignment this might be code on a github public repo, and for normal assignments it might be solutions from a solution manual etc. 
  - Students might be collaborating without permission.
  - Some students might be plagiarizing the work of others without the other party knowing.
- Countermeasures:
  - Cross check the works of all student submissions, and for problems whose anwsers should not be definite, focus on similar works and closely review to determine if any collaboration or plagiarism is involved.
  - Check creative works again solution avaliable in the public domain. If the idea and implementation are both too similar to the published solution, then unallowed reference might be involved.

## Problem 3
- Scenario: In app purchase system for a mobile game
- Assumptions:
  - the game will be published on google play store and apple app store, and payment will be processed through the two store systems
- Assets:
  - The respective share of income for each and every in game purcahse. This is the important source for income of the game, for server upkeep and game updates and maintainence.
  - The in game environment balance. The microtransaction purcahses if gone wrong can destroy the balance of game.
  - The user experience, they should receive the coorect thing they paid for.
  - The payment information and records of the users. 
- Threats:
  - Credit card fraud. This is the most common threat to game developers, some user will use fraud credit card info to make purchase, and once the original owner makes a chargeback, the income is lost while the in game item is already given out.
  - Stolen apple/google account balance. Purcahses made with balance in a stolen google/apple account will be charged back and is another potential lost of income.
  - Hacking of the game server to gain paid items. Hacker might be aiming to crack the database system and edit paid items into user accounts.
  - Man in the middle attack to trick the server that payment has been received.
  - Breakthrough of transaction log to get user info for other frauds.
- Countermeasures:
  - Frequent backup of user data in database, so a rollback to a recent backup will always be avaliable in case of a large crack.
  - Detailed encrypted transcation log with multifactor authentication for access, so items can be recalled if a chargeback happens from credit company or google/apple. Encryption and multifactor authentication will help prevent information leaks.
  - Financial level communition encryption for all communications to prevent MITM attacks, and do multiple checks before transaction is confirmed

