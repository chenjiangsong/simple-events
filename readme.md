# useAge

```js
import EventEmitter from './index.js'

const events = new EventEmitter()

events.on('log', function (info) {
	console.log(info)
})

events.emit('log', 'hello world')
```