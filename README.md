# Simple Calculator (React)

## 📖 What the project does
This project is a **simple calculator web app** built with React.  
It allows users to perform basic arithmetic operations (addition, subtraction, multiplication, division) with a clean, grid-based UI. The calculator supports digit entry, decimal points, deletion, clearing, and evaluation of expressions.

---

## 🛠 Tools & Languages Used
- **React (v19+)** — for building the UI and managing state with `useReducer`.
- **JavaScript (ES6+)** — core language for logic and components.
- **CSS** — for styling the calculator grid, buttons, and output display.
- **Node.js & npm** — for package management and running the development server.
- **react-scripts** — to bootstrap and run the React app.

---

## 🚀 Steps to Build and Run
1. **Clone the repository** (or copy the project folder):
   using following terminal commands :
   git clone <your-repo-url>
   cd simpleCalculator/calculator
2. **Install dependencies**
   using following terminal command in simpleCalculator/calculator directory :
   npm install
3. **Start the development server**
   using following terminal command in simpleCalculator/calculator directory :
   npm start
   The app will run at http://localhost:3000.
4. Challenges I faced :
- The app wasn't running locally at first due to not being in the correct directory containing package.json
- Had issues rendering the UI since my code was calling ReactDOM.render but it was removed in react 18+
  so, I had to import from "react-dom/client" and use createRoot to make it run.
- The app wasn't deploying due to incorrect setup of directory in Vercel
5. 🔗 **Live Demo**
   [Open Calculator on Vercel](https://calculator-e26qgqllq-abdullah-al-abir-shafins-projects.vercel.app/)
