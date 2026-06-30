<h2 class="c-project-heading--task">Style the bullet points</h2>

Add a style to change the bullet points to squares instead of circles.

## Step 1

Add this code to the CSS file:

<div class="c-project-code">
--- code ---
---
language: css
line_numbers: true
line_number_start: 5
line_highlights: 11-13
---
hr {
    height: 4px;
    border: none;
    background-color: orange;
}

ul {
    list-style-type: square;
}
--- /code ---

</div>

## Now run your code

Click on **Run** and check that the bullet points in the ingredients list are square.


<div class="c-project-output">

![The preview showing the recipe for banana milkshake with square bullet points in the ingredients list.](images/step9.png){:style=“width:50%;“}

</div>


