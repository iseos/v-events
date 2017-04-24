# Vuejs events
[Non Parent-Child Communication](https://vuejs.org/v2/guide/components.html#Non-Parent-Child-Communication)

This package consists of two lines of code:
```javascript
import Vue from 'vue'
export default new Vue()
```

## Installing
Using npm:
```bash
npm install --save v-events
```

Using yarn:
```bash
yarn add v-events
```

## Usage
```javascript
import VueEvents from 'v-events'
...
// Call event
VueEvents.$emit('my-event', 1)
...
// Listener event
VueEvents.$on('my-event', function (id) {
  // ...
})
```

