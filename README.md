# Interesting Adventure Game
This is an adventure game I made using Unreal Engine 4. You can see an overview of this game below. I design different types of enemies and set my unique UI. Enjoy the game!

**Overview**
<img width="865" alt="image" src="https://user-images.githubusercontent.com/55035176/164108433-9a391374-6f77-438b-9131-f7d4315914bf.png">
<img width="815" alt="image" src="https://user-images.githubusercontent.com/55035176/164108497-9c8f9ba8-a314-4958-9978-37f31145dc38.png">
<img width="780" alt="image" src="https://user-images.githubusercontent.com/55035176/164108521-6fd1116e-f95d-41da-b722-468302a0c055.png">
<img width="856" alt="image" src="https://user-images.githubusercontent.com/55035176/164108555-7cd62e89-7c74-4de5-b877-d5e356c0cf76.png">


**Level Layout**
<img width="889" alt="image" src="https://user-images.githubusercontent.com/55035176/164107751-45a42a77-033e-47a9-a73e-6f9f213f359c.png">

**skeleton warrior**
<img width="797" alt="image" src="https://user-images.githubusercontent.com/55035176/164107966-29aabece-d08e-46ab-8be2-1aaf83d82c5d.png">
<img width="792" alt="image" src="https://user-images.githubusercontent.com/55035176/164108028-9ccee021-5915-4bd3-a9ac-172e6e8e2968.png">

**skeleton bomb-man**
<img width="798" alt="image" src="https://user-images.githubusercontent.com/55035176/164108108-92163052-ac03-4f70-801a-bea3f7fb66b7.png">
<img width="804" alt="image" src="https://user-images.githubusercontent.com/55035176/164108182-059d7b02-868e-4500-926e-b70d6009d0b9.png">

**dragon**
<img width="771" alt="image" src="https://user-images.githubusercontent.com/55035176/164108267-d21ee4a1-1453-4427-83c0-593bff23a049.png">

**trap witch**
<img width="848" alt="image" src="https://user-images.githubusercontent.com/55035176/164108374-000962ad-3680-4f10-8136-e998729289f5.png">
<img width="792" alt="image" src="https://user-images.githubusercontent.com/55035176/164108397-df041ff7-9062-4adb-a047-b1e8d5c3af3f.png">

**end room**
<img width="814" alt="image" src="https://user-images.githubusercontent.com/55035176/164108599-a5d13c86-7d5c-41f7-bc34-537ac3ff04e3.png">

**death UI**
<img width="866" alt="image" src="https://user-images.githubusercontent.com/55035176/164108646-0a126502-5651-4b15-a2fa-9ac68ba027b4.png">

## Game Design Process

For this level design game, I want to create a game more like an adventure. 

To better design my game, I first think about how the user interacts with the game. I decided to make my game setting be the sky island. The player could jump between different islands in the sky, and they should avoid falling off the island. In that case, if a player jumps off the island accidently, they will die and need to restart the game. I use some small island or stairs as the connection between the big island. The player needs to be careful when they jump between each element.

Next, I think about the enemy design. The three types of enemies have the requirement. I choose the pursuer to be a skeleton warrior. The skeleton warrior has 120 degrees of eyesight. If the skeleton sees the player, it will chase the player. Otherwise, it will walk randomly in a designed area. If the player is chased by a pursuer, the HP will decrease by 20. (100 total) You can see a group of skeleton warriors at the start of the game.

My Mortar is a skeleton mage. It will shoot bombs randomly. The bomb will delay 4 seconds and then explode. If the player is in the range of explosion, the HP will decrease by 50. The Mortar is an unmoving enemy, so I put it in front of the door. In that case, it is harder for the player to avoid the attack. The bomb is in an arc as the requirement.

My flyer is a bomb dragon. It will also shoot bomb as the player’s running direction. In that case, it is necessary to change direction to avoid the bomb. I put the dragon in my battlefield, and it is one of the harder enemies in my game. To win the game, the player needs to shoot many star balls. (player attack method explained below)

My own enemy is a trap witch. It will throw traps in different directions at a very fast speed. Some traps will block players' normal routine. In this case, player needs to find a nice path to avoid the trap. In some cases, players could go directly to the trap if they have enough HP. Trap will decrease 20 HP for players.

Since my game is already hard for jumping around the map. I decided to give some measures for players to fight with the enemy. The player could use the magic to shoot the star ball. If the star ball hits the enemy successfully, the enemy will be eliminated. (except dragon)

Finally, I set the crystal to guide the player, the player could also increase the score when they collect the crystal. If the player goes into that room, he will see the message “You Win!”, and another NPC will celebrate with the player. He can also stand on the Restart button to restart the game. Overall, It is a good adventure to play.
