# Debuggable TypeScript Node.js Template

A simple maven-style TypeScript Node.js project template that supports

- Setting breakpoints in TypeScript source files in Visual Studio Code. This requirement is of paramount importance.
- Separation of source code (TypeScript) and target code (JavaScript). How can anyone bear with seeing `index.ts`, `index.js.map`, and `index.js` next to each other? 

## Usage

```bash
git clone https://github.com/jyuhuan/node-ts
code node-ts  # Or open the folder from VS Code 
```

Run the tsc task (by pressing Cmd+Shift+P, typing in `run task`, and selecting `Tasks: Run Task`).

Set a breakpoint in `src/main.ts`.

Launch debugging and observe the debugger stop at the breakpoint.

## Tested Environment

- node 6.10.0
- tsc 2.2.1
- VS Code 1.10.1


## Reference

Read more in [this article](https://medium.com/@yuhuan/debuggable-maven-style-typescript-node-js-project-set-up-for-visual-studio-code-dc6b4c18b2fe#.yg01n35o9).