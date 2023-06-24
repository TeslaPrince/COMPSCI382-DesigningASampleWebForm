# COMPSCI382-DesigningASampleWebForm
Prompt Given: 
The following HTML code helps you understand how to include input text elements, drop-down menus, checkboxes, radio buttons, and table structure in an HTML document. 

Save the following HTML code as an html file with .html extension.
```
<!doctype html>
<html lang="en">
<head>
 <meta charset="utf-8">
 <!-- Set the viewport so this responsive site displays correctly on mobile devices -->
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <title>Basic Shopping Cart </title>
</head>
<body class='container'>
<h3>UW-Whitewater </h3>
 <!-- include a form -->
 <form >
    <table>
    <thead>
        <tr>
            <th colspan="2">Student Registration Form</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Name: </td>
            <td><input type='text' name='fullname'
                placeholder='Enter full name' />
            </td>
        </tr>
        <tr>
            <td>Status: </td>
            <td><!-- include a group of radio buttons -->
                <input type='radio' name='status' value='fr'>First year student
                <input type='radio' name='status' value='sp'>Sophomore
                <input type='radio' name='status' value='jr'>Junior
                <input type='radio' name='status' value='sn'>Senior
            </td>
        </tr>
        <tr>
            <td>Available hours</td>
            <td><!-- include a checkbox -->
                <input type='checkbox' name='h1' value='1' /> 8:00 - 10:00am <br/>
                <input type='checkbox' name='h2' value='2' /> 10:00am - noon <br/>
                <input type='checkbox' name='h3' value='3' /> after 6:00pm
            </td>
        </tr>

        <tr>
            <td>Major:</td>
            <td><!-- include a drop-down menu -->
                <select name='major' >
                <option value='1'>Computer Science</option>
                <option value='2'>MAGD</option>
                <option value='3'>Math</option>
                <option value='4'>Econ</option>
                <option value='5'>Other</option>
                </select>
            </td>
        </tr>
        <tr>
            <td>Comments: </td>
            <td>
                <textarea name='comments' cols="50" rows="6"></textarea>
            </td>
        </tr>
    </tbody>
  </table>
  <p><button type='submit' >Send Data</button></p>

 </form>
</body>
</html>
```
