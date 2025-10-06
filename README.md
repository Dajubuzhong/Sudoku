# Sudoku

A pure HTML and CSS implementation of Sudoku.

## Links

- **Live Website**: [https://dajubuzhong.github.io/Sudoku/](https://dajubuzhong.github.io/Sudoku/)
- **GitHub Repository**: [https://github.com/Dajubuzhong/Sudoku](https://github.com/Dajubuzhong/Sudoku)
- **Collaborator**: Zhongjie Ren ([https://github.com/LorenzZR](https://github.com/LorenzZR))

## Project Overview

This project is a mock Sudoku website featuring 8 pages including home, game selection, easy mode (6×6), hard mode (9×9), rules, high scores, login, and register pages. The site is built entirely with HTML and CSS, with no JavaScript.

## Pages

1. **Home** - Welcome page with game mode selection
2. **Selection** - List of available Sudoku games
3. **Easy Game** - 6×6 Sudoku grid with 2×3 sub-grids
4. **Hard Game** - 9×9 Sudoku grid with 3×3 sub-grids
5. **Rules** - Game instructions and credits
6. **High Scores** - Leaderboard with mock data
7. **Login** - User login form
8. **Register** - New user registration form

---

## Assignment Writeup

### 1. What was the most challenging piece of this assignment? Did you find it easy or challenging to work with HTML and CSS? How long did this overall assignment take you?

The hardest part of this assignment was building a mobile-friendly navigation bar that shows all links neatly in a grid at the top of the screen. HTML itself was quite simple to work with, but CSS was definitely more difficult—especially when using Grid layout, media queries, and trying to make everything responsive on different screen sizes. Overall, the project took around 25–30 hours. A lot of that time went into designing the Sudoku grids, fixing layout bugs, and testing how the site looked on different devices.

### 2. What decisions did you make when you made your site mobile friendly?

I decided to keep the navigation bar at the top on mobile devices but made it more compact by using a 4-column grid for the 8 links. This layout keeps everything visible without needing JavaScript. For scaling, I used relative units like rem and % instead of fixed pixels, and added breakpoints at 768px and 480px to gradually adjust the layout and text size for tablets and phones. These changes helped the site stay clean and readable on all screen sizes.

### 3. What did you take into account when you developed the design of your website? Is there anything that you're particularly proud of?

When designing the site, I wanted to keep a consistent and modern look. I chose a dark theme with gradient highlights that match the feeling of a puzzle game. I'm especially proud of the smooth animations and transitions I added, such as hover effects on buttons and navigation links. I'm also happy with how well the layout adapts to mobile screens — all content stays easy to read and accessible whether on desktop or mobile. Creating that level of polish with just HTML and CSS felt very rewarding.

### 4. Given more time or resources, what additional features would you add to your site in the future?

If I had more time, I'd like to add more detailed instructions with pictures and short tutorials for new players. I'd also include extra difficulty levels beyond just easy and hard — maybe medium and expert modes with different grid sizes. I'd improve the high scores page with sorting and filtering features, and build a user profile section to display personal stats and achievements. Finally, I'd add a settings page where users could customize the site's color theme and Sudoku grid style using CSS variables.

### 5. How many hours did you spend on this assignment?

About 25-30 hours in total.