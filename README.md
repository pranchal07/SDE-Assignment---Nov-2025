# Merge Discontinuous Time Ranges

### Problem
Given an array of time ranges in the form `[start, end)`, merge:
- Overlapping ranges
- Touching ranges
- Ranges separated by small gaps (≤ threshold)

Output must be:
- Sorted
- Non-overlapping
- Minimal number of ranges

---

### Usage

1. Create a JavaScript file (e.g., `index.js`) and require the module:

```js
const { mergeTimeRanges } = require('./my-module');

const ranges = [
  [1000, 2000],
  [2500, 4000],
  [3900, 4100],
  [8000, 9000],
  [9050, 9500]
];

const threshold = 200;

console.log(mergeTimeRanges(ranges, threshold));
