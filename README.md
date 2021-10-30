# Control + Mutation = Baked Potato
### A control flow, data-driven language
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
- `value` keyword represents the current item from the data set
  - Maybe consider `item` instead since it is less characters

### Current Issues
- How to aggregate/increase data sets
- Built-in functomality (printing, etc)
- Show data at each control point
  - Like 'AutoRest spitting out files at each step' concept
- Output bucket notation in control-side
