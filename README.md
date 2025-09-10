# Mesmorized-Card-Game
## Project Overview:
For this project, I designed and deployed a single-page application (SPA) developed using the Claude genAI tool.
#### Purpose:
To see the development differences between doing code myself and comparing it to the process of just utilizing a genAI tool to do the construction process for me, from start to finish.

## Description / Functionality
A simple application that allows the user to play a Memory Card Puzzle Game. A user will choose their difficulty and then start a game, where they will be selecting cards and trying to find matches in order to win!
- Users can choose between different difficulty levels: Easy (4x4 Card Layout), Medium (6x6 Card Layout), Hard (8x8 Card Layout), and EXTREME (12x12 Card Layout)
- After a successfully won game, a user will have the option to enter a 6-character name to add to a leaderboard for each specific game difficulty level

### How To Play (Detailed Instructions)
- A user will begin by selecting the difficulty level they want to play with.
- The user will then begin the game by clicking on the "Click to Begin" button
- Once a game is started, the user will have all the cards on display for about 3 to 5 seconds, so the user can try to quickly memorize the placement of the different icons.
- After the initial 3 to 5 seconds are up. All the cards will then flip over, hiding all the icons from the user.
- The user will then have the timer begin, and they can start to select two different cards to see if they can match cards together
- (if the cards match, they will be greyed out and highlighted)
- (if the cards do not match, then the cards will flip back over and allow the user to choose another set of cards)
- After a user has successfully matched all the cards with one another, they have WON the game!
- A pop-up will display the user's time they achieved and allow them to enter a 6-character name to add to the leaderboard tied to the specific game difficulty the user was playing on.
- After the pop-up is closed out, it will bring the user back to the main menu screen, where they can repeat the entire process again if they choose to.

## ACCESS to the Game Application
##### Github Repository:
-
##### Github IO:
-

## Known Issues:
- Users are able to switch the difficulty setting while playing a game, which will allow users to enter leaderboard scores for different difficulties, without truly playing the game at that specified difficulty, which they initially selected at the starting Main Menu screen.

## Future Enhancements/Adjustments:
- Make it so when cards are successfully matched/paired, instead of the cards flipping back over to their backend card face and becoming greyed out and highlighted. I would prefer to make the cards stay front-facing. So the icons will still display, while keeping the same features of greying out the cards and having them highlighted.
- Make the "Difficulty" button not visible/clickable once a game has been started.
- Add music in the background, and sound effects
- Create a settings menu to control audio levels, allow customization of the card icons, and be able to change the amount of time given to a user at the beginning of the game before all the cards get flipped over.
- Possibly allow for more GUI/Interface color scheme customization
