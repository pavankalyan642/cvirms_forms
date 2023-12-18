<!DOCTYPE html>   
<html>   
<head>  
    <meta name="viewport" content="width=device-width, initial-scale=1">  
    <title>Login Page</title>  
    <style>   
        body {  
            font-family: Calibri, Helvetica, sans-serif;  
            background-color: pink;  
            text-align: center; /* Center the content */
        }  
        button {   
            background-color: #4CAF50;   
            width: 100%;  
            color: orange;   
            padding: 15px;   
            margin: 10px 0px;   
            border: none;   
            cursor: pointer;   
        }   
        form {   
            border: 3px solid #f1f1f1;   
            width: 300px; /* Adjust the width as needed */
            margin: 0 auto; /* Center the form */
            background-color: lightblue; /* Background color for the form */
            padding: 20px;
            box-sizing: border-box; /* Include padding and border in the width */
        }   
        input[type=text], input[type=password] {   
            width: 100%;   
            margin: 8px 0;  
            padding: 12px 20px;   
            display: inline-block;   
            border: 2px solid green;   
            box-sizing: border-box;   
        }  
        button:hover {   
            opacity: 0.7;   
        }   
        .cancelbtn {   
            width: auto;   
            padding: 10px 18px;  
            margin: 10px 5px;  
        }   
        .container {   
            text-align: left; /* Align text to the left */
        }   
    </style>   
</head>    
<body>    
    <h1>Welcome to CVIRMS</h1>
    <form>  
        <div class="container">   
            <label>Username:</label>   
            <input type="text" placeholder="Enter Username" name="username" required>  
            <label>Password:</label>   
            <input type="password" placeholder="Enter Password" name="password" required>  
            <button type="submit">Login</button>   
            <input type="checkbox" checked="checked"> Remember me   
            <button type="button" class="cancelbtn">Cancel</button>   
            <br>
            <a href="#">Forgot password?</a>   
        </div>   
    </form>     
</body>     
</html>
