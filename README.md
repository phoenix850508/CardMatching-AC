# CardMatching-AC

CardMatching-AC is a mini-game project that is testing player's memory on the relative position of paired number cards. Players are tested to memorize where
are the paired cards and by left clicking 2 cards. If 2 cards number are matched, it will remain face-up. However, if 2 cards are not matched in number, 
both cards will flip back to the default face-down position.

The game will be finished once all 52 cards have a matched pair, the number attemped will also be shown in the completed scene!

## Specs

### MVC design
The code is designed in the MVC pattern, and there are also objects like GAME-STATE, Symbol, and utilities that is used to support MVC pattern.

### State concept
From this mini-game project, the concept of `state` emerged, in total there are 5 different states that could possibly happen. All actions are performed
based on the `state` of game. So it is particularly important concept in this game.

### Animation
There are also a couple animation shown in the game when there are particular event triggered.

<img width="1506" alt="截圖 2022-12-27 下午2 10 56" src="https://user-images.githubusercontent.com/121414639/209619875-686a47d9-25e9-4cad-83a9-2882bfb7266c.png">
