#Bootstrap 3 for IE7 (Alpha)

As you know Bootstrap 3 drops support for Internet Explorer 7, so i decide to write specific CSS make Boostrap 3 supported on IE7.

This support will be using separate conditional file CSS.

#How to include conditional CSS file?

```html
<!--[if lt IE 8]>
    <link href="/css/bootstrap3-ie7.css" rel="stylesheet">
<![endif]-->
```

### Requirements
- Bootstrap 3 uses the box-sizing property for layouts which is not natively supported by IE7. The polyfill 'boxsizing.htc' is required: https://github.com/Schepp/box-sizing-polyfill

### Known Issues
Will be added soon.

### FAQS
Will be added soon.

