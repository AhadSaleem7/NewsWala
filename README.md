# NewzWala

NewzWala is a responsive news aggregator web application built with React. It leverages the [NewsAPI](https://newsapi.org/) to fetch the latest headlines from various categories such as business, entertainment, health, science, sports, and technology. The app features infinite scrolling, a dynamic top-loading progress bar, and a search functionality that lets users filter news by keywords. Notably, the search query state is updated only when the user submits the search form (and not on every keystroke) to avoid making excessive API calls.

## Features

- **Multiple News Categories:** Browse headlines from categories like general, business, entertainment, health, science, sports, and technology.
- **Search Functionality on Submit:** Filter news articles by keywords using a search form that updates the state only on submit to minimize unnecessary API calls.
- **Infinite Scrolling:** Load more articles seamlessly as you scroll down.
- **Top Loading Bar:** Visual indicator of page loading progress.
- **Responsive Design:** Works well on desktops, tablets, and mobile devices.

## Getting Started

This project is intended to be run locally. Follow the instructions below to copy the repository and run the application on your local machine.

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/en/) (v12 or higher)
- npm (which comes with Node.js) or yarn

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/newzwala.git
   cd newzwala
