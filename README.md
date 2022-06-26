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


<img width="489" alt="Screenshot 2022-06-27 at 1 21 32 AM" src="https://user-images.githubusercontent.com/107938450/175831518-12db5101-d98c-4570-b946-a079dd98f996.png">
