# Control + Mutation = Baked Potato
### A control flow, data-driven language
TODO: Maybe it isn't 'control flow' but instead 'flow control'?
- Use a definition language for flow control
- Use a programming language for programming logic
- It represents the logistics of an application: https://en.wikipedia.org/wiki/Logistics

TODO: Maybe not 'mutation' but instead 'logic operation'?
- I like the idea of calling blocks of logic 'operations' instead of functions/methods/subroutine

---
### Notation Notes

#### Mutation file
```
[Mutation 1 Name] [Input 1 Name] [Input 2 Name] {etc}
[Statement 1]
[Statement 2]
{etc}

[Mutation 2 Name] [Input 1 Name] [Input 2 Name] {etc}
[Statement 1]
[Statement 2]
{etc}
```
- Empty lines indicate new mutation block
  - Therefore, mutation blocks cannot contain empty lines
  - All statements are one after another, no space in-between
  - It feels like a paragraph-style design
- `value` keyword represents the current item from the data set
  - Maybe consider `item` instead since it is less characters

### Current Issues/Ideas
- How to aggregate/increase data sets
- Built-in functomality (printing, etc)
- Show data at each control point
  - Like 'AutoRest spitting out files at each step' concept
  - Call it a `probe` or something like that. You can just place the probe at any control point. Or even have multiple probes, kinda like how you have the 'watch' window for variables in IDEs.
- Output bucket notation in control-side
- Does the language have variables?
  - Variables in most language seem like a poor way to either break up the length of a single statement or 'hold something in-hand' until it is needed
- When creating this, think less 'matematical' and notice what feels natural when solving a problem
  - You should never have to read any information from right-to-left. All reading/writing should be left-to-right.
  - Keyboard keys limit ingenuity a bit because you have only so many default symbols and such.
  - Try to limit amount of modifier keys required (shift, ctrl, alt, etc)
  - Limit number of characters required to make statements
- Programming languages don't display 'time' of operations
  - Consider showing time information in control blocks/nodes/points
  - Consider making them displayed visually, similar to music arranging software (timeline). Maybe color coding or sized differently.
