Reference 69

## You load the following page:

```
<!DOCTYPE html>
<html>
<head>
      <title>Intro to JavaScript</title>
           <meta charset="utf-8" />
</head>
<body>
      <script>
           var functionKeys = ["F1", "F2", "F5", "F3", "F7", "F6", "F9", "F8"];
           var result = ' ';

           function func1(key) {
                switch (key) {
                     case "F1":
                          result += "F1";
                     case "F2":
                          result += "F2";
                     case "F3":
                          result += "F3";
                     case "F4":
                          result += "F4";
                     case "F5":
                          result += "F5";
                }
           }

           functionKeys.forEach(function (k) { func1(k) });
           console.log(result);
      </script>
</body>
</html>

```
What will result contain?

 a
 ```
F1F2F3F5F2F3F5F5F3F5
```
 b
 ```
F1F2F3F4F5F2F3F4F5F5F3F4F5
```
 c
 ```
F1F2F3F5
```
 d
 ```
F1F2F5F3
```
