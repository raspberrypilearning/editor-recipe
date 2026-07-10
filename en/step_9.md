## Style the bullet points

Add a style to change the bullet points to squares instead of circles.

Add this code to the CSS file:

```css line_numbers="true" line_number_start="5" line_highlights="11-13"
hr {
    height: 4px;
    border: none;
    background-color: orange;
}

ul {
    list-style-type: square;
}
```

## Now run your code

Click on **Run** and check that the bullet points in the ingredients list are square.

![The preview showing the recipe for banana milkshake with square bullet points in the ingredients list.](images/step9.png){:style="width:50%;"}
