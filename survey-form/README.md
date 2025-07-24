# Build a Survey Form

## Objective: 
Build an app that is functionally similar to https://survey-form.freecodecamp.rocks


# 📋 Survey Form Requirements

## Overview
This document outlines the technical requirements for building a compliant survey form with proper HTML structure and validation.

## 🎯 Core Requirements

### Page Structure
1. **Page Title**: Create an `<h1>` element with `id="title"` containing the main page heading
2. **Description**: Include a `<p>` element with `id="description"` providing a brief explanation of the form's purpose
3. **Form Container**: Implement a `<form>` element with `id="survey-form"` to wrap all form controls

### 📝 Input Fields

#### Required Text Inputs
4. **Name Field**: 
   - Input element with `id="name"` and `type="text"`
   - Corresponding label with `id="name-label"`
   - Include descriptive placeholder text

5. **Email Field**:
   - Input element with `id="email"` and `type="email"`
   - Corresponding label with `id="email-label"`
   - Built-in HTML5 validation for email format
   - Include descriptive placeholder text

6. **Number Field**:
   - Input element with `id="number"` and `type="number"`
   - Corresponding label with `id="number-label"`
   - Must include `min` and `max` attributes for range validation
   - HTML5 validation prevents non-numeric input
   - Include descriptive placeholder text

### 🎛️ Selection Controls

7. **Dropdown Menu**:
   - Select element with `id="dropdown"`
   - Minimum of two `<option>` elements

8. **Radio Button Group**:
   - At least two radio buttons grouped by shared `name` attribute
   - Allow single selection from multiple options

9. **Checkbox Group**:
   - Multiple checkbox inputs for multi-selection
   - Each checkbox must have a `value` attribute

### 💬 Additional Elements

10. **Comments Section**:
    - `<textarea>` element for additional user feedback
    - Allows multi-line text input

11. **Submit Button**:
    - Button element with `id="submit"`
    - Triggers form submission when clicked

## ✅ Validation Features

- **Email Validation**: Automatic HTML5 format checking
- **Number Validation**: Range checking based on `min`/`max` attributes
- **Input Type Validation**: Browser-level prevention of invalid characters
- **Required Field Validation**: Ensures essential fields are completed

## 🎨 User Experience

- All form fields include descriptive labels for accessibility
- Placeholder text provides helpful hints and examples
- Clear visual hierarchy with proper heading structure
- Intuitive form flow from top to bottom