# Personal Portfolio - Claire Wairimu

## Author
Claire Wairimu

## Description
I am Claire Wairimu from IYF S12. This is my portfolio for Week 2 CSS. Week 1 was only HTML, now I added CSS.

## Live Demo
My personal Week 2 CSS Webpage: [View Live Website](https://gakuruclaire39-cmd.github.io/iyf-s12-week-02-gakuruclaire39-cmd/)

My personal Week 1 HTML Webpage: [View Live Website](https://gakuruclaire39-cmd.github.io/iyf-s12-week-01-gakuruclaire39-cmd/)

## Technologies Used

I only used HTML and CSS, no javascript.

- HTML5 - header, nav, main, section, article, footer
- CSS3
- I used CSS variables for colors like --color-primary
- Google Fonts - Montserrat and Open Sans
- Flexbox for navbar and footer
- CSS Grid for gallery and projects
- Media queries for responsive - 768px, 1024px, 1280px
- Git and GitHub Pages for hosting

## Features

- I have 4 pages: Home, About, Projects, Contact. Plus 3 practice pages.

- Home page has hero section.

- Projects page has grid - on phone 1 column, tablet 2 columns, desktop 3 columns.

- About page has image and text side by side on desktop, one column on phone.

- Contact page has form, on desktop form + sidebar, on phone full width.

Practice pages:
- box-model-practice.html - shows box model
- flexbox-practice.html - nav, cards, footer with flex
- grid-practice.html - gallery 3 cols and magazine layout

Other features:
- Hamburger menu on phone using CSS only
- Hover effects on buttons and cards
- Responsive images
- No horizontal scroll

I used semantic HTML so screen readers can read.

## How to Run

1. Clone repo:
2. Open `index.html` in browser or use Live Server in VS Code
3. No install needed - pure HTML/CSS

## Pages

- index.html is my home page
- about.html is about me
- projects.html shows my projects in grid
- contact.html has form
- box-model-practice.html I practiced box model there
- flexbox-practice.html flexbox examples
- grid-practice.html grid gallery and magazine layout
  
## Lessons Learned

- Before I didn't know why my layout was breaking, now I know border-box makes it easier because padding doesn't add extra width.

- I learned flexbox is good for nav and one line things, grid is better for gallery and many columns.

- I used to start with desktop then fix mobile, but now I start with mobile first then add tablet and desktop with min-width. It's easier.

- I learned how to make header span full width in grid, you use grid-column 1 / -1. Took me time to understand.

- Also object-fit cover helps image not stretch in grid.

- Hamburger menu I made with checkbox only, no javascript. When checkbox is checked, nav shows.

- And hover effects make site look better, just add transition 0.3s and translateY -2px.

- I also finished flexbox froggy 24 levels and grid garden 28 levels, they helped me understand.

## Challenges Faced

- My biggest challenge was cards having different heights. One card with more text was taller. I asked and learned to make card display flex and flex-direction column, then p flex-grow 1. Now they are equal.

- Second challenge was images overflowing. My images were big and breaking the grid. I fixed with width 100% and max-width 100% and object-fit cover and height 200px.

- Third was horizontal scroll on phone. On 320px my site was scrolling left-right. I fixed by adding overflow-x hidden on body and box-sizing border-box for all.

- Also nav was not centering vertically. I added align-items center on navbar.

- For grid, header and footer were not spanning full width. I searched and found grid-column 1 / -1. Now it works.

- Hamburger menu was also hard. I didn't want javascript so I used checkbox hack. Input hidden then label with ☰.

- Testing on different widths took time but I did 320px, 768px, 1024px and 1440px as task said.
