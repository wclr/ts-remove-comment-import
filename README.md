```
// install desp
yarn 

// compile
yarn tsc 
```

Se out dir `file-with-removed.js` - with comment removed. Other files with comment present.

There are also problems with config `removeComments: true` and `/*! @some-comment */`, they too are removed in some cases.