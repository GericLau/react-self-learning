# React Note

## Syntax 语法

### Demo01

```javascript
<script type="text/babel">
    ReactDOM.render(
        // use comma , to separate lines
        <h1>Hello World!</h1>,
        // no need semicolon ;
        document.getElementById('example')
    );
</script>
```
1. type babel for JSX
2. use comma , to separate lines
3. no need semicolon ;

### Demo02

Each child in an array or iterator should have a [unique "key" prop](https://fb.me/react-warning-keys).

### Demo04: Define a component

1. Use React.createClass to define a component
2. component variable must start with a upper case letter
3. render function must include
4. [Components](https://facebook.github.io/react/docs/components-and-props.html) are like JavaScript functions. They accept arbitrary inputs (called "props") and return React elements describing what should appear on the screen.

### Demo06: propTypes

用propTypes可以来验证component的属性