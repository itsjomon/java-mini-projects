# Calorie Calculator
A simple Java console application that calculates your daily calorie needs based on your age, gender, weight, height, and activity level using the Basal Metabolic Rate (BMR) formula, specifically the Revised Harris-Benedict Equations (1984).

## Sample Input & Output

```
Calorie Calculator
Enter your gender (M/F): M
Enter your age (in years): 30
Enter your weight (in kilograms): 75
Enter your height (in centimeters): 180
Enter your activity level (sedentary/moderate/active): moderate

Your Basal Metabolic Rate (BMR) is: 1795 calories per day.
Your estimated daily calorie needs are: 2782 calories per day.
```

## Formula
- **Men**: `88.362 + (13.397 × weight in kg) + (4.799 × height in cm) − (5.677 × age in years)`
- **Women**: `447.593 + (9.247 × weight in kg) + (3.098 × height in cm) − (4.330 × age in years)`
- **Multipliers**: `Sedentary ×1.2` | `Moderate ×1.55` | `Active ×1.725`

## Run

- Clone the repo:
  ```bash
  git clone https://github.com/itsjomon/java-mini-projects.git
  ```
  
- Navigate to the project directory:
  ```bash
  cd java-mini-projects/calorie-calculator
  ```
  
- Compile and Run:
  ```bash
  javac src/App.java
  
  java -cp src App
  ```
