# EXPERIMENT 04: CREATE A WEBLAYOUT USING GRIDBOX
## AIM:
To create a weblayout using gridbox.
## ALGORITHM:
1. Set up the container to display as a grid with three columns and four rows.
2. Define the styles for the header, sidebar, main content, and footer divisions, including their grid placement, background colors, padding, and text styles.
3. Create a header division that spans all three columns.
4. Create a sidebar division that occupies the first column and second to fourth rows.
5. Create a main content division that spans the second and third columns and is placed in the second row. Lastly, create a footer division that spans all three columns.
## PROGRAM:
### Gridbox.html
```
<!DOCTYPE html>
<html>
<head>
  <style>
    
    body {
      margin: 0;
      padding: 0;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      grid-template-rows: auto 1fr auto;
      min-height: 100vh;
    }

    
    .header {
      grid-column: 1 / 4;
      background-color:lightgreen;
      padding: 20px;
      color:black;
      text-align: center;
    }

    .sidebar {
      grid-column: 1 / 2;
      grid-row: 2 / 4;
      background-color:lightcoral;
      padding: 20px;
      
    }

    .main-content {
      grid-column: 2 / 4;
      grid-row: 2 / 3;
      background-color:turquoise;
      padding: 20px;
      color: #000;
    }

    .footer {
      grid-column: 1 / 4;
      background-color: black;
      padding: 20px;
      color: #FFF;
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">Header</div>
    <div class="sidebar">Sidebar</div>
    <div class="main-content">Main Content</div>
    <div class="footer">Footer</div>
  </div>
</body>
</html>

```
## OUTPUT:
![image](https://github.com/Rithigasri/ModernWeb-EXP4/assets/93427256/ea3271a0-5766-429a-8b4a-324cdcb0d855)
## RESULT:
Thus, a weblayout is created using gridbox.
