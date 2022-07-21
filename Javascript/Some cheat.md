### String génération

String.fromCharAt(64 + i) where i is the alphabetical index

`String.fromCharAt(65) => "A"

### Numbers

Determine if a string is a digit : `IsNaN("1231")=> false`

### Array
génération 

`Array.apply(null, new Array(n)).map((x, i) => i)`

```javascript
Array.from({length: 10}, (_, i) => i + 1)
```
==> [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
