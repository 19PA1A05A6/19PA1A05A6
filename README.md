<!DOCTYPE html>
<html>

<head>

    <h1>HTML FORM</h1>
    <form action=submit.html>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width">
</head>

<body>
    <label for="fname">First Name</label><br>
    <input type="text" required><br><br>
    <label for="lname">Last Name</label><br>
    <input type="text" required><br><br>
    <label for="gender">Gender  </label>
    <input type="radio" name="gender" checked><label for="male">Male</label>
    <input type="radio" name="gender"><label for="female">Female</label>
    <input type="radio" name="gender"><label for="other">Other</label><br><br>
    <label for="Qualification">Highest Qualification</label>
    <select name="Qualification">
                <option value="1">SSC</option>
                <option value="2">Inter</option>
                <option value="3">B.Tech</option>
                <option value="4">M.Tech</option>
                <option value="5">Ph.D</option>
            </select><br><br><br>
    <label for="email">E-mail  </label>
    <input type="email" required><br><br>
    <label for="phonenumber">Phone Number  </label>
    <input type="tel" pattern="[0-9]{10}" required><br><br>
    <label for="address">Address</label><br>
    <textarea name="address" cols="40" rows="2"></textarea><br><br>
    <button type="submit">Submit</button>
    <button type="reset">Reset</button>
    </form>
</body>

</html>
