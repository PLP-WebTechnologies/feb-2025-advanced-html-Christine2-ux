<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My first Website</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List</h2>
    <ol type="I">
        <li>Boat Racing</li>
        <li>Horse Riding</li>
        <li>Zip lining</li>
        <li>Swimming</li>
        <li>Sky W</li>
    </ol>

    <!-- External Image -->
    <h2>Image from Pexels</h2>
    <img src="ziplining.jpg" alt="Zip Lining Adventure" width="600">">

    <!-- Contact Table -->
    <h2>Contact List</h2>
    <table>
        <tr>
            <th>Name</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>Christine Kabuga</td>
            <td>+254717065853</td>
            <td>kabugachristine4@gmail.com</td>
        </tr>
        <tr>
            <td>Steve Mwangi</td>
            <td>+245769092662</td>
            <td>kabugasteve02@gmail.com</td>
        </tr>
        <tr>
            <td>Brian Muturi</td>
            <td>+254795215071</td>
            <td>brianmuturi@gmail.com</td>
        </tr>
        <tr>
            <td>Jane Wanjiku</td>
            <td>+254724937085</td>
            <td>janewanjiku@gmail.com</td>
        </tr>
        <tr>
            <td>Benard Kabuga</td>
            <td>+254790150711</td>
            <td>benardkabuga@gmail.com</td>
        </tr>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="post">
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Christine Kabuga" required>
        <br><br>

        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email" placeholder="kabugachristine4@gmail.com" required>
        <br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Password" required minlength="6">
        <br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>

        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label>
        <br><br>

        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select a country</option>
            <option value="Kenya">Kenya</option>
            <option value="Uganda">Uganda</option>
            <option value="Tanzania">Tanzania</option>
            <option value="Australia">Australia</option>
        </select>
        <br><br>

        <label>Interests:</label>
        <input type="checkbox" id="sports" name="interests" value="Sports">
        <label for="sports">Sports</label>
        <input type="checkbox" id="music" name="interests" value="Music">
        <label for="music">Music</label>
        <input type="checkbox" id="travel" name="interests" value="Travel">
        <label for="travel">Travel</label>
        <br><br>

        <input type="submit" value="Register">
    </form>
</body>
</html>

