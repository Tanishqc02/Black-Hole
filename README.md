# Black Hole Facts Web Application

A single-page web application that displays and filters interesting facts about black holes, featuring a dark space-themed design.

## Description

This application presents 20 curated facts about black holes in an interactive card-based layout. Users can filter facts by different categories to explore specific aspects of black hole physics and astronomy.

## Features

- Interactive fact cards with hover effects
- Category-based filtering system
- Responsive grid layout
- Space-themed dark mode design
- Single-file implementation

## Implementation Options

### Single-File Version
- One self-contained `index.html` file including all HTML, CSS, and JavaScript
- No external dependencies required
- Ideal for quick deployment and testing

### Multi-File Version (Alternative Setup)
- `index.html` - Main HTML structure
- `styles.css` - Stylesheet
- `app.js` - Application logic and data

## Installation

1. Download the `index.html` file
2. Open it in any modern web browser

No server setup or additional dependencies required.

## Usage

- Open the application to view all black hole facts
- Use the dropdown menu to filter facts by categories:
  - Basic
  - Physics
  - Structure
  - Formation
  - Observation

## Data Structure

The application uses a JSON structure for facts:
```json
{
  "id": number,
  "fact": "string",
  "category": "string",
  "source": "string"
}
