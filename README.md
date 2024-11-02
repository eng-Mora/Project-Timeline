<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Education Platform Project Timeline</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }

        h2 {
            text-align: center;
            color: #6a1b9a;
            margin: 20px 0;
        }

        .table-container {
            display: flex;
            justify-content: center;
            padding: 20px;
            max-width: 100%;
        }

        table {
            width: 90%;
            border-collapse: collapse;
            max-width: 1200px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
            margin: 20px auto;
        }

        thead {
            background-color: #6a1b9a;
            color: white;
        }

        th, td {
            padding: 10px;
            border: 1px solid #ddd;
            text-align: left;
        }

        tbody tr:nth-child(even) {
            background-color: #f4f4f9;
        }

        tbody tr:hover {
            background-color: #e1bee7;
            cursor: pointer;
        }

        .task-category {
            font-weight: bold;
            color: #6a1b9a;
        }
    </style>
</head>
<body>

<h2>Project Timeline for Education Platform</h2>
<div class="table-container">
    <table>
        <thead>
            <tr>
                <th>ID</th>
                <th>Task Name</th>
                <th>Duration</th>
                <th>Start</th>
                <th>Finish</th>
                <th>Predecessors</th>
                <th>Resource Names</th>
            </tr>
        </thead>
        <tbody>
            <!-- HTML/CSS Structure and Design -->
            <tr>
                <td>1</td>
                <td class="task-category">HTML/CSS Structure and Design</td>
                <td colspan="5"></td>
            </tr>
            <tr>
                <td>1.1</td>
                <td>Create Basic HTML Structure</td>
                <td>2 days</td>
                <td>Mon 2/4/13</td>
                <td>Tue 2/5/13</td>
                <td></td>
                <td>Jason</td>
            </tr>
                        <tr>
                <td>1.2</td>
                <td>Design Header with Logo and Theme Toggle</td>
                <td>1 day</td>
                <td>Wed 2/6/13</td>
                <td>Wed 2/6/13</td>
                <td>1.1</td>
                <td>Carly</td>
            </tr>
            <tr>
                <td>1.3</td>
                <td>Build Video List Layout with Flexbox</td>
                <td>3 days</td>
                <td>Thu 2/7/13</td>
                <td>Mon 2/11/13</td>
                <td>1.2</td>
                <td>Maria</td>
            </tr>
            <tr>
                <td>1.4</td>
                <td>Style Video Items with Hover Effects</td>
                <td>1 day</td>
                <td>Tue 2/12/13</td>
                <td>Tue 2/12/13</td>
                <td>1.3</td>
                <td>Jason</td>
            </tr>
            <tr>
                <td>1.5</td>
                <td>Design Cart and Payment Modals</td>
                <td>2 days</td>
                <td>Wed 2/13/13</td>
                <td>Thu 2/14/13</td>
                <td>1.4</td>
                <td>Carly</td>
            </tr>
            <tr>
                <td>1.6</td>
                <td>Implement Light/Dark Theme Switcher</td>
                <td>1 day</td>
                <td>Fri 2/15/13</td>
                <td>Fri 2/15/13</td>
                <td>1.5</td>
                <td>Maria</td>
                </tr>

            <tr>
    <td>2</td>
    <td class="task-category">JavaScript Functionality</td>
    <td colspan="5"></td>
</tr>
<tr> <!-- Missing <tr> tag added here -->
    <td>2.1</td>
    <td>Render Video Items Dynamically</td>
    <td>3 days</td>
    <td>Mon 2/18/13</td>
    <td>Wed 2/20/13</td>
    <td></td>
    <td>Jason</td>
</tr>
<tr> <!-- Missing <tr> tag added here -->
    <td>2.2</td>
    <td>Add Video to Cart Functionality</td>
    <td>2 days</td>
    <td>Thu 2/21/13</td>
    <td>Fri 2/22/13</td>
    <td>2.1</td>
    <td>Carly</td>
</tr>
<tr> <!-- Missing <tr> tag added here -->
    <td>2.3</td>
    <td>Display Cart Items in Modal</td>
    <td>1 day</td>
    <td>Mon 2/25/13</td>
    <td>Mon 2/25/13</td>
    <td>2.2</td>
    <td>Maria</td>
</tr>
            <tr>
                <td>3</td>
                <td class="task-category">User Interface Enhancements</td>
                <td colspan="5"></td>
            </tr>
            <tr>
                <td>3.1</td>
                <td>Implement Hover and Transition Effects</td>
                <td>1 day</td>
                <td>Thu 2/28/13</td>
                <td>Thu 2/28/13</td>
                <td></td>
                <td>Maria</td>
            </tr>
            <tr>
                <td>3.2</td>
                <td>Add Confirmation Messages for Cart Actions</td>
                <td>1 day</td>
                <td>Fri 3/1/13</td>
                <td>Fri 3/1/13</td>
                <td>3.1</td>
                <td>Jason</td>
            </tr>
            <tr>
                <td>3.3</td>
                <td>Display Video Player Upon Successful Payment</td>
                <td>2 days</td>
                <td>Mon 3/4/13</td>
                <td>Tue 3/5/13</td>
                <td>3.2</td>
                <td>Carly</td>
            </tr>
            <tr>
                <td>3.4</td>
                <td>Implement Form Validation for Payment Fields</td>
                <td>2 days</td>
                <td>Wed 3/6/13</td>
                <td>Thu 3/7/13</td>
                <td>3.3</td>
                <td>Maria</td>
            </tr>
            <tr>
                <td>3.5</td>
                <td>Style Alerts for Error Messages</td>
                <td>1 day</td>
                <td>Fri 3/8/13</td>
                <td>Fri 3/8/13</td>
                <td>3.4</td>
                <td>Jason</td>
            </tr>

            <!-- Optional Enhancements -->
            <tr>
                <td>4</td>
                <td class="task-category">Optional Enhancements</td>
                <td colspan="5"></td>
            </tr>
            <tr>
                <td>4.1</td>
                <td>Add Responsive Design for Mobile Views</td>
                <td>3 days</td>
                <td>Mon 3/11/13</td>
                <td>Wed 3/13/13</td>
                <td></td>
                <td>Carly</td>
            </tr>
            <tr>
                <td>4.2</td>
                <td>Improve Accessibility (ARIA attributes)</td>
                <td>2 days</td>
                <td>Thu 3/14/13</td>
                <td>Fri 3/15/13</td>
                <td>4.1</td>
                <td>Maria</td>
            </tr>
            <tr>
                <td>4.3</td>
                <td>Implement Save Cart to Local Storage</td>
                <td>2 days</td>
                <td>Mon 3/18/13</td>
                <td>Tue 3/19/13</td>
                <td>4.2</td>
                <td>Jason</td>
            </tr>
            <tr>
                <td>4.4</td>
                <td>Add Email Contact Form Integration</td>
                <td>2 days</td>
                <td>Wed 3/20/13</td>
                <td>Thu 3/21/13</td>
                <td>4.3</td>
                <td>Carly</td>
            </tr>
        </tbody>
    </table>
</div>

