# NASM Calorie Calculator

A comprehensive, professional-grade web application for calculating BMR, TDEE, and creating personalized nutrition plans based on the NASM (National Academy of Sports Medicine) methodology.

## Features

### 🎯 Core Calculations
- **BMR (Basal Metabolic Rate)** - Using the Mifflin-St. Jeor equation
- **TDEE (Total Daily Energy Expenditure)** - With 5 activity level multipliers
- **Goal Weight Planning** - With timeline and daily calorie targets
- **Macronutrient Distribution** - Interactive pie chart with preset diets

### 📊 Calculation Methods

#### BMR Calculation (Mifflin-St. Jeor Equation)
- **Men**: BMR = 10 × weight(kg) + 6.25 × height(cm) - 5 × age + 5
- **Women**: BMR = 10 × weight(kg) + 6.25 × height(cm) - 5 × age - 161

#### TDEE Multipliers
- Sedentary (little to no exercise): 1.2
- Lightly Active (light exercise 1-3 days/week): 1.375
- Moderately Active (moderate exercise 3-5 days/week): 1.55
- Very Active (hard exercise 6-7 days/week): 1.725
- Extremely Active (hard exercise & physical job): 1.9

#### Macronutrient Conversion
- Carbohydrates: 4 calories per gram
- Protein: 4 calories per gram
- Fat: 9 calories per gram

### 🎨 User Interface
- **Multi-step Form** - 6 intuitive steps with progress tracking
- **Responsive Design** - Works on mobile, tablet, and desktop
- **Unit Conversion** - Supports both U.S. (imperial) and Metric units
- **Interactive Charts** - Visual pie chart for macronutrient distribution
- **Weight Progression** - Visual timeline showing projected weight change

### 📥 Export Features
- **CSV Download** - Spreadsheet-ready format for Excel/Google Sheets
- **JSON Download** - Structured data for integration with other tools
- **Print Functionality** - Clean, professional printable results

### ⚠️ Safety Validations
- Age limits: 13-120 years
- Weight limits: 50-500 lbs (or kg equivalent)
- Height validation
- Goal rate warnings:
  - Weight loss > 2 lbs/week triggers warning
  - Weight gain > 1 lb/week triggers warning

## How to Use

1. **Open the Calculator**
   - Simply open `index.html` in any modern web browser
   - No installation or server required

2. **Step 1: Basic Information**
   - Enter client name
   - Select units (U.S. or Metric)
   - Input weight, height, biological sex, and age
   - Click "Start"

3. **Step 2: BMR Display**
   - Review calculated BMR
   - Click "Continue"

4. **Step 3: Activity Level**
   - Select appropriate activity level
   - TDEE updates automatically
   - Click "Continue"

5. **Step 4: Goal Weight**
   - Enter target weight
   - Set timeline (days or date)
   - Review safety warnings
   - Click "Continue"

6. **Step 5: Macronutrient Ratios**
   - Choose diet preset or customize
   - Adjust sliders for custom ratios
   - View interactive pie chart
   - Click "Finish"

7. **Step 6: Results Dashboard**
   - Review all calculations
   - Download CSV or JSON
   - Print results
   - Edit or reset as needed

## Diet Presets

| Diet Type | Carbs | Fats | Protein |
|-----------|-------|------|---------|
| Default | 40% | 30% | 30% |
| Low Carb | 25% | 40% | 35% |
| High Protein | 30% | 25% | 45% |
| Balanced | 33% | 33% | 34% |

## Example Calculations

### Sample Client
- 30-year-old male
- Weight: 180 lbs (81.6 kg)
- Height: 6'0" (183 cm)
- Activity: Moderately Active
- Goal: Lose 15 lbs in 180 days

### Results
- **BMR**: 1,816 calories
- **TDEE**: 2,815 calories (1,816 × 1.55)
- **Daily Target**: 2,095 calories (to lose ~1.75 lbs/week)
- **Macros** (40/30/30):
  - Carbs: 838 cal (210g)
  - Fats: 629 cal (70g)
  - Protein: 629 cal (157g)

## Technical Details

- **Technology**: Pure HTML/CSS/JavaScript (vanilla, no frameworks)
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **Responsive**: Mobile-first design with CSS Grid/Flexbox
- **File Size**: ~61KB (single file, no dependencies)
- **Offline Ready**: Works without internet connection

## Color Scheme

- Primary Blue (#2E5C8A) - BMR sections
- Primary Green (#4A9B8E) - TDEE sections
- Primary Purple (#8E4A9B) - Goal/Macro sections
- Primary Orange (#D17D32) - Accent elements

## Data Privacy

- All calculations performed locally in browser
- No data sent to external servers
- No cookies or tracking
- Optional local storage for session persistence

## Use Cases

- Personal trainers working with clients
- Nutritionists creating meal plans
- Fitness professionals in assessments
- Individuals tracking their own nutrition
- Health coaches and wellness consultants

## License

This calculator is provided as-is for professional use by nutrition and fitness professionals.

## Support

For issues or questions, please refer to NASM guidelines and consult with qualified nutrition professionals for client-specific advice.

---

**Disclaimer**: This calculator is a tool for estimation purposes. Results should be validated by qualified healthcare or nutrition professionals. Individual needs may vary based on health conditions, medications, and other factors not captured by standard equations.
