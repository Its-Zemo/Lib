# Events Documentation

## postrender Event
Fires after the rendering process is complete.

```javascript
element.addEventListener('postrender', (e) => {
  console.log('Rendering completed!');
});
```

## process Event
Fires during the processing phase.

```javascript
element.addEventListener('process', (e) => {
  console.log('Processing started!');
});
```

## Event Flow
1. `process` - During processing
2. `postrender` - After rendering