# LocalStorage in JavaScript: How to Use?

To use localStorage in your web application, there are five methods to choose from:
1. setItem(): Add key and value to localStorage;
2. getItem(): Retrieve a value by the from localStorage;
3. removeItem(): Remove an item by key from localStorage;
4. clear(): Clear all localStorage;
5. key(): Passed a number to retrieve nth key of a localStorage.


# LocalStorage JavaScript Limitation

1. Do not store sensetive user information;
2. It is not a substitute for a server based database as information is only stored on the browser;
3. LocalStorage is limited to 5MB across all major browsers;
4. LocalStorage is quite insecure as it has no form of data protection and can be accessed by any code on your web page;
5. LocalStorage is synchronous. Meaning each operation called would only execute one after the another.