# Taco Riendo Website
## About the Restaurant
Taco Riendo is a small Mexican food spot in Tulare, CA. It is family-owned and known for its burritos and tacos. 
## Author
Jovanni Corona
## Description of Project
I am building a four-page website for Taco Riendo because they currently do not have one.
## Technologies
- HTML
- CSS
- JavaScript
## Pages
- Home (index.html)
- Menu (menu.html)
- About (about.html)
- Contact (contact.html)
## Progress
- Part 1: Outline and style guide, complete
- Part 2: HTML structure for all 4 pages, complete
- Part 3: CSS styling, responsive design, and hamburger menu, complete
## Notes
- Taco Riendo isn't on any of the food delivery apps so the site uses a "Call to Order" button that dials the restaurant instead of an "Order Now" delivery link.
- The menu was reorganized from the in-store menu into cleaner categories, and the items that had the same price and a choice of meat were grouped together.
- The logo and mascot were recreated as SVGs in Adobe Illustrator, using the colors from the style guide.
- Prices are based on the current in-store menu.
## Image Credits
- Food photos from Pexels and Unsplash
- Storefront photo: Taco Riendo's listing in hey-restaurants.com
## Part 3: CSS & JavaScript
- Style guide was applied across all 4 pages (colors, fonts, button systems and spacing scale).
- Responsive layouts, for mobile, tablet and desktop.
- JavaScript hamburger menu for mobile navigation.
### CSS Approach
- Chose custom CSS because it's what I'm most comfortable with.
- Flexbox for nav, hero, and buttons; Grid for featured items, the menu, the footer, and location.
- CSS variables for colors, fonts, and an 8-point spacing scale.
- Focus states, 44px minimum touch targets, and aria-labels.
### JavaScript
- Hamburger menu: Only on screens smaller than 768px. Clicking ☰ opens a top down menu from the nav revealing the nav links. When the menu is open the ☰ changes to an X using if. 
### Challenges & What I Learned
- Small typos broke code, as a result I was more careful checking my code as I typed.
- The logo I created for part 2 disappeared into the background because "Riendo" was the same color as the background. I created a different version of the logo that made "Riendo" old lace to fix the accessibility issue.
- JavaScript: I failed to capitalize textContent and I messed up using toggle vs contains on the hamburger menu.
- The hamburger menu couldn't animate because it was display:none so I made it max-height: 0 with overflow: hidden to make it be able to animate.