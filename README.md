# DEPRECATED!

# Vuejs events
[Non Parent-Child Communication](https://vuejs.org/v2/guide/components.html#Non-Parent-Child-Communication)

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

