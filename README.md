# Roman-Numeral-Converter

You can access the converter here:
https://fadliazharr.github.io/Roman-Numeral-Converter/

# Roman Numeral Converter  

## Overview  

This is a simple **Roman Numeral Converter** built using **HTML, CSS, and JavaScript**. It allows users to enter a number between **1 and 3999**, click a button, and instantly see its **Roman numeral equivalent**.  

## Features  

- **User-friendly interface** with a clean, minimal design.  
- **Instant conversion** of numbers to Roman numerals.  
- **Input validation** to ensure only valid numbers are processed.  
- **Responsive design**, making it accessible on different devices.  

## How It Works  

1. **User Input**  
   - The user enters a number in the input field.  
   - The number must be between **1 and 3999**.  

2. **Conversion Logic**  
   - The JavaScript script takes the number and converts it into a **Roman numeral** using a predefined mapping.  
   - It loops through the values from **largest to smallest**, appending the corresponding Roman numeral symbols.  

3. **Output Display**  
   - The converted Roman numeral is displayed below the input field.  
   - If the user enters an invalid number (empty, non-numeric, or out of range), a relevant error message appears.  

## Code Breakdown  

### 1. **HTML Structure (`index.html`)**  
- A simple interface with:  
  - An input field for the number.  
  - A button to trigger the conversion.  
  - A `<p>` tag to display the result.  

### 2. **Styling (`styles.css`)**  
- A centered, modern **card-style container** with a white background.  
- A **blue button** that changes color on hover.  
- Responsive input field styling.  

### 3. **JavaScript Logic (`script.js`)**  
- Listens for a button click.  
- Validates the input and converts it using a **Roman numeral mapping** array.  
- Displays the result or an appropriate error message.  

## Usage  

1. Open `index.html` in a web browser.  
2. Enter a number (between **1 and 3999**) in the input field.  
3. Click **Convert** to see the Roman numeral representation.  

### Example Inputs & Outputs  

| Input | Output |
|--------|--------|
| `4` | `IV` |
| `29` | `XXIX` |
| `99` | `XCIX` |
| `500` | `D` |
| `3999` | `MMMCMXCIX` |

## Future Enhancements  

- Add a **Roman numeral to number converter**.  
- Improve UI with animations or a dark mode.  
- Allow keyboard shortcuts for faster conversion.  

---

