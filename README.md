## attrs

Shortcut to [attr](http://github.com/azer/attr).attrs

```js
me = attrs({ name: 'Azer Koculu', age: 25, status: 'Writing Code' }

me.age()
// => 25

me.age(26)
// => 26

me.status('Drinking Tea')

me.status.subscribe(function(newStatus, oldStatus){
  
  newStatus
  // => Drinking Tea

})

```

## Install

```bash
$ npm install attrs
```

![](https://dl.dropbox.com/s/9q2p5mrqnajys22/npmel.jpg?token_hash=AAHqttN9DiGl63ma8KRw-G0cdalaiMzrvrOPGnOfDslDjw)
