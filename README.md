# Bash

## Objective
Create a bash script that creates a game that is playable by user. At first I wanted there to be a user vs two bosses with a random number generated that the user has to try and guess, and if they do, that boss is defeated. After making it, I wanted to make it more advanced with starting characters to chose with unique stats each that will effect the game directly. For this more advanced part I utilized AI to try add more to my already working script to include stats like health and attack power.

## Skills Learned
- Ability to create bash scripts
- Knowledge in executing scripts and changing their permissions
- Understanding on how to use AI with coding

## Tools Used
- Kali Linux machine
- VirtualBox
- Copilot

## Steps
1. First, was creating the base of my game with two beasts to fight and a number input for the user to do each fight. I made the first boss pick between 0 or 1 and if the user guesses correct, they move on the next boss which is a number between 0-9. I also added a cheat for the second fight since it is more difficult, by making an or statement where it defeats the boss if I put the secret word, donut.
 _See screenshot below (click to enlarge)._
![Screenshot 2025-05-09 151545](https://github.com/user-attachments/assets/f757a964-af20-474d-8007-154994559b48)

3. Second, I wanted another user to play and make it so they automatically win if they can make it to the second fight regardless of their number guess. Made an elif statement where the user bob defeats the boss, no matter if they chose the right number or secret cheat. See screenshot below (click to enlarge).
![Screenshot 2025-05-09 151738](https://github.com/user-attachments/assets/168427c6-4018-491f-9029-e097ccba8ddc)

4. Third, I added three different characters for the user to select from before the game begins. I gave each charcter and boss a name, health amount, and attack power. I was having trouble implementing the attack and health into the game and asked copilot for any suggestions. See screenshot below (click to enlarge).
![Screenshot 2025-05-09 153725](https://github.com/user-attachments/assets/c1e431b5-139f-461e-bd33-cad092c00332)

5. Lastly, I used some feedback Copilot AI gave with specific intructions to still implement the random number selection, but this time how much attack is based off the attack stat of that charcter and how close the user's number was to the randomly generated number. For example, if I guess the random number exactly, it will do the attack stat # + 5 damage to the bosses health, and if I am more than 5 away on my guess it will do attack stat #/4 damage to the bosses health. Also asked for the boss to attack the user after the user goes, here it suggested a defense stat to all characters which will be subtracted from the attack power from the boss. Below is the final script with two test runs on different characters. See screenshots below (click to enlarge).

![Screenshot 2025-05-09 161503](https://github.com/user-attachments/assets/9f6e6813-81de-4246-99f5-2deafa9492ad)
![Screenshot 2025-05-09 161528](https://github.com/user-attachments/assets/3cac844d-111e-4ee4-a488-3c27c83da7c3)
![Screenshot 2025-05-09 161852](https://github.com/user-attachments/assets/ad9f3822-4596-49fe-873d-63eddb8f1a2d)
![Screenshot 2025-05-09 162248](https://github.com/user-attachments/assets/574cb309-3f0c-4498-b27a-af41de7218cd)
