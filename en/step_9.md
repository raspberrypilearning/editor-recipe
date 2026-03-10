<h2 class="c-project-heading--task">Style the line</h2>

--- task ---

Add CSS code to set the style of the line. 

--- /task --- 


--- task ---

Add the code below to the CSS file. 

Edit the code:
- Replace `orange` with a colour you like. 
- Change the `height` to make the line thinner or thicker.

--- /task ---

<div class="c-project-callout c-project-callout--tip">

### Tip

In `height: 2px` px is short for pixels, and is the number of dots on a screen. 

</div>


<div class="c-project-code">
--- code ---
---
language: css
line_numbers: true
line_number_start: 1
line_highlights: 5-9
---
body {
    color: blue;
}

hr {
    height: 4px;
    border: none;
    background-color: orange;
}
--- /code ---

</div>

--- task ---

Click **Run** to see the new style.

--- /task ---

<div class="c-project-output">

![A recipe for banana milkshake in light red with a light red line underneath it](images/step10.png)

</div>
