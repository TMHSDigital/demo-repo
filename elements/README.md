# Interactive Elements Demo

This section demonstrates various interactive elements and components that can be used in the project.

## Buttons

### Primary Button
<button class="primary">Click me!</button>

### Secondary Button  
<button class="secondary">Learn more</button>

### Disabled Button
<button disabled>Not available</button>

## Form Elements

### Text Input
<input type="text" placeholder="Enter your name">

### Checkbox
<input type="checkbox" id="terms"> 
<label for="terms">I agree to the terms</label>

### Radio Buttons
<input type="radio" name="choice" id="opt1">
<label for="opt1">Option 1</label>
<br>
<input type="radio" name="choice" id="opt2">
<label for="opt2">Option 2</label>

## Progress Indicators

### Loading Spinner
<div class="spinner"></div>

### Progress Bar
<progress value="70" max="100"></progress>

## Alerts

### Success Alert
<div class="alert success">
  Operation completed successfully!
</div>

### Error Alert  
<div class="alert error">
  Something went wrong. Please try again.
</div>

## Interactive Cards

### Hover Card
<div class="card hover">
  <h3>Hover Me</h3>
  <p>This card has hover effects</p>
</div>

### Click Card
<div class="card clickable">
  <h3>Click Me</h3>
  <p>This card is clickable</p>
</div>

## Tooltips

Hover over <span class="tooltip" data-tip="This is a tooltip!">this text</span> to see a tooltip.

## Accordions

<details>
  <summary>Click to expand</summary>
  <p>This is expandable content that can be toggled.</p>
</details>

## Tabs

<div class="tabs">
  <button class="tab active">Tab 1</button>
  <button class="tab">Tab 2</button>
  <button class="tab">Tab 3</button>
</div>

---

These elements can be styled using CSS and enhanced with JavaScript for full interactivity. See the documentation for implementation details.
