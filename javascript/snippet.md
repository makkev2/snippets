### Snippets

```javascript
/**
 * For loops
 */

/**
 * Spread Operator
 */

avengers = ['Captain America', 'Iron Man', 'Thor'];
avengers = [...avengers, ...['Hulk', 'Hawkeye', 'Black Widow']]
// ['Captain America', 'Iron Man', 'Thor', 'Hulk', 'Hawkeye', 'Black Widow'];

/**
 * Maps
 * similar to a dictionary
 */
const romanNumerals = new Map();
romanNumerals.set(1,'I');

romanNumerals.set(2, 'II').set(3, 'III').set(4, 'IV').set(5, 'V')

/**
 * Defining Function
 */
function hello(){
    console.log('Hello World!');
}

/**
 * Function Expressions
 */
const goodbye = function() {
    console.log('Goodbye World!');
};

/**
 * Invoking a Function
 */
hello();
// reference a function without invoking
goodbye;
// << [Function: goodbye]


/**
 * Arrow Functions
 */
const square = x => x * x;

// with no parameters
const hello = () => alert('Hello World!');


/**
 * Callbacks
 * A function that is passed as an argument.
 */
function sing(song, callback) {
    console.log(`I'm singing along to ${song}.`);
    callback();
}

// anonymous function as a callback
sing('Let It Go', () => {
    console.log("I'm standing on my head.");
});

// sorting an array of numbers by providing a callback function
[1, 3, 12, 5, 23, 18, 7].sort( (a, b) => {return a - b;} );



```
