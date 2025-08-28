# MLSE-Web-development-Internship-week4-tasks

# Task 1: E-Commerce Discount System - Technical Implementation

## Task Description

The goal of this task was to create a web-based discount calculator for an e-commerce platform that applies category-specific discounts to product prices. The system needed to:

1. Accept product price and category inputs from users
2. Apply appropriate discounts based on category:
   - Electronics: 10% discount
   - Clothes: 20% discount
   - Food: 5% discount
3. Calculate and display the final price after discount
4. Provide a user-friendly interface with validation and feedback

## JavaScript Implementation

### Core JavaScript Features Used:

1. **DOM Manipulation**
   - `document.getElementById()` to access HTML elements
   - `element.textContent` to update text content dynamically
   - `element.style.display` to show/hide the results section

2. **Event Handling**
   - `addEventListener()` to handle button click events
   - Input validation before processing

3. **Conditional Logic**
   - `switch` statement to handle different discount rates based on category
   - `if` statements for input validation

4. **Arithmetic Operations**
   - Percentage calculations for discounts
   - Subtraction to calculate final price

5. **Data Validation**
   - Checking for valid numerical input
   - Ensuring a category is selected

6. **String Manipulation**
   - Template literals for dynamic text generation
   - `toFixed()` method for currency formatting

## Technical Achievements

This implementation demonstrates:
- Clean separation of concerns (HTML, CSS, JavaScript)
- Responsive design principles
- User input validation
- Dynamic UI updates
- Professional code organization and commenting
- Cross-browser compatibility

The solution effectively meets all requirements while providing an excellent user experience with visual feedback and error handling.






# Task 2: Voting Eligibility Checker

## Description
A web application that determines voting eligibility based on age and citizenship status.
The system implements nested conditional logic to check if a user meets the requirements to vote.

## Features
- **Age Verification**: Checks if user is 18 years or older
- **Citizenship Validation**: Verifies citizenship status
- **Nested Conditional Logic**: 
  - Eligible to vote if age ≥ 18 AND citizen = true
  - Not a citizen if citizen = false
  - Too young to vote if under 18
- **Visual Feedback**: Color-coded results with appropriate icons
- **Input Validation**: Ensures valid age input and citizenship selection

## Technical Implementation
- Clean HTML5 structure with semantic markup
- Modern CSS with gradient backgrounds and responsive design
- JavaScript with event handling and conditional statements
- User-friendly interface with clear feedback mechanisms






# Task 3: Object Property Checker

## Description
A web application that demonstrates JavaScript object property checking using the `in` operator. Users can verify if specific properties exist in a predefined person object and modify the object dynamically.

## Features
- **Property Existence Check**: Uses the `in` operator to verify if properties exist
- **Object Visualization**: Displays the current state of the person object
- **Interactive Object Management**: 
  - Add new properties with custom values
  - Remove existing properties
  - Reset object to default state
- **Visual Feedback**: Color-coded results indicating property status
- **Input Validation**: Ensures valid property names are entered

## Technical Implementation
- Clean HTML5 structure with code display area
- Modern CSS with developer-friendly styling
- JavaScript object manipulation and dynamic DOM updates
- User-friendly interface for interacting with JavaScript objects
