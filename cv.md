###[rsschool-cv]()

---
###Giorgi Mamulashvili

---

### Contact information:

* Phone: +995 111 223344
* E-mail: giorgi.mamulashvili2003@gmail.com
* [Linkdin](https://www.linkedin.com/in/giorgi-mamulashvili-b8688a235/)

--- 

### About Myself:

I want to learn more about Front-End development and I have high expectetions RSSchool courses

---

### Skills and Proficiency:

* HTML5,CSS3
* Javascript Basics
* Python Basics
* VS Code, WebStorm, Pycharm

---
### Code Example:
Create a simple multiplication table asking the user the number of rows and columns he wants.
```javascript 
var rows = prompt("How many rows for your multiplication table?");
    var cols = prompt("How many columns for your multiplication table?");
    if(rows == "" || rows == null)
   		 rows = 10;
    if(cols== "" || cols== null)
   		 cols = 10;
    createTable(rows, cols);
    function createTable(rows, cols)
    {
      var j=1;
      var output = "<table border='1' width='500' cellspacing='0'cellpadding='5'>";
      for(i=1;i<=rows;i++)
      {
    	output = output + "<tr>";
        while(j<=cols)
        {
  		  output = output + "<td>" + i*j + "</td>";
   		  j = j+1;
   		}
   		 output = output + "</tr>";
   		 j = 1;
    }
    output = output + "</table>";
    document.write(output);
    }
```

### Education and courses:
1. FreeCodeCamp Javascript Basic https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/
2. Business and Technology University - Programing faculty

---

### Work experience:
Nothing yet...

---

### Languages:
* Georgian - Nativ
* English - Intermediate
* Russian - Basic
