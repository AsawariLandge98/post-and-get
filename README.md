# post-and-get
miislanios fil create two another file of frontend and backend this is the front file code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form method="get" action="http://localhost:8080/register">
        <input placeholder="enter username" name="user" type="text">
        <input placeholder="enter Password" name="password" type="password">
<button>submit</button>
<hr>

<form method="post" action="http://localhost:8080/register">
    <input placeholder="enter username" name="user" type="text">
    <input placeholder="enter Password" name="password" type="password">
<button>submit</button>

    </form>
</body>
</html>
