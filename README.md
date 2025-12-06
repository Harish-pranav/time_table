# Ex02 Time Table
# Date:06.12.2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
---
<html>

<head>
    <title>Colourful Timetable</title>

    <style>
        body {
            font-family: Arial, sans-serif; /* DEFAULT FONT */
            background: #f4f7fb;
            margin: 0;
            padding: 20px;
        }

        .logo-container {
            text-align: center;
            margin-bottom: 20px;
        }

        table {
            border-collapse: collapse;
            margin: auto;
            width: 95%;
        }

        caption {
            font-size: 22px;
            font-weight: bold;
            padding: 10px;
            color: white;
            background: linear-gradient(45deg, #4b6cb7, #182848);
            border-radius: 8px;
            margin-bottom: 8px;
        }

        th, td {
            padding: 14px;
            text-align: center;
            font-size: 16px;
        }

        th {
            font-weight: bold;
        }

        /* Time column */
        .time {
            background: #ffeb3b;
            font-weight: bold;
            width: 90px;
        }

        /* Colourful subjects */
        .sub1 { background: #ff9aa2; }
        .sub2 { background: #ffdac1; }
        .sub3 { background: #e2f0cb; }
        .sub4 { background: #b5ead7; }
        .sub5 { background: #c7ceea; }
        .sub6 { background: #f5b7b1; }
        .sub7 { background: #aed6f1; }

        .slotfree { background: #eeeeee; font-style: italic; }

        /* Subject list table */
        .sub-table {
            width: 50%;
            margin-top: 30px;
            background: white;
            border-radius: 10px;
            box-shadow: 0px 0px 10px #ccc;
        }

        .sub-table th {
            background: #d63031;
            color: white;
        }

        .sub-table td {
            background: #ffecec;
        }
    </style>

</head>

<body>

    <div class="logo-container">
        <img src="logo.png" height="150" width="700">
    </div>

    <table border="1">
        <caption>Slot Time Table - HARISH PRANAV (25008640)</caption>

        <tr style="background:#ff5252; color:white;">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>

        <!-- 8–10 -->
        <tr>
            <th class="time">8-10</th>
            <td class="sub1">public speaking</td>
            <td class="sub1">public speaking</td>
            <td class="slotfree">FREE SLOT</td>
            <td class="slotfree">FREE SLOT</td>
            <td class="sub1">public speaking</td>
            <td class="sub2">Python programming</td>
        </tr>

        <!-- 10–12 -->
        <tr>
            <th class="time">10-12</th>
            <td class="slotfree">FREE SLOT</td>
            <td class="sub2">Python programming</td>
            <td class="sub1">public speaking</td>
            <td class="slotfree">FREE SLOT</td>
            <td class="sub3">web application</td>
            <td class="slotfree">FREE SLOT</td>
        </tr>

        <!-- Lunch -->
        <tr>
            <th class="time">12-1</th>
            <td colspan="6" style="background:#fff59d; font-weight:bold;">LUNCH BREAK</td>
        </tr>

        <!-- 1–3 -->
        <tr>
            <th class="time">1-3</th>
            <td class="sub3">web application</td>
            <td class="slotfree">FREE SLOT</td>
            <td class="sub4">mentor meet</td>
            <td class="slotfree">FREE SLOT</td>
            <td class="slotfree">FREE SLOT</td>
            <td class="sub3">web application</td>
        </tr>

        <!-- 3–5 -->
        <tr>
            <th class="time">3-5</th>
            <td class="slotfree">FREE SLOT</td>
            <td class="sub2">Python programming</td>
            <td class="sub2">Python programming</td>
            <td class="sub2">Python programming</td>
            <td class="sub3">web application</td>
            <td class="sub3">web application</td>
        </tr>
    </table>

    <table class="sub-table" border="1" align="center">
        <tr>
            <th>S.NO</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>

        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>

        <tr>
            <td>2</td>
            <td>19AI301</td>
            <td>Python Programming (PYT)</td>
        </tr>

        <tr>
            <td>3</td>
            <td>19EN105</td>
            <td>Public Speaking (ENG)</td>
        </tr>
    </table>

</body>

</html>
---
# OUTPUT
<img width="1919" height="1079" alt="Screenshot 2025-12-06 213151" src="https://github.com/user-attachments/assets/e6f95414-8ad9-46f6-b469-a42830463688" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
