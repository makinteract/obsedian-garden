---
{"dg-publish":true,"permalink":"/code/typescript-notes-from-udemy/"}
---

### Course details

[Course page](https://www.udemy.com/course/typescript-for-professionals/?couponCode=24T4FS22124)

### Type Class (video 3)

```js
class Queue<T>{
	priovate data: Array<T> = []
}
```

```js
let queue: Queue<number> = new Queue();
```

### Tuple (video 4)

```js
let tuple: [number, number] = [0, 0]
```
### Type assertion (video 16)

```js
(varname as string).trim()
```