# Black Hole Facts Web Application

A simple, interactive single-page web application that displays various facts about black holes with category filtering capabilities.

## Features

- Display of 20 curated black hole facts
- Category-based filtering system
- Responsive card-based layout
- Dark theme design suitable for astronomical content
- Hover animations for interactive elements

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript

## Installation

1. Download the `index.html` file
2. Open the file in any modern web browser

That's it! No additional setup or dependencies required.

## Usage

- View all facts on initial load
- Use the dropdown menu at the top to filter facts by category:
  - All Categories
  - Basic
  - Physics
  - Structure
  - Formation
  - Observation

## Structure

The application is contained in a single `index.html` file that includes:
- HTML markup for the page structure
- CSS styles in the `<style>` section
- JavaScript code including the facts database in the `<script>` section

## Data Structure

Each fact in the database follows this format:
```json
{
  "id": number,
  "fact": "string",
  "category": "string",
  "source": "string"
}
