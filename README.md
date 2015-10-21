# subxy ( DRAFT )


### init()
how many child processes that we want to support ?

### register('name', '/path/to/function')
getting a function into the pool

### exec

```js
subxy.exec('name', arguments)
  .on('done', function(err, result) {
  });
```
