<img width="1280" height="640" alt="image" src="https://github.com/user-attachments/assets/af583f61-c101-4071-815d-e90e92b81f83" />

# 🥤 SipWise: The Drinks Info Hub

## 📌 Basic Details

**Team Name:** velvet  

### 👥 Team Members
- **Member 1:** [jaziya ebrahim] - [viswajyothi college of engneering and tecnology]  
- **Member 2:** [anughraha vinu] - [viswajyothi college of engneering and tecnology]  

### 🔗 Hosted Project Link
[Click here to view the live project](https://jaziya-143.github.io/velvet2/)

---

## 📖 Project Description

A comprehensive web-based beverage encyclopedia that separates drinks into categories for kids and adults. It provides detailed nutritional information, ingredients, and pricing for everything from healthy smoothies to popular energy drinks.

---

## ❗ The Problem Statement

Consumers, especially parents, often struggle to find clear, categorized information about what's inside common beverages. General search results are often cluttered with advertisements rather than specific ingredient data and calorie counts.

---

## 💡 The Solution

SipWise provides a clean, distraction-free interface with an integrated age-gate. It allows users to filter between:

- **Healthy Drinks** (for kids)
- **General Beverages** (for adults)

Data is presented in easy-to-read cards with high-quality visuals.

---

# ⚙️ Technical Details

## 🖥️ Technologies/Components Used

### For Software

- **Languages Used:** HTML5, CSS3, JavaScript (ES6+)  
- **Frameworks Used:** None (Vanilla JS implementation)  
- **Tools Used:** VS Code, Git, GitHub Pages (for hosting)  

---

# ✨ Features

- 🔒 **Age Verification Gate**  
  A mandatory entry point to ensure appropriate content delivery.

- 🔄 **Dynamic Content Switching**  
  Uses a Single Page Application (SPA) approach to toggle between Adult and Kid sections without refreshing.

- 🔙 **Navigation History**  
  A custom JavaScript-based "Back" button system that allows users to retrace their steps through the app.

- 🧾 **Detailed Beverage Cards**  
  Displays brand, cost, ingredients, quality, quantity, and flavors for every drink.

- 🔥 **Nutritional Highlighting**  
  The Healthy Drinks section includes specific calorie counts (kcal) to promote wellness.

---

# 🚀 Implementation

## 💻 For Software

### 📥 Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/sipwise-drinks-hub.git
```

Navigate into the project directory:

```bash
cd sipwise-drinks-hub
```

---

### ▶️ Run

Since this project is built using vanilla web technologies, no build step is required.

You can run it by:

- Opening the `index.html` file directly in any web browser  
- Using the **Live Server** extension in VS Code for real-time updates  

---

# 📚 Project Documentation

## 📸 Screenshots
 ![Screenshot 1](/Screenshot%202.png)
![Screenshot 2](/Screenshot%202.png)
![Screenshot 3](/Screenshot%202.png)
- The Age-Gate entry point ensuring user compliance  
- The custom selection hub where users choose between Kid and Adult profiles  
- Detailed drink information cards showing ingredients and pricing  

---

## 📊 Diagrams

### Application Workflow

- Navigation is managed by a central `MapsTo` function  
- The DOM is dynamically updated  
- Application state is tracked in a `navigationHistory` array  

---

# 🤖 AI Tools Used

**Tool Used:** Gemini  

**Purpose:**  
- Assistance in structuring the CSS Flexbox layout for the drink cards  
- Debugging the `navigationHistory` array logic for the back-button functionality  

### 🔑 Key Prompts Used

- *"How can I implement a back button in a single-page HTML file without using a router library?"*  
- *"Create a responsive flexbox layout for product cards that wrap on mobile screens."*

**Percentage of AI-generated code:** ~25%

### 👨‍💻 Human Contributions

- Curating the beverage database (ingredients, costs, brands)  
- Designing the color palettes and UI transitions  
- Manual testing of the state-based navigation logic  

---

# 👥 Team Contributions

- **[Your Name]:** Logic implementation (JavaScript), Age-gate system, and documentation  
- **[Partner Name]:** UI/UX design (CSS), Content curation, and Image assets management  

---

# 📄 License

This project is licensed under the MIT License — see the `LICENSE` file for details.
