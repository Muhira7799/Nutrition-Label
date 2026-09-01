# 🥗 Nutrition Facts Label

A detailed **Nutrition Facts Label** recreated using HTML and CSS. This project focuses on accurately structuring nutritional information and using CSS to create a clean, organized label similar to those found on food packaging.

## 📌 Features

* Nutrition Facts heading
* Serving information
* Calories section
* Daily Value percentages
* Total Fat and Saturated Fat
* Cholesterol and Sodium
* Total Carbohydrates
* Dietary Fiber and Sugars
* Added Sugars
* Protein
* Vitamin D, Calcium, Iron, and Potassium
* Daily Value explanation
* Custom borders and dividers
* Responsive and structured layout

## 🛠️ Technologies Used

* **HTML5** – For the structure and nutritional information
* **CSS3** – For layout, typography, spacing, borders, and styling
* **Google Fonts** – Open Sans


## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/Nutrition-Label.git
```

2. Open the project folder.

3. Open `index.html` in your web browser.

An internet connection is required to load the Open Sans font from Google Fonts.

## 🎨 CSS Concepts Used

This project demonstrates several CSS concepts:

* Universal selector
* `box-sizing: border-box`
* Flexbox
* Margins and padding
* Borders and dividers
* Font sizing using `rem` and `em`
* Font weights
* Text indentation
* Element alignment
* Child and descendant selectors
* The `:not()` pseudo-class

### Flexbox Example

The calorie information uses Flexbox to position the calorie value:

```css
.calories-info {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
}
```

The nutritional information is also aligned using:

```css
p {
  display: flex;
  justify-content: space-between;
}
```

## 🎯 Learning Objectives

This project helps practice:

* Building structured HTML layouts
* Working with nested elements
* Creating reusable CSS classes
* Using Flexbox for alignment
* Understanding margins and padding
* Creating visual dividers with borders
* Working with relative font units
* Styling complex information displays
* Recreating real-world UI components with CSS


This project was created for educational and learning purposes.
