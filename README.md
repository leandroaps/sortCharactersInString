# sortCharactersInString
This snippet can be used to alphabetically sort the characters in a string.

```
const sortCharactersInString = str => [...str].sort((a, b) => a.localeCompare(b)).join('');
```

**Usage:**
```
sortCharactersInString('cabbage'); // 'aabbceg'
```
