
**1. List all the Escape Sequences characters in javascript.**
| Code  | Result|
| ------------- | ------------- |
| \b  | Backspace  |
| \f  | Form feed  |
| \n  | New line  |
| \r  | Carriage return|
| \t  | Horizontal tabulator|
| \v  | Vertical tabulator|
| \\'  | Single quote|
| \\"  | Double quote  |
| \\\  | Backslash  |

**2. Explain with example length and substring methods in javascript**
- The length funtion in javascript is used to return the length of the object, array and string 
EX: "hello".length =>\\ 5
- The substring() method extracts characters, between two indices, from a string, and return the substring
EX: "hello".substring(1,4) => ell

**3. What are padStart and padEnd in javascript, explain with an example.**
- padStart - padStart() methond pads the current string with another string (multiple times, if needed) untill the resulting string reaches the given length. the padding is applied from the start of the current string.
- EX: const str1 = '8';
console.log(str1.padStart(2, '0'));
// expected output: "08"

- padEnd - padEnd() method pads the currrent string with a given string (repeated, if needed) so that the resulting string reaches a given length. The padding is applied from the end of the current string.
-EX: const str1 = 'hello';
console.log(str1.padEnd(7, '.'));
// expected output: "hello.."

**4. Define Global Object in javascript along with the global scope.**
- Global object - A global object is an object that always exists in the global scope. In JavaScript, there's always a global object defined.
- Global scope - global scope is that hte variyable declared globally (out side any function) have global scope. global variyables cabn be accessed from anywhere in a javascript program.

**5. List all the names of Javascript engines present currently.**
- V8
- SpiderMonkey
- Chakra
- Tamarin
- Nashorn
- JavaScriptCore
