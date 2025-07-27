<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>First Experiment - FSD</title>
    <style>
        label {
            font-size: 22px;
        }   
        h1 {
            font-size: 28px;
        }
        input[type="submit"] {
            padding: 8px 16px;
            font-size: 16px;
            border: 1px solid #888;
            border-radius: 5px;
            background-color: #d3d3d3;;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #f0f0f0;
 }
    </style>
</head>
<body>
    <form>
        <h1>Student Registration Form</h1>

        <label for="name">Name: </label><br>
        <input type="text" name="name" placeholder="Enter your full name" required><br><br>

        <label for="email">Email: </label><br>
        <input type="email" name="email" placeholder="Enter your email" required><br><br>

        <label for="age">Age: </label><br>
        <input type="number" name="age" placeholder="Enter your age" required><br><br>

        <input type="submit" value="Register">
    </form>
</body>
</html>
