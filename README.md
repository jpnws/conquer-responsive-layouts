<h1>Conquering Responsive Layouts - Challenges</h1>
<p>A set of responsive CSS3 layout challenges and notes from Kevin Powell's online course.</p>

<hr>

<details open>
    <summary>Notes on <code>rem</code> & <code>em</code></summary>
    <ul>
        <ul>Try to stick with using either em or rem throughout the site.</ul>
        <ul>Use em for adaptibility and rem for consistency.</ul>
        <ul>Padding might need to adapt sometimes, for buttons, so use em for button paddings.</ul>
        <ul>Margins might need consistency sometimes, between blocks/buttons/elements, so use rem in such cases.</ul>
        <ul>em for padding and margin takes the font-size of the element for which em is being applied.</ul>
        <ul>rem for padding and margin takes the font-size of the root element no matter what.</ul>
        <ul>em font-size takes on the font-size of the parent element, and it compounds.</ul>
    </ul>
<details>

<details open>
    <summary><b>Using Percentages for Width, and Avoiding Heights</b></summary>
    <p>Learned that using percentage for width is recommended for responsive layouts. Also, height should not be used in many cases to avoid overflowing content when displaying the webpage in smaller viewport sizes.</p>
    <ul>
        <li>👨‍💻 <a href="https://github.com/jiparkdev/conquer-responsive-layouts/tree/master/percentages-width" target="_blank">Source Code</a></li>
        <li>🔗 <a href="https://jiparkdev.github.io/conquer-responsive-layouts/percentages-width" target="_blank">Live Demo</a></li>
    </ul>
</details>

<details open>
    <summary><b>Using Max-Width and Width Properties</b></summary>
    <p>Learned that max-width property could help us in avoiding the issue of content stretching out too much on larger viewport sizes. So, the recommendation is to have both widths as a percentage and max-width as a fixed value.</p>
    <ul>
        <li>👨‍💻 <a href="https://github.com/jiparkdev/conquer-responsive-layouts/tree/master/percentages-width" target="_blank">Source Code</a></li>
        <li>🔗 <a href="https://jiparkdev.github.io/conquer-responsive-layouts/max-width" target="_blank">Live Demo</a></li>
    </ul>
</details>
