# Simple BMI Calculator - RevoU Fundamental Course Software Engineering Mini Project

#### 📌 Goal

The goal of this mini project was to create a website of BMI Calculator as a way to practice the main responsibilities of a software engineer. This website allows users to quickly determine their health category based on their weight and height.

---

#### 🔬 Methodology

1. **Requirement Analysis:** The system must allow users to input gender, weight (kg) and height (cm), calculate BMI, and display the explanation of the BMI Form & Result.
2. **System Design**: The BMI is calculated using the standard formula:
    
    $$
    BMI = \frac{weight\ (kg)}{(height\ (m))^2}
    $$
    
    The result is then classified into:
    
    - Underweight (BMI < 18.5)
    - Ideal (18.5 ≤  BMI < 24.9)
    - Overweight (25 ≤ BMI < 29.9)
    - Obese (BMI ≥ 30)
    
    The system flow includes input → validation → calculation → category classification → result display.
    
3. **Implementation:** The application is developed using:
    - HTML: Structure of the application
    - CSS: Styling and responsive layout
    - JavaScript: BMI calculation logic and interactivity
4. **Testing and Evaluation:** The system is evaluated based on calculation accuracy, usability, and overall user experience. 

---

#### 🌟 **Key Features**

- Input validation (prevents empty or invalid values)
- Real-time BMI calculation
- Automatic BMI classification (Underweight, Normal, Overweight, Obesity)
- Simple and responsive user interface

---

📊 **Results**

**Github Pages:** https://floweredscent.github.io/30-oct-23-floweredscent/

The application successfully calculates BMI with accurate results and correctly classifies users into standard BMI categories.

**Future Improvements:**

- Improve the user interface with better visual design and layout optimization.
- Provide personalized health recommendations
