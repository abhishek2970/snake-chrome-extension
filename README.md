# snake-chrome-extension

Very basic chrome extension that let's you play snake with arrow keys (up, down, left, right) in a popup activated by clicking the extension icon.

Highscore gets saved in chrome.storage.sync, which means it's stored in the cloud (maintained between different chrome instances logged into same google account).

Game is reset by closing and reopening the popup and no pause function is implemented (yet).

Written with Pure JavaScript, CSS and HTML snake Game loop:

check for collisions (wall, food, snake itself)
if collision with wall - end game
if collision with food - add new node, spawn new food
if collision with itself - end game
advance snake (delete last node, add new)
check if end of game (spawned enough food to end the game)

# Photo

<img width="652" alt="Screenshot 2022-06-26 at 3 34 21 PM" src="https://user-images.githubusercontent.com/107938450/175809176-26175411-afd0-496c-b635-805e91128dad.png">

<img width="549" alt="Screenshot 2022-06-26 at 3 36 03 PM" src="https://user-images.githubusercontent.com/107938450/175809254-8ca874a8-901a-4a6d-8e90-9065fc8ae41f.png">
