# Use ChatGPT to translate coding language
To use ChatGPT to translate `JavaScript` code into `TypeScript`, you can provide the `JavaScript` code to ChatGPT and ask it to provide the equivalent `TypeScript` code.

## Example
Here's an example of how you can use ChatGPT to translate a simple JavaScript function into TypeScript.
To translate this code into TypeScript, you can provide it to ChatGPT in a question format like this:


JavaScript code
``` javascript
function add(a, b) {
  return a + b;
}
```
Can you provide the equivalent TypeScript code for the following JavaScript function?


## Result

ChatGPT will then provide the equivalent TypeScript code for the function:


```typescript
function add(a: number, b: number): number {
  return a + b;
}
```
This TypeScript code adds type annotations to the function parameters and return type, making it more type-safe and easier to understand.