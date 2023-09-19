<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Customer Information Upload</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }

        h1 {
            text-align: center;
            color: #333;
        }

        form {
            max-width: 400px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        label {
            display: block;
            margin-bottom: 10px;
            color: #555;
        }

        input[type="file"] {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
        }

        input[type="submit"] {
            width: 100%;
            padding: 10px;
            background-color: #007BFF;
            color: #fff;
            border: none;
            cursor: pointer;
        }

        input[type="submit"]:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>Upload Customer Information</h1>
    <form action="upload.php" method="post" enctype="multipart/form-data">
        <label for="customerFile">Select a File:</label>
        <input type="file" name="customerFile" id="customerFile" accept=".csv, .xlsx, .json"><!-- Adjust the 'accept' attribute to specify allowed file types -->
        <br>
        <input type="submit" value="Upload">
    </form>
</body>
</html>
