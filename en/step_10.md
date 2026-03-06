<h2 class="c-project-heading--task">Bullet styles</h2>

--- task ---

Add a style to change the bullet points to squares instead of circles:

--- /task ---

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

--- task ---

Click **Run** to see the new shape.

--- /task ---

</div>

<div class="c-project-output">

![A recipe for banana milkshake with bullet points in the shape of squares](images/recipe-ul-css.png){:style=“width:50%;“}

</div>