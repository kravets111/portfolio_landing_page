# "The MET" - this is museum website. Here you can see what current exhibitions are and contact us.
  - [DEMO LINK](https://kravets111.github.io/portfolio_landing_page/)
  - [The MET landing](https://www.figma.com/file/lSR1m42L9YwzQwzzxKwHpw/THE-MET)

## Core Technologies:

**Frontend Technologies:**
* **HTML5** – page structure with semantic tags
* **SCSS/Sass** – CSS preprocessor for styling

## Architectural Approaches:

**CSS/SCSS Organization:**
* **BEM Methodology** – for class naming (e.g., `now-on-view__content`, `contacts__form--input`)
* **Modular Architecture** – separating styles into individual files inside the `blocks/` folder
* **SCSS Mixins** – for responsive design (`@include onTablet`, `@include onDesktop`)

## Responsive Design:

**Breakpoints:**
* Mobile-first approach
* Tablet: `576px` and up
* Desktop: `1260px` and up

**CSS Grid System:**
* Adaptive grid (2 columns → 6 columns → 12 columns)
* Using CSS Grid for layout

## Additional Technologies:

**Fonts:**
* Google Fonts (Roboto, Cinzel)

**Images:**
* WebP format for optimization
* Responsive images with different versions for various screens

**Forms:**
* HTML5 forms with validation
* GET method used for demonstration purposes

## Implementation Details:

* **CSS-only menu** – no JavaScript, uses the `:target` selector
* **Smooth scroll** behavior
* **CSS transitions** and **hover effects**
* **Flexbox** and **CSS Grid** for layout
* **CSS Custom Properties** (variables) in the `variables.scss` file

The project is a static website for the MET Museum with a modern responsive design, built using pure HTML & SCSS.


## Getting start project:

* **Clone the repository:**
* git clone https://github.com/kravets111/portfolio_landing_page.git
* git cd portfolio_landing_page

* **Install dependencies:**
* npm install

* **Run the project locally:**
* npm start


