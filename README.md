// Import the 'random' library (Math.random()) to randomly choose between "Hello" and "Goodbye"
// There are no external libraries needed for this, just JavaScript itself.

// Array of names
const names = ["Alice", "Bob", "Charlie", "David", "Eve"];

// Function to generate a random boolean value (true or false)
function getRandomBoolean() {
    return Math.random() < 0.5;
}

// Loop through the names
for (const name of names) {
    // Use the random boolean value to determine the greeting
    const greeting = getRandomBoolean() ? "Hello" : "Goodbye";
    
    // Print the greeting along with the name
    console.log(`${greeting}, ${name}!`);
}
