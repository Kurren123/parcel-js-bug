# Parcel JS Bug

Repro steps:

1. Clone
2. `npm install`
3. `parcel index.html` should work
4. `parcel folder1/index.html` won't work. Error message:

```
D:\dev\parcel-test\folder1\node_modules\xhook\dist\xhook.js: ENOENT: no such file or directory, open 'D:\dev\parcel-test\folder1\node_modules\xhook\dist\xhook.js'
```