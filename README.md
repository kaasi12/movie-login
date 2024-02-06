# movie-login
pract login mve
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cinema Scope</title>
    <style>
        body {
            background-image:url(Movies\ BG.jpeg);
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            background-attachment: fixed;

        }
        table{
            border-style: hidden;
            backdrop-filter: blur(10px);    
        }
        

        .links{
            font-size: 20px;
            color: rgb(247, 203, 8);
        }
        
        .header img{
            float: none;
            width: 400px;
            height: 100px;

        }

        p{
            color: white;
            font-size: 25px;
        }

        #login{
            border-style: solid;
            border-color: grey;
            padding: 5%;
            height: 350px;
            width: 350px;
            border: grey;
            backdrop-filter: blur(10px);
            font-size: 100%;
            margin: auto;
            border-radius: 15%;
        }

    </style>
</head>
<body> 
    <div class="header">
        <img src="CinemaScope_logo.svg" alt="logo"/>
    </div>

    <table border="10">
        <tr>
            <th width="120"><a href="Home.html" class="links">Home</a></th>
            <th width="120"><a href="Movie News.html" class="links">Movie News</a></th>
            <th width="120"><a href="Trailers.html" class="links">Trailers</a></th>
            <th width="120"><a href="Sign-up.html" class="links">Sign-up</a></th>
            <th width="120"><a href="Login.html" class="links">Login</a></th>
        </tr>
    </table>
    <hr>
    <div id="login">
    <p> Email: <input type="email" name="email" value=""></p>
    <p> Password: <input type="password" name="password" value=""></p>
    <input type="reset">
    <input type="submit">
    </div>
</body>
</html>
