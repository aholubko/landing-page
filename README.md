# MyBike Landing Page

## Introduction

Welcome to the MyBike Landing Page project, implemented according to a Figma design.

This is a responsive single-page website created to present a modern bicycle brand, its products, advantages, and contact information. The main goal of the project was to reproduce the provided design while creating a clear, accessible, and responsive interface for mobile, tablet, and desktop devices.

The project demonstrates practical skills in semantic HTML, responsive layout development, SCSS architecture, reusable styles, and implementation of interactive navigation elements.

## Key Features

- Responsive Design: The page adapts to mobile, tablet, and desktop screen sizes.
- Responsive Header: Includes the company logo, phone link, and hamburger menu.
- Navigation Menu: Allows users to navigate between the main sections of the page.
- Product Comparison Section: Presents different bicycle models with images, descriptions, and prices.
- Product Details Section: Highlights the main advantages and features of the bicycles.
- Contact Section: Provides contact information and a feedback form.
- Smooth Scrolling: Navigation links move smoothly between page sections.
- Interactive Elements: Buttons, links, images, and navigation elements include hover effects and transitions.
- Semantic Structure: The page uses meaningful HTML elements to improve accessibility and maintainability.

## Challenges

This project was one of my first complete responsive landing pages based on a professional Figma design. During its development, I encountered several practical challenges.

### Key Challenges

- Responsive Layout: Adapting the design to different screen sizes required careful work with breakpoints, element dimensions, spacing, and content positioning.

- Header and Hamburger Menu: Creating a navigation menu that worked correctly on smaller screens required coordinating HTML structure, SCSS styles, and anchor navigation.

- Accurate Design Implementation: Reproducing typography, spacing, images, and proportions from the Figma design required detailed comparison and repeated adjustments.

- Reusable SCSS Structure: Organizing styles into separate blocks and utility files helped avoid duplicated code and made the project easier to maintain.

- Image Adaptation: Product images needed to remain correctly aligned and scaled across mobile, tablet, and desktop layouts.

- Form Layout: Creating a responsive contact form required proper handling of inputs, text areas, buttons, and spacing.

Overcoming these challenges helped me improve my understanding of responsive web development, SCSS organization, semantic HTML, and implementation of layouts based on design specifications.

## Technical Requirements

To run this project locally, you need:

- Node.js
- NPM

## Installation and Setup

Follow these steps to install and run the project locally.

### 1. Clone the repository

```bash
git clone https://github.com/aholubko/landing-page.git
``` 

### 2. Navigate to the project directory

```bash
cd landing-page 
```

### 3. Install dependencies

```bash
npm install 
```

### 4. Start the local development server

```bash
npm start 
```

After starting the project, open the local address displayed in the terminal.

## Live Preview

[View the live website](https://aholubko.github.io/landing-page/)

## Design Reference

The project was implemented according to the following Figma design:

[View the MyBike Figma design](https://www.figma.com/file/NZQAIydtHo5QkINyGLHNcq/BIKE-New-Version?node-id=0%3A1)

## Technologies Used

This project was built using the following technologies:

- HTML5: Used to create the semantic structure of the page.
- SCSS: Used to organize reusable styles, variables, mixins, and responsive rules.
- CSS Flexbox: Used for element alignment and flexible layouts.
- CSS Grid: Used for responsive content sections and structured layouts.
- BEM Methodology: Used to create predictable and reusable class names.
- JavaScript: Used where interactive page behavior was required.
- Parcel: Used to build and run the project locally.
- Node.js: Used as the project runtime environment.
- NPM: Used to install and manage project dependencies.
- Git: Used for version control.
- GitHub: Used to store and manage the repository.
- GitHub Pages: Used to deploy the live website.

## Design Specifications

### Responsive Breakpoints

- Desktop: 1024px and wider
- Tablet: 576px and wider
- Mobile: 320px and wider

### Main Design Principles

- Responsive layout
- Consistent spacing
- Reusable components
- Semantic HTML
- Smooth hover effects
- Mobile-first adaptation
- Visual consistency with the Figma design

## Available Scripts

Run the project locally:

```bash
npm start
```

Run the tests:

```bash
npm test 
```

Deploy the project to GitHub Pages:

```bash
npm run deploy
```
