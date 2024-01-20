This is a minimal example on how `await Meteor.userAsync()` throws an error inside a publication, as soon as `matb33:collection-hooks` is added to the project.

If you start the app via `meteor run`, an error is thrown as soon as you call the publication by opening the app in a browser.

Try

```
meteor remove matb33:collection-hooks
```

and then `meteor run`, and the exception is gone.