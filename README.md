# SpiceGarden - Digital Restaurant Menu

SpiceGarden is a responsive digital restaurant menu website built using **HTML, CSS, and JavaScript**. It includes food search, category filtering, a simple cart counter, and an AI Food Assistant connected to **Ollama**.

## Features

- Responsive restaurant menu design
- Hero section with restaurant branding
- Menu categories:
  - Main Course
  - Snacks
  - Drinks
  - Dessert
- Search food items by name
- Filter menu items by category
- Add food items to cart with a cart counter
- AI Food Assistant using Ollama
- Uses the `llama3.2` Ollama model
- Mobile-friendly layout

## Menu Items

| Food | Category | Price |
|---|---|---:|
| Chicken Biryani | Main Course | ₹220 |
| Paneer Biryani | Main Course | ₹180 |
| Masala Dosa | Snacks | ₹90 |
| Veg Burger | Snacks | ₹120 |
| Mango Juice | Drinks | ₹70 |
| Cold Coffee | Drinks | ₹100 |
| Gulab Jamun | Dessert | ₹80 |
| Ice Cream | Dessert | ₹90 |

## Project Structure

```text
SpiceGarden/
├── index.html
├── README.md
└── requirements.txt
```

## Requirements

- A modern web browser such as Chrome, Edge, or Firefox
- VS Code (recommended)
- VS Code Live Server extension (recommended)
- Ollama for the AI Food Assistant
- Ollama model: `llama3.2`

## Installation

### 1. Install Ollama

Install Ollama from the official Ollama website.

After installation, open Command Prompt or PowerShell and run:

```bash
ollama pull llama3.2
```

### 2. Start Ollama

Run:

```bash
ollama serve
```

Ollama should be available at:

```text
http://localhost:11434
```

The website code sends requests to:

```text
http://localhost:11434/api/generate
```

### 3. Open the Website

Save the provided HTML code as:

```text
index.html
```

Open the project folder in VS Code.

Then right-click `index.html` and select:

```text
Open with Live Server
```

## How to Use

1. Open the website in your browser.
2. Use **View Menu** to move to the menu section.
3. Use the search box to search for food.
4. Select a category to filter food items.
5. Click **Add to Cart** to increase the cart count.
6. Enter a question in the **AI Food Assistant**.
7. Click **Ask Ollama**.
8. Ollama will recommend suitable items from the available menu.

### Example AI Question

```text
Recommend a spicy vegetarian meal
```

The AI is instructed to recommend only items available in the restaurant menu and to mention the food name and price.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Ollama
- Llama 3.2

## Notes

The current project is a frontend application. The cart only maintains a simple item count in the browser and does not include payment, checkout, database storage, or user authentication.

The Ollama connection requires Ollama to be running locally and the `llama3.2` model to be installed.

## Author

SpiceGarden Digital Restaurant Menu - 2026
