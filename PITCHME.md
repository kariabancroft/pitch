@title[Introduction]
## React Concepts
##### <span style="font-family:Helvetica Neue; font-weight:bold">Ada Curriculum Plan</span>

---

## Learning Goals

@title[Learning Goals]

- JSX
- Component Creation |
- Components render other Components |
- props  |
- state |
- Styling components |
- Stateful components with Stateless components |
- Container components and Presentational components |
- Validation via propTypes  |

---
@title[Using JSX]

## Using JSX
JSX is a preprocessor most often used within React. It looks very similar to HTML with a few key differences.
<span style="font-size:0.6em; color:gray">Press Down key for examples.</span> |

![Press Down Key](assets/down-arrow.png)

+++
@title[JSX]
#### JSX

<br>

+++
@title[Block: JSX Snippets]

```javascript
<h1>Hello, World!</h1>

<h1>Hello, { name }!</h1>

<h1 className="welcome">Hello, { name }!</h1>
```

@[1](Basic JSX element usage)
@[3](Use a variable within a JSX element)
@[5](To add a class we must use `className` instead of `class` because `class` is reserved)

---

## Creating a Component
<span style="font-size:0.6em; color:gray">Press Down key for examples.</span>

![Press Down Key](assets/down-arrow.png)

+++
@title[Component Creation]

#### Create a Component

<br>

+++?code=code/sample.js&lang=javascript&title=Source: Components

@[1-2](Necessary imports)
@[4](Component class definition)
@[5-11](Constructor options)
@[13-15](Render function)
@[18](Render the component class created above)

---
