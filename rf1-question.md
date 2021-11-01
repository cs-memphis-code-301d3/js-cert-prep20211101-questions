Reference: 59

You load the following script in the browser:
```
      <script>
          let beeCount = 400;
          let course = {
               name: 'intro to programming',
               id: 1012,
               description: 'this course introduces students to programming',
               students: [
                    student1 = {
                         name: 'James',
                         credits: 5
                    },
                    student2 = {
                         name: 'Bryan',
                         credits: 3
                    }
               ]
          };
 
          var func1 = function (a) {
               a = 456;
          }
 
          var func2 = function (item) {
               if (!item) return;
               item.name = 'JavaScript programming';
               item.id = 1015;
          }
 
          function callThem() {
               console.log(beeCount);
               func1(beeCount);
               console.log(beeCount);
 
               console.log(`Name: ${course.name}, id: ${course.id}`);
               func2(course);
               console.log(`Name: ${course.name}, id: ${course.id}`);
          }
 
          callThem();
     </script>
```
     
What will be displayed in the console?

a
```
456
456
Name: intro to programming, id: 1012
Name: JavaScript programming, id: 1015
```
 b
 ```
400
456
Name: intro to programming, id: 1012
Name: JavaScript programming, id: 1015
```
 c
 ```
400
400
Name: intro to programming, id: 1012
Name: JavaScript programming, id: 1015
```
 d
 ```
400
400
Name: intro to programming, id: 1012
Name: intro to programming, id: 101
```

