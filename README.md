## Steps to reproduce:

```
npm i
npm t
```

## Sample warning output:

```
(node:29756) V8: C:\Users\chris\Downloads\react-pdf-linking-failure\node_modules\@react-pdf\yoga\src\build\Release\nbind.js:1781 Linking failure in asm.js: Unexpected stdlib member
    at C:\Users\chris\Downloads\react-pdf-linking-failure\node_modules\@react-pdf\yoga\src\build\Release\nbind.js:9750:4
    at Object.<anonymous> (C:\Users\chris\Downloads\react-pdf-linking-failure\node_modules\@react-pdf\yoga\src\dist\entry-browser.js:21:1)
    at Runtime._execModule (C:\Users\chris\Downloads\react-pdf-linking-failure\node_modules\jest-runtime\build\index.js:1646:24)
    at Runtime._loadModule (C:\Users\chris\Downloads\react-pdf-linking-failure\node_modules\jest-runtime\build\index.js:1185:12)
    at Runtime.requireModule (C:\Users\chris\Downloads\react-pdf-linking-failure\node_modules\jest-runtime\build\index.js:1009:12)
    at Runtime.requireModuleOrMock (C:\Users\chris\Downloads\react-pdf-linking-failure\node_modules\jest-runtime\build\index.js:1210:21)
    at Object.<anonymous> (C:\Users\chris\Downloads\react-pdf-linking-failure\node_modules\@react-pdf\layout\lib\node\getPadding.js:8:36)
    at Runtime._execModule (C:\Users\chris\Downloads\react-pdf-linking-failure\node_modules\jest-runtime\build\index.js:1646:24)
    at Runtime._loadModule (C:\Users\chris\Downloads\react-pdf-linking-failure\node_modules\jest-runtime\build\index.js:1185:12)
    at Runtime.requireModule (C:\Users\chris\Downloads\react-pdf-linking-failure\node_modules\jest-runtime\build\index.js:1009:12)
```
