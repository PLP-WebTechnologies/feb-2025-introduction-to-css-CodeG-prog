# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
#The following is the HTML page
<!DOCTYPE html>
<html lang="eng">
    <head>
        <title>
            <strong>Advanced HTML5 Elements and Forms</strong>
        </title>
        <link rel ="stylesheet" href ="mystyle.css">
    </head>

    <body>
<h1>Important Tips for Html</h1>
<hr>
<pre>HTML is the Standard markup langauge for creators. Below are various elements that make up the language</pre>

<ol type="i" align= "center">
<li>Head</li>
<li>Title</li>
<li>Body</li>
<li>Sections</li>
<li> Paragraphs</li>

</ol>
<h2>HTML Images</h2>
<pre>Images are key in web development. Lets check out the image below</pre>
<img src="https://images.pexels.com/photos/577585/pexels-photo-577585.jpeg?auto=compress&cs=tinysrgb&w=600"  width="400" height="300" alt="A Coding Computer Interface">

<h2>Tables in HTML</h2>
<p>Tables in HTML can be used to visually represent data in an attractive manner</p>
<br><br>
<table border="1">
    <thead>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tbody>
            <tr>
                <td>Axray</td>
                <td>Bungoma County</td>
                <td>0706126243</td>
                <td>wekesaaugutine@gmail.com</td>
            </tr>
            <tr>
                <td>Roy</td>
                <td>Kitale</td>
                <td>0715641169</td>
                <td>roykoome@gmail.com</td>
            </tr>
            <tr>
                <td>Delvin</td>
                <td>Busia</td>
                <td>0745768906</td>
                <td>delvinwaino@gmail.com</td>

            </tr>
            <tr>
                <td>Richman</td>
                <td>Webuye</td>
                <td>070000000</td>
                <td>richmanshenz@gmail.com</td>
        </tr>
            <td>Paulman</td>
            <td>Kimilili</td>
            <td>0778923456</td>
            <td>susankavehi@gmail.com</td>
        </tr>
        </tbody>
    </thead>
</table>
    <br><br>
    <h2>Registration forms in HTML</h2>
    <p>Registration forms helps to collect and dislay data about various components</p>
    <br><br>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <label for="Email">Email Address:</label>
        <input type="email" id="email address" name="email address">
        <label for="password">Password:</label>
        <input type="password" id="password" name="password">
        <label for="date">Date:</label>
        <input type="date" id="date" name="date">
        <label for="time">Time:</label>
        <input type="time" id="time" name="time">

    </form>
<br><br>
<h2> Select county of Origin</h2>
<br><br>
    <select type="County" name="County">
        <option value="Bungoma">Bungoma</option>
        <option value="Kiambu">Kiambu</option
        <option value="Tranzoia">Tranzoia</option>
        <option value="Vihiga"></option>
        <option value="Kajiado">Kajiado</option>
    </select>
    <br><br>

<label for="Hobbies">Hobbies:</label>
<input type="checkbox"  name="Hobbies" value="Sports">Sports
<input type="checkbox" name="Hobbies" value="Reading">Reading
<input type="checkbox" name="Hobbies" value="Travelling">Travelling
<input type="checkbox" name="Hobbies" value="Swimming">Swimming
<input type="checkbox" name="Hobbies" value="Cooking">Cooking
<br><br>


<label for="country">Country</label>
<select>
    <option value="Kenya">Kenya</option>
    <option value="Uganda">Uganda</option>
    <option value="Tanzania">Tanzania</option>
    <option value="Rwanda">Rwanda</option>
    <br><br>
</select>
<button type="Submit">Submit</button>
<label 

<label for="comments">Comments</label>
<textarea name="Comments" rows="5" cols="60" placeholder="Write here your comments"></textarea>
<button type="Submit">Submit</button>

<footer>
<p>All Rights Reserved by wekesaaugutine@2025</p>


</footer>

    </body>

    #The following is the CSS Design for my HTML Page

    /* Reset and base styles */
* {
    margin: 0;
    padding: 20px;
    box-sizing: content-box;
    font-family: 'Segoe UI', sans-serif;
}

body {
    background-color: #d4c8c8;
    color: #333;
    line-height: 1.6;
    padding: 20px;
}

/* ID Selector - Main heading */
#main-heading {
    color: #ccd0d3;
    text-align: center;
    margin-bottom: 20px;
    font-family: 'Georgia', serif;
    text-transform: uppercase;
    letter-spacing: 1px;
}

/* Class Selector - Container */
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

/* Element Selector - Images */
img {
    display: block;
    margin: 20px auto;
    border: 3px solid #3498db;
    border-radius: 5px;
    box-shadow: 0 4px 8px rgba(220, 144, 144, 0.2);
    transition: transform 0.3s ease;
}

img:hover {
    transform: scale(1.02);
}

/* Table Styles */
table {
    width: 100%;
    border-radius: 0%;
    border-collapse: collapse;
    margin: 25px 0;
}

th, td {
    padding: 12px 15px;
    text-align: left;
    border-bottom: 1px solid #ddd;
}

th {
    background-color: #3498db;
    color: white;
}

tr:hover {
    background-color: #f5f5f5;
}

/* Form Styles */
form {
    background-color: #f9f9f9;
    padding: 25px;
    border-radius: 5px;
    margin: 30px 0;
    border: 1px solid #ddd;
}

label {
    display: block;
    margin-bottom: 8px;
    font-weight: bold;
    color: #4a90d6;
}

input[type="text"],
input[type="email"],
input[type="password"],
input[type="date"],
input[type="time"],
select,
textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ddd;
    border-radius: 4px;
    font-size: 16px;
    color-scheme: dark;
}

input[type="checkbox"] {
    margin-right: 10px;
}

button[type="submit"] {
    background-color: #db3434;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 16px;
    transition: background-color 0.3s;
}

button[type="submit"]:hover {
    background-color: #2980b9;
}

/* Footer Styles */
footer {
    text-align: center;
    margin-top: 40px;
    padding: 20px;
    background-color: #c3448a;
    color: white;
    border-radius: 5px;
}

/* Special class for ordered list */
.roman-list {
    list-style-type: upper-roman;
    padding-left: 20px;
    font-family: 'Courier New', Courier, monospace;
    background-color: #f0f8ff;
    padding: 15px;
    border-left: 4px solid #3498db;
    margin: 15px 0;
}
