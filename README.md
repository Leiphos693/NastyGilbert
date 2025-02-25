i dont know what does this do
 <!DOCTYPE html>

<html>
<head>
    <title>NGPage2</title>
</head>
<body >
    <h1 align = "CENTER">This is the 2<sup>nd</sup> page</h1>
    <hr Width = "7368329">
    <p>now please fill up the form</p>
    <h3><b>Personal information</b></h3>
    <form action="action.php" method="POST">
        
        <div>
            <label for="fname">First Name:</label>
            <input type="text" id="fname" name="fname" placeholder="Leitanthem" required>
        </div>
        <br>
        <div>
            <label for="lname">Last Name:</label>
            <input type="text" id="lname" name="lname" placeholder="Leiphaba">
        </div>
        <br>
        <div>
            <label for="pass">Password:</label>
            <input type="password" id="pass" name="pass" maxlength="12" required>
        </div>
        <br>
        <div>
            <label for="email">email:</label>
            <input type="email" id="email" name="email" placeholder="abcd@gmail.com">
        </div>
        <br>
        <div>
            <label for="phone">phone No.:</label>
            <input type="tel" id="phone" name="phone" placeholder="7802683649">
        </div>
        <br>
        <div>
            <label for="bdate">Birthdate:</label>
            <input type="date" id="bdate" name="bdate">
        </div>
        <br>
        <div>
            <label for="quantity">Quantity:</label>
            <input type="number" id="quantity" name="quantity" min="0" max="100">
        </div>
        <br>
        <div>
            <label for="title">title:</label>

            <label for="st">Stand</label>
            <input type="radio" id="st" name="Jojo" value="St">

            <label for="Hm">Hamon</label>
            <input type="radio" id="Hm" name="Jojo" value="Hm">

            <label for="Req">Both</label>
            <input type="radio" id="Req" name="Jojo" value="Req">
        </div>
        <br>
        <div>
            <label for="payment">Payment:</label>
            <select id="payment" name="payment">
                <option value="Credit">Credit</option>
                <option value="Visa">Visa</option>
                <option value="UPI">UPI</option>
            </select>
        </div>
        <br>
        <div>
            <label for="Good">Good:</label>
            <input type="checkbox" id="Good" name="Good">

            <label for="doom">Bad-ass:</label>
            <input type="checkbox" id="doom" name="doom">
        </div>
        <br>
            <input type="reset">
            <input type="submit">
        


    </form>
    
    
</body>


</html>
