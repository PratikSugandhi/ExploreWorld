# ExploreWorld — Travel Website

[Live Demo](https://exploreworld-beryl.vercel.app/)

## 📌 About the Project

**ExploreWorld** is a responsive travel website.

The website provides users with an interactive travel experience where they can explore destinations, view travel packages, read testimonials, and navigate to the booking section.

## ✨ Features

* 🌍 Explore different travel destinations
* 📦 Travel packages section
* 💬 Testimonials section
* 📝 Book Now section
* 📱 Responsive design
* 🧭 Smooth navigation between sections
* ♿ Accessibility-focused HTML structure
* 🔊 ARIA labels for improved screen-reader accessibility
* 🎨 Clean and user-friendly interface

## ♿ Accessibility & ARIA Labels

Accessibility was an important part of this project. **ARIA (Accessible Rich Internet Applications) labels** have been used to make interactive elements more understandable to users who rely on screen readers.

Examples include:

```html
<button aria-label="Open navigation menu">
```

```html
<a href="#home" aria-label="Go to Home section">
```

```html
<button aria-label="Close navigation menu">
```

### Why ARIA Labels?

An `aria-label` provides an accessible name for an element when its visible content may not be sufficient for assistive technologies.

For example:

```html
<button>
    ☰
</button>
```

A screen reader may not clearly communicate the purpose of this button.

Instead:

```html
<button aria-label="Open navigation menu">
    ☰
</button>
```

allows a screen reader to communicate the purpose of the button more clearly.

### Accessibility Considerations

This project focuses on:

* Meaningful `aria-label` attributes for interactive controls
* Accessible navigation
* Descriptive names for icon-only buttons
* Semantic HTML elements
* Keyboard-friendly interactive elements
* Clear navigation between website sections
* Better compatibility with screen readers

ARIA labels were specifically considered for elements such as **navigation controls, menu buttons, icons, and other interactive elements** where additional accessible context is useful.

## 🛠️ Technologies Used

* HTML5
* CSS3

## 📂 Project Structure

```text
21-days-project-1/
│
├── index.html
├── style.css
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Open the project

Open the project folder in VS Code.

### 3. Run the website

You can open `index.html` directly in a browser or use the **Live Server** extension in VS Code.

## 🌐 Live Website

🔗 **ExploreWorld:**
https://exploreworld-beryl.vercel.app/

## 🎯 Project Goal

The goal of this project was to build a travel website while also paying attention to **responsive design, user experience, navigation, and web accessibility**.

A particular focus was placed on using **ARIA labels** to make interactive elements more accessible to users using assistive technologies such as screen readers.

