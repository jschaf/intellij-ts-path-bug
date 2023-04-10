# IntelliJ 2023.1 TypeScript paths and import unused bug

This is a minimal reproduction of a bug in IntelliJ 2023.1 where IntelliJ
doesn't recognize TypeScript tsconfig.paths and flags unused imports incorrectly.

IntelliJ incorrectly shows the function `someAlphaFunction` as unused. 
The function is used by `bravo.ts`.

<img width="1277" alt="Screenshot 2023-04-10 at 1 56 02 PM" src="https://user-images.githubusercontent.com/22385/230997639-1013051a-cd4f-4fe9-b6e0-be276c79a547.png">
