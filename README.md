# C# Battleship App - Duc Nguyen

Git Repository:
https://github.com/GauCenaDX/CSharp_Battleship_App

## Description:

A two-player console game that has its roots in the game Battleship from Mattel. There will be a 25-spot grid (A1 - E5). Each Player will place five pegs on the board to represent their five ships. Players will then take turns firing on their opponent's ships. The first person to sink all five ships wins.

## Other details:

- Each ship takes up one spot on the grid
- Two players will share the same console
- No completing the round after 5 sunk ships
- Show the visual of the grid with hits and misses
- Don't allow a player to shoot the same spot twice

## Grid Display

```
   A1 A2 A3 A4 A5
   B1 B2 B3 B4  X
   C1 C2 C3 C4 C5
    O  O D3 D4 D5
    X E2  X E4 E5
```

- \<Letter\>\<Number\>  =  empty spot
- X  =  Hit
- O  =  Miss

## New Grid Display

```
      1  2  3  4  5
   A  -  X  -  -  -
   B  -  O  -  -  -
   C  -  -  -  -  X
   D  -  -  O  O  -
   E  -  -  -  -  -
```

- \-  =  empty spot
- X  = Hit
- O  = Miss
