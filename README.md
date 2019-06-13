# Bootstrap 4 contao component

If you have problems with symlinking the twbs/bootstrap dependency, simply add the following `post-update-cmd` to your project `composer.json`.

```
"scripts": {
    "post-update-cmd": [
        "ln -snf ../vendor/twbs/bootstrap/ assets/bootstrap"
    ]
}
```


