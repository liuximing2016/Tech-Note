React中的setState是异步、有回调：

```
this.setState(
    { state },
    () => {} //回调
);
```

dva中dispatch reducer是同步、无回调、无Promise：

```
this.props.dispatch({
    type: 'save',
    payload: { state },
});
```

dva中dispatch effects是异步、有Promise：

```
this.props.dispatch({ type: 'initQuery' })
    .then((res) => {})
    .catch((err) => {});
```



