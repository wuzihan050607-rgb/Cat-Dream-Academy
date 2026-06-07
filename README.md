# Dream Pet Academy

**Dream Pet Academy** is a browser-based virtual pet and learning game. Players can adopt a cat, take care of it, complete study tasks, earn coins, buy decorations, dress up their pet, and join learning competitions.

The goal of the game is to make studying more fun by combining daily learning habits with pet care and customization.

## Features

### Account System

* Register a new account with a custom username.
* Log in with an existing username.
* Each account saves its own pet, coins, items, progress, and game data.

### Cat Adoption

* Choose a cat breed from the adoption screen.
* Name your cat and select its personality.
* The selected cat becomes your main pet.

### Dynamic Pet World

* The cat moves around in a small world scene.
* Scenes include:

  * Cat room
  * Grass field
* The game includes a time display.
* The world changes depending on time, such as day and night effects.

### Pet Care System

The pet has several status values:

* Hunger
* Happiness
* Energy
* Health
* Experience

Players can:

* Feed the cat
* Play with the cat
* Let the cat rest
* Take the cat to the doctor if needed

### Feeding System

Players can choose different foods:

* Cat food: costs 10 coins, increases hunger by 80
* Canned food: costs 5 coins, increases hunger by 50
* Water: costs 1 coin, increases hunger by 20

If the player does not have enough coins, a “Not enough coins” message appears on the current page or popup.

### Play System

Players can choose toys to interact with the cat:

* Cat teaser wand
* Tumbler toy
* Yarn ball

After choosing a toy, the player can drag it in the world to play with the cat. Playing with the cat increases happiness and creates heart effects.

### Wardrobe System

Players can buy and wear clothes, hats, and accessories.

Wardrobe features include:

* Clothes
* Hats
* Multiple accessories at the same time
* Dragging items to adjust their position
* Saving outfits
* Removing worn items by clicking “Wearing” again

### Shop System

The scene menu includes a shop where players can buy furniture and pet items.

Available shop items include:

* Normal cat bed: energy recovery +20, costs 20 coins
* Cloud cat bed: energy recovery +40, costs 30 coins
* Luxury cat bed: energy recovery +60 and happiness +10, costs 50 coins
* Normal cat tree: happiness +20, costs 20 coins
* Cloud cat tree: happiness +40, costs 30 coins
* Luxury cat tree: happiness +60, costs 50 coins

### Pet Shop

The scene menu also includes a pet shop.

Pet shop features:

* Shows all cat breeds from the adoption screen
* Each cat costs 20 coins
* Cats already owned will show as “Sold Out”
* The cat chosen at the start is also marked as “Sold Out”
* Players cannot buy the same breed twice

### Study Task System

Players can complete learning tasks to earn coins and experience.

Tasks include:

* Daily check-in
* English vocabulary quiz
* Focused reading
* Math training

Each task can only be completed once every 24 hours.

### Competition System

Players can join learning competitions.

Competition modes include:

* Single-player mode
* Match mode

Subjects include:

* English vocabulary
* English dictation
* Math calculation

Difficulty levels include:

* Easy
* Medium
* Hard

Players can earn coins by answering questions correctly.

### Achievements and Statistics

The game tracks:

* Pet level
* Completed study tasks
* Study time
* Competition wins
* Achievements

## Technologies Used

This project is built with:

* HTML
* CSS
* JavaScript
* LocalStorage for saving game data
* Inline SVG images for shop items and decorations

No external libraries are required.

## How to Run

1. Download or clone this repository.
2. Open the main `.html` file in a browser.
3. Register an account.
4. Choose your cat and start playing.

No installation is required.

## Project Structure

```text
Dream-Pet-Academy/
│
├── index.html
└── README.md
```

If your HTML file has a different name, you can rename it to `index.html` before uploading it to GitHub Pages.

## How to Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload the HTML file and `README.md`.
3. Rename the HTML file to `index.html`.
4. Go to the repository settings.
5. Open the “Pages” section.
6. Select the main branch as the source.
7. Save and wait for GitHub Pages to publish the site.

## Future Improvements

Possible future features:

* More pet types, such as dogs, rabbits, and birds
* More rooms and outdoor scenes
* More clothes and accessories
* More learning subjects
* Sound effects and background music
* More furniture and decoration items
* A real achievement badge system
* More advanced pet animations

## Purpose

This game is designed to help students build better study habits by connecting learning progress with virtual pet care. By completing study tasks, players can earn rewards, take care of their pet, and create a fun learning routine.
