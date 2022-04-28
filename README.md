# Type script hello-world application

https://www.typescripttutorial.net/typescript-tutorial/typescript-hello-world/

## Prerequisites

- node.js (https://nodejs.org/en/download/)
- TypeScript(https://www.typescriptlang.org/download)
    - `npm install -g typescript`

  ### Optional
    - ts-node (https://www.typescripttutorial.net/typescript-tutorial/setup-typescript/)
        - `npm install -g ts-node`

## For creating new TypeScript project

1. Create a new TypeScript file called `app.ts`:
    ``` typescript
    let message: string = 'Hello, World!';
    // create a new heading 1 element
    let heading = document.createElement('h1');
    heading.textContent = message;
    // add the heading the document
    document.body.appendChild(heading);
    ```
3. Create a new `index.html` file:
    ```html
    <!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>TypeScript: Hello, World!</title>
        </head>
        <body>
            <script src="app.js"></script>
        </body>
    </html>
    ```
4. `tsc app.ts`
5. Open index.html in browser