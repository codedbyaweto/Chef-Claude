# Chef Claude

Chef Claude is a React-based application that generates recipe recommendations using AI, based on the ingredients provided by the user.

Users can add ingredients they currently have, and once enough ingredients are available, Chef Claude suggests a complete recipe with ingredients and step-by-step instructions.

---

## Features

- Add ingredients dynamically
- Conditional UI rendering based on ingredient count
- AI-generated recipe recommendations
- Clean component-based React architecture
- Accessible UI using ARIA live regions

---

## How It Works

1. The user adds ingredients using the input form.
2. Once enough ingredients are added, a **“Get a recipe”** button appears.
3. Clicking the button sends the ingredient list to an AI model.
4. The AI returns a recipe in markdown format.
5. The recipe is displayed in the UI under **Chef Claude Recommends**.

---

## Built With

- React
- JavaScript (ES6+)
- AI API (Claude / Mistral via client-side helper)
- CSS (provided styles)

---

