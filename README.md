# Exploring Different Ways to Style in React

This project features a sign-up page styled using various methodologies to understand their advantages and disadvantages. The methods explored are:

- Vanilla CSS
- Inline Styling
- CSS Modules
- Styled Components
- Tailwind CSS

## Styling Methodologies

### 1. Vanilla CSS

Vanilla CSS refers to the traditional way of writing CSS styles in separate `.css` files.

#### Pros
- **Simplicity:** Easy to write and understand.
- **Browser Support:** Well-supported across all browsers.
- **Separation of Concerns:** Styles are kept separate from JavaScript.

#### Cons
- **Global Scope:** Styles are global, leading to potential naming conflicts.
- **Maintainability:** Can become unwieldy in larger projects.
- **No Dynamic Styling:** Limited ability to use dynamic values directly in styles.

### 2. Inline Styling

Inline styling involves applying styles directly to elements using the `style` attribute.

#### Pros
- **No Dependencies:** No need for external stylesheets.
- **Dynamic Styles:** Easily apply dynamic styles based on component state.

#### Cons
- **Reusability:** Styles are not reusable.
- **Readability:** Can make JSX markup harder to read.
- **Limited Features:** Lacks the full power of CSS (e.g., media queries, pseudo-classes).

### 3. CSS Modules

CSS Modules allow you to write CSS that is scoped locally to the component.

#### Pros
- **Local Scope:** Avoids naming conflicts by scoping styles locally.
- **Maintainability:** Easier to manage in large projects.
- **Reusability:** Styles can be reused across components.

#### Cons
- **Configuration:** Requires build configuration.
- **Learning Curve:** May have a learning curve for new developers.

### 4. Styled Components

Styled Components utilize tagged template literals in JavaScript to style components.

#### Pros
- **Component-Based:** Styles are tied directly to components.
- **Dynamic Styling:** Supports dynamic and conditional styling.
- **No Class Name Bugs:** Automatically generates unique class names.

#### Cons
- **Bundle Size:** Can increase the JavaScript bundle size.
- **Learning Curve:** Requires learning the Styled Components library.
- **Tooling:** May need additional tooling for optimal performance.

### 5. Tailwind CSS

Tailwind CSS is a utility-first CSS framework for rapid UI development.

#### Pros
- **Speed:** Fast to develop with pre-built utility classes.
- **Consistency:** Ensures consistent styling across the application.
- **Customization:** Highly customizable via configuration.

#### Cons
- **Readability:** Can lead to cluttered JSX with many utility classes.
- **Learning Curve:** Requires understanding of Tailwind’s utility classes.
- **Purging:** Must configure purging to remove unused styles in production.

## Summary of Pros and Cons

| Method              | Pros                                                                                                                                         | Cons                                                                                                                                           |
|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| **Vanilla CSS**     | Simplicity, Browser Support, Separation of Concerns                                                                                           | Global Scope, Maintainability, No Dynamic Styling                                                                                              |
| **Inline Styling**  | No Dependencies, Dynamic Styles                                                                                                               | Reusability, Readability, Limited Features                                                                                                     |
| **CSS Modules**     | Local Scope, Maintainability, Reusability                                                                                                     | Configuration, Learning Curve                                                                                                                  |
| **Styled Components** | Component-Based, Dynamic Styling, No Class Name Bugs                                                                                        | Bundle Size, Learning Curve, Tooling                                                                                                           |
| **Tailwind CSS**    | Speed, Consistency, Customization                                                                                                             | Readability, Learning Curve, Purging                                                                                                           |



## Prerequisites

Please install the following: 

- [Node](https://nodejs.org/en/download/package-manager)
- NPM(Node Package Manager): `npm install -g npm`
- Vite: `npm i vite`

## Installation

Install Tic-Tac-Toe with npm

```bash
  npm install
```
    