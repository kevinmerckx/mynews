# Warmup Exercise: Filter Incomplete Tasks

## Problem Statement
Imagine you're working on a to-do list application. You need to implement a utility function that takes an array of tasks and returns a new array containing only the tasks that are not marked as completed.

## Requirements
- Implement a function `filterIncompleteTasks` in TypeScript.
- The function should accept an array of task objects where each task has:
  
  ```ts
  type Task = {
    id: number;
    title: string;
    completed: boolean;
  };
  ```

- Return only the tasks where `completed === false`.

## Example

### **Input:**
```ts
const tasks = [
  { id: 1, title: "Write documentation", completed: false },
  { id: 2, title: "Fix login bug", completed: true },
  { id: 3, title: "Refactor component", completed: false }
];
```

### **Expected Output:**
```ts
[
  { id: 1, title: "Write documentation", completed: false },
  { id: 3, title: "Refactor component", completed: false }
]
```

