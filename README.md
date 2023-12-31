# Truth Or Dare 2 (TOD 2)

## Introduction

**Truth Or Dare 2 (TOD 2)** is the exciting sequel to the original Truth Or Dare game that was initially created as a fun project to play privately with friends. Unlike the first version, TOD 2 takes the game to the next level, introducing a new gaming experience using JavaScript and the powerful Socket.IO library. This enhancement allows all players to interact with their screens simultaneously, making it even more enjoyable and engaging.

![Animation](https://github.com/IbrahimEllahi/TOD-2-Online-Game/assets/85767913/d1edfc24-ffaf-49c6-8d32-bc0502a1960e)

## Game Concept

TOD 2 is a turn-based game with multiple modes, turn cycles, and round options, designed to provide hours of entertainment. The fundamental concept of the game is straightforward: players take turns choosing between "truth" or "dare." After making their selection, they receive a corresponding challenge or question that they must complete or answer. The catch is that while one player is in the hot seat, all other players get to rate their performance on a scale of 0 to 4 points.

![Animation2](https://github.com/IbrahimEllahi/TOD-2-Online-Game/assets/85767913/afbae08f-eeb2-4400-ad01-6e09caf84de7)

## Gameplay

The game continues with the cycle of turns, and it's a race to accumulate the most points. The player with the highest score at the end of the final round emerges as the ultimate winner.

## Features

**TOD 2** offers several exciting features:

- **Multiplayer Interaction:** Unlike the original version, TOD 2 allows all players to interact with the game simultaneously. This feature makes it perfect for virtual hangouts with friends and family.

- **Diverse Game Modes:** The game offers multiple modes and round options, ensuring variety and adaptability to different preferences and group sizes.

- **In-Built Chat:** TOD 2 includes an in-built chat, making it convenient for players to communicate within the game. However, it is highly recommended to use third-party chat software like Discord for voice chats or facecams to enhance the gaming experience.

- **Customizable Truths and Dares:** Create your own truths and dares to make the game even more unique and tailored to your group's personality.

- **Redos:** In case a dare is too hard or a truth is too challenging, TOD 2 provides a "Redo" option. This allows players to have another attempt at completing the task without penalties, adding an extra layer of fun and excitement to the game.

- **Fair Voting:** TOD 2 ensures fair play by not allowing players to vote for themselves. This ensures unbiased rating of the performances, making the game even more competitive and enjoyable. Voting buttons are greyed out for the player performing the dare or answering a truth (shown in the below gif).

![Animation3](https://github.com/IbrahimEllahi/TOD-2-Online-Game/assets/85767913/74aca59c-2440-4718-a404-a7e2d7f18477)
(_Gif may contain glitched particle graphics, due to recording issues_)

## Recommendations

**TOD 2** is all about fun and camaraderie, so it is best suited for friend groups looking to have a great time and take on challenging dares and truths. For an optimal experience, it's highly recommended to use a third-party chat software like Discord, allowing players to connect through voice chat and even use webcams to add a face-to-face dimension to the game.

This game is not intended for public play with random individuals; instead, it thrives when shared among close-knit circles of friends seeking a memorable and entertaining time together.

**TOD 2** is your go-to choice for a virtual party game that's sure to spark laughter, surprises, and unforgettable moments.

![Animation4](https://github.com/IbrahimEllahi/TOD-2-Online-Game/assets/85767913/75e446f4-4972-4eeb-9a37-a7d2eb457a3d)


## Setup

To get started with **Truth Or Dare 2 (TOD 2)** and host your own game night with friends, follow these setup instructions:

### Prerequisites

1. **Node.js:** Make sure you have Node.js installed on your computer. You can download it from [Node.js](https://nodejs.org/).

2. **npm (Node Package Manager):** npm usually comes bundled with Node.js. You can check if it's installed by running `npm -v` in your command prompt or terminal.

3. **Socket.IO:** TOD 2 relies on Socket.IO for real-time communication between players. You can install it using npm:

   ```bash
   npm install socket.io
