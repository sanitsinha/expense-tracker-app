# Expense Tracker Web App

## Overview
This is a simple and interactive expense tracking web application built using JavaScript, HTML, and CSS. The app allows users to add, view, and delete expenses while maintaining a running total.

The application stores data in the browser using localStorage, ensuring that user data persists across sessions.

---

## Features
- Add new expenses with name and amount  
- Delete individual expenses dynamically  
- Real-time total expense calculation  
- Persistent data storage using browser localStorage  
- Input validation to ensure correct data entry  
- Efficient event handling using event delegation  

---

## How It Works
1. User enters expense name and amount  
2. On form submission:
   - Data is validated  
   - Expense is added to an internal array  
   - Data is saved to localStorage  
3. Expenses are rendered dynamically on the UI  
4. Total amount is recalculated using JavaScript array methods  
5. Users can delete expenses, which updates both UI and storage  

---

## Tech Stack
- **Languages:** JavaScript, HTML, CSS  
- **Concepts Used:**  
  - DOM Manipulation  
  - Event Handling  
  - Event Delegation  
  - localStorage API  
  - Array methods (reduce, filter)  

---

## Code Highlights
- Used `localStorage` for persistent data storage  
- Implemented `reduce()` to calculate total expenses efficiently  
- Used `filter()` for deleting expenses  
- Applied event delegation to handle dynamically created elements  

---

## Future Improvements
- Add expense categories (Food, Travel, etc.)  
- Add edit functionality for existing expenses  
- Add monthly/weekly analytics  
- Improve UI/UX with better styling  

---

## Learnings
- Strengthened understanding of DOM manipulation and event handling  
- Learned how to manage application state using arrays  
- Gained experience with browser storage APIs (localStorage)  
- Improved ability to build interactive web applications  

---

## How to Run
1. Clone the repository  
2. Open `index.html` in your browser  
3. Start adding expenses  

---

## Contributing
Feel free to fork the repository and submit pull requests for improvements.
