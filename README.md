# react-faster

React snippets for TypeScript done right.

Many people are not good in memorizing magic acronims like `rcc`, `imr`, and similar.

So many books on coding stress on importance of readable names. So, it's okay to spell out snippets' prefixes:

![](./images/v0-0-2--main-demo.gif)

## List of Snippets

### Component Snippets

| Prefix (name)                            | Snipper result                                    |
|------------------------------------------|---------------------------------------------------|
| `react-component-functional`             | React functional component.                       |
| `react-component-class-stateteless`      | React class component without state.              |
| `react-component-class-stateteful`       | React class component with state.                 |
| `react-mobx-component-functional`        | mobx-enabled React functional component.          |
| `react-mobx-component-class-stateteless` | mobx-enabled React class component without state. |
| `react-mobx-component-class-stateteful`  | mobx-enabled React class component with state.    |

### Hook Snippets

| Prefix (name)                                        | Snipper result                                                                |
|------------------------------------------------------|-------------------------------------------------------------------------------|
| `react-hook-useState-initialize-immediately`         | Template of State Hook with immediate initialization.                         |
| `react-hook-useState-initialize-lazily`              | Template of State Hook with delayed initialization using a callback function. |
| `react-hook-useEffect`                               | Template of Effect Hook.                                                      |
| `react-hook-useEffect-with-cleanup`                  | Template of Effect Hook with a cleanup function.                              |
| `react-hook-useEffect-with-dependencies`             | Template of Effect Hook with explicit dependencies.                           |
| `react-hook-useEffect-with-cleanup-and-dependencies` | Template of Effect Hook with a cleanup function and explicit dependencies.    |
