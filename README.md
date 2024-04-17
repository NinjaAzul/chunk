# chunk

```js

function paginate(array, page_size, page_number) {
  // human-readable page numbers usually start with 1, so we reduce 1 in the first argument
  return array.slice((page_number - 1) * page_size, page_number * page_size);
}

```
```js
const quotaIdChunks: number[][] = []
      const quotaIdsCopy = [...quotaIds]
      while (quotaIdsCopy.length)
        quotaIdChunks.push(quotaIdsCopy.splice(0, 2000))

        ```
