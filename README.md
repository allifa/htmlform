<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>What is your favorite prog language?</title>
    <link rel="stylesheet" type="text/css" href="layout.css">
</head>
<body>
    form>
        <fieldset>
            <legend>add user</legend>
    
    <div>
        <label for="first name">First Name</label> <br>
        <input type="text" id="firstname" name="last_name">
    </div>
    <div>
        <label for="last name">Last Name </label><br>
        <input type="text" id="lastname" name="last_name">

    </div>
    <div>
        <label for="email">Email</label><br>
        <input type="email" id="emailid" name="email_id">
    </div>
    <div>
        <label for="status"></label><br>
        <select id="role" name="user_role_name">
            <option value="student"> student </option>
            <option value="teacher">teacher</option>
            <option value="guest">guest</option>
        </select>


        <label for="date"></label> <br>
        <select id="date" name="dates">
        <input type="date" id="date" name="date_to">
    </select>
    </div>
    <div>
        <P>choose your favorite web language</P>
        <input type="radio" id="html" name="html_option " value="HTML">
        <label for="html">HTML</label> <br>
        <input type="radio" id="css" name=" css_option" value="CSS">
        <label for="css">CSS</label><br>
        <input type="radio" id="js" name="js_option" value="JS">
        <label for="js">JS</label><br>
        </div>
<div>
    <p>
        comments:
    </p>
    <textarea name="COMMENTS" id="explain" cols="30" rows="10" placeholder="add a comment"></textarea>
</div>
<div>
   <input type="checkbox" id="signup" name="sign_up" value="sign up for email">
   <label for="Sign up for email">Sign up for email</label> <br>
   <input type="checkbox" id="agree" name="sign_up" value="agree to terms">
   <label for="agree to terms">agree to terms</label> <br>
</div>
<div>
    <input type="button" id="submit" name="submi_form" value="submit">
</div>
</fieldset>

</form>



</body>
</html>
