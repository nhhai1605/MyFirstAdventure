# My First Adventure - 2D Platformer - UE5
This is my first UE project and my first interaction with event graphs. I chose Maplestory becauses it has always been one of my favourite games since i was a child. Maplestory looks simple but so complicated, specially with animations and combos. So i tried to replica it within a week with no UE knowledge. I hope this can showcase some of my researching, self-learning and adaptablility skills. Thank you.
![image](https://github.com/user-attachments/assets/208fbb1a-ad46-45d5-b636-259fa5a315db)

## 1. Movements and Actions:
- Move around with A and D key, Shift to sprint, Space to jump (can double jump), have jump buffering and coyote. A to attack.
- Have stamina and will drain if jump, attack or sprint. If stamina reach 0, will go to coolldown and cannot use any stamina for some duration.
- Animations and sound effects.
https://github.com/user-attachments/assets/62240805-8341-4d8a-b80b-0cef90a70398

## 2. Objects
- Have solid ledges, acts like a wall.
- Two way ledge which you can jump on and drop down from (similar to the one in Maplestory).
-  Have portal to another portal and portal to next level.
-  Can interact with items like spring and drops (will pick up to inventory when step on it).
https://github.com/user-attachments/assets/0f6cf109-7f81-4834-a652-a707e731c705

## 3. Other pawns
- Have some types of enemies that use AI Controller with Behavior Tree.
- AIs can patrol from left to right (have wall and ledge detector) and when see the player within some range, will aggro the player. AIs can stop aggro player if player go to far.
- When aggro the player, these mobs will chase the player and when near enough, attack the player (AIs cannot jump and will stop at ledge or wall).
https://github.com/user-attachments/assets/089f3cb1-90ce-40dc-b647-6dd26903cd2f

##. 4. Simple UIs 
- Some simple UIs like enemy health text, player HP and SP, main menu and inventory (stil working on it and need improvement here :V)
https://github.com/user-attachments/assets/26dee2d3-1975-490a-b6c0-08b5b9698a0d



