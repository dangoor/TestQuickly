A trivial Brackets extension that adds a shortcut Cmd/Ctrl-P
for running tests that are referred to by the current file.

To tell the extension which tests should be run, add a specially formatted comment to the file.
Here's an example from QuickOpen.js:

```javascript
/*unittests: QuickOpen */
```

This tells TestQuickly to run the suite called QuickOpen.