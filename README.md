<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>School Attendance Management System</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f4f6f9;
}

header{
    background:#1e3a8a;
    color:white;
    padding:20px;
    text-align:center;
}

.container{
    width:95%;
    margin:auto;
    padding:20px;
}

.dashboard{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
    margin-bottom:30px;
}

.card{
    background:white;
    padding:20px;
    border-radius:10px;
    box-shadow:0 2px 10px rgba(0,0,0,0.1);
    text-align:center;
}

.card h2{
    color:#1e3a8a;
}

.section{
    background:white;
    padding:20px;
    margin-bottom:25px;
    border-radius:10px;
    box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

h3{
    margin-bottom:15px;
    color:#1e3a8a;
}

table{
    width:100%;
    border-collapse:collapse;
}

table th, table td{
    border:1px solid #ddd;
    padding:12px;
    text-align:center;
}

table th{
    background:#1e3a8a;
    color:white;
}

.present{
    color:green;
    font-weight:bold;
}

.absent{
    color:red;
    font-weight:bold;
}

ul{
    list-style:none;
}

ul li{
    padding:10px;
    border-bottom:1px solid #ddd;
}

footer{
    text-align:center;
    background:#1e3a8a;
    color:white;
    padding:15px;
    margin-top:20px;
}
</style>
</head>

<body>

<header>
    <h1>School Attendance & Administration System</h1>
    <p>Manage Students, Teachers, Staff, Events and Holidays</p>
</header>

<div class="container">

    <!-- Dashboard -->
    <div class="dashboard">
        <div class="card">
            <h2>850</h2>
            <p>Total Students</p>
        </div>

        <div class="card">
            <h2>45</h2>
            <p>Total Teachers</p>
        </div>

        <div class="card">
            <h2>18</h2>
            <p>Admin Staff</p>
        </div>

        <div class="card">
            <h2>92%</h2>
            <p>Today's Attendance</p>
        </div>
    </div>

    <!-- Student Attendance -->
    <div class="section">
        <h3>Student Attendance Register</h3>

        <table>
            <tr>
                <th>Roll No</th>
                <th>Student Name</th>
                <th>Class</th>
                <th>Status</th>
            </tr>

            <tr>
                <td>101</td>
                <td>Rahul Sharma</td>
                <td>10-A</td>
                <td class="present">Present</td>
            </tr>

            <tr>
                <td>102</td>
                <td>Priya Patel</td>
                <td>10-A</td>
                <td class="absent">Absent</td>
            </tr>

            <tr>
                <td>103</td>
                <td>Amit Verma</td>
                <td>10-B</td>
                <td class="present">Present</td>
            </tr>
        </table>
    </div>

    <!-- Teacher Attendance -->
    <div class="section">
        <h3>Teacher Attendance Register</h3>

        <table>
            <tr>
                <th>Teacher ID</th>
                <th>Name</th>
                <th>Department</th>
                <th>Status</th>
            </tr>

            <tr>
                <td>T001</td>
                <td>Mrs. Mehta</td>
                <td>Mathematics</td>
                <td class="present">Present</td>
            </tr>

            <tr>
                <td>T002</td>
                <td>Mr. Kumar</td>
                <td>Science</td>
                <td class="present">Present</td>
            </tr>

            <tr>
                <td>T003</td>
                <td>Mrs. Shah</td>
                <td>English</td>
                <td class="absent">Absent</td>
            </tr>
        </table>
    </div>

    <!-- Administration Staff -->
    <div class="section">
        <h3>Administration Staff Records</h3>

        <table>
            <tr>
                <th>Employee ID</th>
                <th>Name</th>
                <th>Designation</th>
                <th>Status</th>
            </tr>

            <tr>
                <td>A001</td>
                <td>Rakesh Singh</td>
                <td>Principal</td>
                <td class="present">Present</td>
            </tr>

            <tr>
                <td>A002</td>
                <td>Neha Joshi</td>
                <td>Accountant</td>
                <td class="present">Present</td>
            </tr>

            <tr>
                <td>A003</td>
                <td>Vikas Rao</td>
                <td>Clerk</td>
                <td class="absent">Absent</td>
            </tr>
        </table>
    </div>

    <!-- Events -->
    <div class="section">
        <h3>Upcoming Events</h3>

        <ul>
            <li>📅 Annual Sports Day - 15 August 2026</li>
            <li>📅 Science Exhibition - 25 August 2026</li>
            <li>📅 Teacher's Day Celebration - 5 September 2026</li>
            <li>📅 Cultural Festival - 20 September 2026</li>
        </ul>
    </div>

    <!-- Holidays -->
    <div class="section">
        <h3>Upcoming Holidays</h3>

        <ul>
            <li>🎉 Independence Day - 15 August</li>
            <li>🎉 Ganesh Chaturthi - 27 August</li>
            <li>🎉 Gandhi Jayanti - 2 October</li>
            <li>🎉 Diwali Vacation - October/November</li>
        </ul>
    </div>

</div>

<footer>
    <p>© 2026 School Attendance & Administration Management System</p>
</footer>

</body>
</html>
