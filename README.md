# Web-Dev-Review

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>

    <header><h1>Contact Me Form</h1></header>

    <br>
    <hr>

    <form>
      <label>Name</label>
      <input type = "text" name ="name"></input>

      <br>
      <br>
      <hr>

      <label>Age</label>
      <input type = "number" name = "name"></input>

      <br>
      <br>
      <hr>

      <label>Grade</label>
      <input type = "number" name = "name"></input>

      <br>
      <br>
      <hr>


    <label>Gender</label>
    <select>
      <option>Male</option>
      <option>Female</option>
      <option>Other</option>
    </select>

    <br>
    <br>
    <hr>

    <label>Date of Submission</label>
    <input type = "date"; name = "date"> </input>

    <br>
    <br>
    <hr>

    <label>Email</label>
      <input type = "text" name = "name"></input>

    <br>
    <br>
    <hr>

    <label>Phone Number</label>
      <input type = "number" name = "name"></input>
    
    <br>
    <br>
    <hr>

    <label>Submit</label>
      <input type = "button"></input>
    </form>

    <table>
      <thead>
        <tr>
          <td>First Name</td>
          <td>Email</td>
          <td>Phone Number</td>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Chris</td>
          <td>@gmail</td>
          <td>858</td>
        </tr>
        <tr>
          <td>Chris</td>
          <td>@gmail</td>
          <td>858</td>
        </tr>
        <tr>
          <td>Chris</td>
          <td>@gmail</td>
          <td>858</td>
        </tr>
      </tbody>
    </table>

    </table>
    <script src="script.js"></script>
  </body>
</html>




label {
  font-family:Verdana, Geneva, Tahoma, sans-serif;
}

table {
  text-align: center;
}

* {
  background-color: antiquewhite;
}

body {
  color: black;
}

header {
  text-align: center;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-size: 25px;
  text-decoration: underline overline;
}
table, header {
  color: rgb(84, 0, 0);
}
