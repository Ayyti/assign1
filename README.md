# assign1
#Generic Web-page html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styleee.css">
</head>
<body>
 <header>
    <div class="navbar">
       <div class="home">
        <a href="#">  HOME</a>
       </div>
       <div class="product">
       
        <div class="dropdown">
            <a href="#">PRODUCT &#9662;</a>
            <div class="dropdown-content">
                <a href="#">product 1</a>
                <a href="#">product 2</a>
                <a href="#">product 3</a>
            </div>
        </div>
    
        </div>
        <div class ="ABOUT">
            <a href="#"> ABOUT </a>
        </div>
           
        <div id="login">
            <button class="login-button"><a href="#login">LOGIN</a></button>
            <div class="login-dropdown">
                <form>
                    <label for="username">Username:</label>
                    <input type="text" id="username" name="username" required><br>
                    <label for="password">Password:</label>
                    <input type="password" id="password" name="password" required><br>
                    <button ><a href="#create">create</a></button> 
                    <input type="submit" value="sign in">
                </form>
            </div>
       
        </div>   
        <div id ="create">     

                
                    <div class="login-dropdown">
                <form>
                    <h1>Registration Page</h1>
                    <label for="Username">First Name:</label>
                    <input type="text" id="username" name="firstname" required><br>
                    <label for="lastname">Last Name:</label>
                    <input type="text" id="username" name="lastname" required><br>
                    <div>
                        Email: <input type="email" name="email">
                    </div>
                    <div>
                        <label for="password">Password:</label>
                    <input type="password" id="password" name="password" required><br>
                    </div>
                    <label for="password">Confirm Password:</label>
                    <input type="password" id="password" name="password" required><br>

                </form>
            </div>
               
    </div>
</div>
 </header>

</body>
</html>


