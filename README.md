# JavaScript-Date-object
Building a date formatter



In JavaScript, there are many built-in constructors that create objects. A constructor is like a regular function, but starts with a capital letter, and is initialized with the new operator.

For example, you can use the Date() constructor with the new operator to create a new Date object that returns a string with the current date and time:

    const currentDate = new Date();
    console.log(currentDate);

// Output:
// Mon Aug 23 2021 15:31:00 GMT-0400 (Eastern Daylight Time)

The Date object has a number of methods that allow you to get the date and time in different formats.

One of those is the .getDate() method, which returns a number between 1 and 31 that represents the day of the month for that date. For example:

    const date = new Date();
    const dayOfTheMonth = date.getDate();
    console.log(dayOfTheMonth); // 20

The .getMonth() method returns a number between 0 and 11. This represents the month for the date provided, where 0 is January and 11 is December. Because the number this method returns is zero-based, you need to add 1 to it to get the expected month number.

The .getFullYear() method returns a number which represents the year for the provided date.

In JavaScript, the change event is used to detect when the value of an HTML element has changed:

    element.addEventListener("change", () => {
        
    });

A switch statement is used to compare an expression against multiple possible values and execute different code blocks based on the match. It's commonly used for branching logic.

For example, here's how to compare the expression dayOfWeek against possible values:

    switch (dayOfWeek) {
    case 1:
        console.log("It's Monday!");
        break;
    case 2:
        console.log("It's Tuesday!");
        break;
    // ...cases for other workdays
    default:
        console.log("It's the weekend!");
    }

The split() method is used to divide a string into substrings based on a specified separator. It then returns these substrings as elements of an array.

Here is an example of taking the words "Hello World" and returning an array of one element:

    const greeting = "Hello World";
    greeting.split(); // ["Hello World"]

The split method takes in a parameter known as a separator. The separator is used to tell the computer where each split should occur.

Here is an example of using an empty string as a separator:

    // returns ["h", "e", "l", "l", "o"]
    "hello".split(""); 
Other examples of separators can include a space " ", or a hyphen "-". If you don't provide a separator, the method will return an array with the original string as the only element.

To reverse an array of elements, you can use the reverse method. This method reverses the order of the elements in the array in place. The first element becomes the last, and the last element becomes the first.

Here is an example of using the reverse method:

    // returns [5, 4, 3, 2, 1]
    [1, 2, 3, 4, 5].reverse(); 

In the previous project, you learned how to work with the join method. This method takes an array of elements and joins them into a string. Similar to the split method, the join method also takes an optional separator. If you don't provide a separator, the default separator is a comma.

Here is an example of using the join method:

    // returns "1-2-3-4-5"
    [1, 2, 3, 4, 5].join("-");

If your switch statement is going to have multiple cases, it is best practice to include a break statement.

The break statement will tell the JavaScript interpreter to stop executing statements. Without adding a break statement at the end of each case block, the program will execute the code for all matching cases:

    switch (someVariable) {
    case 'case123':
        // Write your logic here
        break; // Terminates the switch statement
    }
    
In a switch statement, the default case is executed when none of the previous case conditions match the value being evaluated. It serves as a catch-all for any other possible cases. For example:

        const dayOfWeek = 7;

        switch (dayOfWeek) {
        case 1:
            console.log("It's Monday!");
            break;
        case 2:
            console.log("It's Tuesday!");
            break;
        // ...cases for other workdays
        default:
            console.log("It's the weekend!");
        }
        