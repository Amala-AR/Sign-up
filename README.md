# Sign-up
Registration form
<!DOCTYPE html>
<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <title>Add User</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
</head>
<body class="col-md" style="background-color:black;font-family:'Lucida Sans', sans-serif; color:azure">
">
    <center><h3 style="margin-top:30px">Sign up</h3></center>
    <div class="container h-100">
        <div class="row h-100 justify-content-center align-items-center">
            <div class="col-10 col-md-8 col-lg-6">
                <form class="form-group">
                    <label style="margin-top:20px">Name</label>
                    <div class="row">
                        <div class="col ">
                            <input type="text" class="form-control" placeholder="First name" required>
                        </div>
                        <div class="col">
                            <input type="text" class="form-control" placeholder="Last name" required>
                        </div>
                    </div>
                    <label>Password</label>
                    <input type="password" class="form-control" id="formGroupExampleInput" placeholder="Password" required>
                    <label>Address</label>
                    <input type="text" class="form-control" id="formGroupExampleInput" placeholder="Door-no,street,.......">
                    <div class="row">
                        <div class="col">
                            <label>City</label>
                            <input type="text" class="form-control" id="formGroupExampleInput" placeholder="City Name">
                        </div>
                        <div class="col">
                            <label>Postal Code</label>
                            <input type="number" class="form-control" id="formGroupExampleInput" placeholder="Postal Code">
                        </div>
                    </div>
                    <label>State</label>
                    <input type="text" class="form-control" id="formGroupExampleInput" placeholder="State Name">
                    <label>Country</label>
                    <input type="text" class="form-control" id="formGroupExampleInput" placeholder="Country Name" required>
                    <br />
                    <center><a class="btn btn-primary" href="success.html" role="button">Submit</a></center>
                </form>
                </div>
            </div>
        </div>
</body>
</html>
