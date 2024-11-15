<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>forms</title>
</head>
<body>
    <form action="">
        <label for="un">User Name:</label>
        <input type="text" id="un" name="rani" placeholder="User Name" required> <br><br>
    <label for="em">Email:</label>
    <input type="email" name="em" id="em" placeholder="Email"> <br><br>
    <label for="pwd">password:</label>
    <input type="password" name="pwd" id="pwd"  placeholder="password" pattern="[A-Za-z]{5,}"> <br><br> 
        <label for="cpass">confirm password</label>
        <input type="password" id="cpass">
    <label for="">Phone No:</label>
    <input type="text" name="number" id="" placeholder="Phone No" pattern="[0-9]{10}"> <br><br>
    <button type="submit">submit:</button>
    </form>
</body>
</html>
