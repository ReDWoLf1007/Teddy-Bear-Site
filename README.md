# Teddy-Bear-Site
I started lwarning HTML and got me to make this trial project.
It contains numerous things such as-
01. It contains the headings with different size and mark.
02. It contains Tabular form of Teddy's description, I added some unusual descriptions that are kinda funny to me at the time.
03. It contains Tables and Lists that contains details of teddy and more.
04. It contains some pictures one of which is Teddy's and the others are to make the site FULL. I'll be adding CSS for it later.
05. It contains a form that you can fill and submit, it will not save the details though as I have not connected it to the backend.
06. It will contain some more details as I add them moving forward that I will mention them as they get added.
-I know it's child's play compare to everything in this platform, but I am very proud of my accomplishments and just wanted to show them.

-->Here's the head and body of the HTML language I used and its contents-

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="This is the description">
    <meta name="keywords" content="html, html contents, html tutorials">
    <meta name="robots" content="INDEX, FOLLOW">

    <title>Teddy's Biography</title>

    <!-- This is how you link CSS -->
    <link rel="stylesheet" href="learning.css">
    <!-- This is how you link javascript -->
    <link rel="stylesheet" href="learning.js">

    <style>
        h2 {
            background-color: gray;
        }
        
        #H{
            background-color: yellow;
            color: black;
        }
        #para{
            background-color: aquamarine;
        }
        #t{
            background-color: bisque;
        }
        #t1{
            background-color: lightgoldenrodyellow;
        }
        #t2{
            background-color: bisque;
        }
        #t3{
            background-color: aquamarine;
        }
    </style>

</head>

<body>
    <!-- Heading -->
    <h1 id="H">Teddy's Website</h1>
    <p id="para">Lorem ipsum, dolor sit amet consectetur adipisicing elit. <strong>Bold Letters</strong> Dolor ipsum fuga
        repellendus, atque voluptatibus eveniet quo dolorum architecto aperiam libero quidem tempora? <em>This is
            emphesized</em> Possimus, ipsam nulla similique <em><strong>DAMNN!!</strong></em> assumenda laudantium eos
        atque <STRONG><EM>WOW!!!</EM></STRONG> nisi nihil nam numquam tenetur facilis quas quis blanditiis aliquam?</p>

        <!-- LInks -->
    <a href="https://google.com" target="_blank">Go to Google </a> <br>
    <a href="https://facebook.com" target="_blank"> Go to Facebook </a> <br>
    <a href="https://instagram.com" target="_blank"> Go to Instagram </a> <br>
    <a href="https://twitter.com" target="_blank"> Go to Twitter </a> <br>

<!-- Lists -->
    <ul id="t">
        <li>This Teddy bear is Healthy</li>
        <li>This Teddy bear is Happy</li>
        <li>This Teddy bear is Funny</li>
        <li>This Teddy bear is Evil</li>
    </ul>
    <ul id="t1">
        <li>This Teddy Bear is </li>
    </ul>
    <ol id="t2">
        <li>PURE EVIL</li>
        <li>Piece of SHIT</li>
        <li>SON OF A BITCH!!</li>
        <li>LOVE!♥ :)</li>
    </ol>

    <!-- Tables -->
    <table id="t3">
        <thead>
            <tr>
                <td>Username </td>
                <td> Age </td>
                <td> Opinion on Teddy </td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Sagar Tiwari</td>
                <td>20</td>
                <td>LOVE</td>
            </tr>
            <tr>
                <td>Vipin Kumar</td>
                <td>20</td>
                <td>HATE</td>
            </tr>
            <tr>
                <td>Vee</td>
                <td>19</td>
                <td>HATE</td>
            </tr>
        </tbody>
    </table>
    <br>
    <span>
        <strong>
            <h2>Fill This Form!</h2>
        </strong>
    </span>

    <form action="backend.php">
        <br>
        <div>
            Name: <input type="text" name="myName">                 
        </div>  
        <br>                                
        <div>
            Role: <input type="text" name="myRole">
        </div> 
        <br>
        <div>
            Email: <input type="text" name="myEmail">
        </div>
        <br>
        <div>
             Date: <input type="date" name="myDate">
        </div>
        <br>
        <div>
             How much you HATE Teddy?(1 to 100): <input type="number" name="myNumber">
        </div>     
        <br>
        <div>
             Teddy is:   CUTE <input type="radio" name="myRadio" >
                    Adorable! <input type="radio" name="myRadio">
                    Fucking Asshole! <input type="radio" name="myRadio">
                    All of the Above ♥ <input type="radio" name="myRadio">
        </div>
        <br>
        <div>
            <label for="Feeling">Feeling</label>
            <select name="Myfeeling" id="Feeling">
                <option value="LOVE">LOVE</option>
                <option value="HATE">HATE</option>
                <option value="TOXIC">TOXIC(LOVE/HATE)</option>

            </select>
        </div>
        <br>
        <div>Search Engine</div> <input type="Search" > 
        <br>
        <span id="d">
            Describe Teddy: <br>
            <textarea name="text" cols="50" rows="30"></textarea> <img src="Kira.jpg" alt="OOPS">
        </span>
        <br>
        <div>
            <input type="Submit" value="Submit Now">
            <input type="Reset" value="Reset Now">
        </div>
        <br>
        
                
</body>

</html>
