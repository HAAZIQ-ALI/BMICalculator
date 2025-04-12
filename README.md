# BMI Calculator (C++)

## Overview
This is a simple console-based BMI (Body Mass Index) calculator written in C++. It takes the user's height (in feet and inches) and weight (in kilograms), performs necessary conversions, calculates the BMI, and then outputs the BMI value along with a health status message.

---

## How to Compile and Run

To compile the program, use a C++ compiler such as `g++`:

```bash
g++ -o bmi bmi.cpp
./bmi
```

---

## Program Flow

1. The program prompts the user to enter their height in feet and inches.
2. It converts the height to total inches and then to meters.
3. It prompts the user to enter their weight in kilograms.
4. It calculates the BMI using the formula:
   
   **BMI = weight (kg) / (height in meters)^2**

5. It classifies the BMI into categories:
   - Underweight (BMI < 18.5)
   - Normal (BMI >= 18.5 and < 25)
   - Overweight (BMI >= 25), with a humorous message.

---

## Example Input/Output

```
Enter Your Height 🏃‍♂️  
feet: 5
Inches: 7
Enter Your Weight In KG ⚖️ : 68
Your 📊 BMI :23.4
🩺 Status     : Normal
```

---

## Notes
- The height is first converted from feet and inches to inches.
- Then inches are converted to meters (1 inch = 0.0254 meters).
- The BMI is calculated using metric units.
- A custom message is printed based on the calculated BMI.

---

## Caution
The BMI categories are generalized and may not be medically precise for every individual. Always consult a healthcare professional for accurate health assessments.

---

## License
This is a simple educational project and can be freely used or modified.

