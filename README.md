# IEalert
if IE version < 9 , send a warning to advise the user changing or updating the browser.

## Usage
* include:
    * iealert   (directory)
    * iealert.js (js file)

    into your workspace

* add the code blocks before the ```</head>``` tag like this:
```html
    <!--[if lt IE 9]>
    <script src="iealert.js" type="text/javascript"></script>
    <script type="text/javascript">
        DomReady.ready(iealert);
    </script>
    <![endif]-->
</head>
```

## Result
* if your browser is IE and the version < 9, you will see: 
![image](https://raw.githubusercontent.com/cc93/IEalert/master/ieAlertResult.png)