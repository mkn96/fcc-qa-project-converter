<p class="has-line-data" data-line-start="0" data-line-end="1">A full stack JavaScript app that is functionally similar to this: <a href="https://metric-imperial-converter.freecodecamp.rocks/">https://metric-imperial-converter.freecodecamp.rocks/</a>. Working on this project will involve you writing your code using one of the following methods:</p>
<p class="has-line-data" data-line-start="2" data-line-end="8">Complete the necessary conversion logic in /controllers/convertHandler.js<br>
Complete the necessary routes in /routes/api.js<br>
Copy the sample.env file to .env and set the variables appropriately<br>
To run the tests uncomment NODE_ENV=test in your .env file<br>
To run the tests in the console, use the command npm run test. To open the Replit console, press Ctrl+Shift+P (Cmd if on a Mac) and type “open shell”<br>
Write the following tests in tests/1_unit-tests.js:</p>
<p class="has-line-data" data-line-start="9" data-line-end="26">convertHandler should correctly read a whole number input.<br>
convertHandler should correctly read a decimal number input.<br>
convertHandler should correctly read a fractional input.<br>
convertHandler should correctly read a fractional input with a decimal.<br>
convertHandler should correctly return an error on a double-fraction (i.e. 3/2/3).<br>
convertHandler should correctly default to a numerical input of 1 when no numerical input is provided.<br>
convertHandler should correctly read each valid input unit.<br>
convertHandler should correctly return an error for an invalid input unit.<br>
convertHandler should return the correct return unit for each valid input unit.<br>
convertHandler should correctly return the spelled-out string unit for each valid input unit.<br>
convertHandler should correctly convert gal to L.<br>
convertHandler should correctly convert L to gal.<br>
convertHandler should correctly convert mi to km.<br>
convertHandler should correctly convert km to mi.<br>
convertHandler should correctly convert lbs to kg.<br>
convertHandler should correctly convert kg to lbs.<br>
Write the following tests in tests/2_functional-tests.js:</p>
<p class="has-line-data" data-line-start="27" data-line-end="32">Convert a valid input such as 10L: GET request to /api/convert.<br>
Convert an invalid input such as 32g: GET request to /api/convert.<br>
Convert an invalid number such as 3/7.2/4kg: GET request to /api/convert.<br>
Convert an invalid number AND unit such as 3/7.2/4kilomegagram: GET request to /api/convert.<br>
Convert with no number such as kg: GET request to /api/convert.</p>
