---
layout: page
title: Summary of Units
description: A blog for ideas for CompSci, etc.
permalink: /summary of units/

---


{% include nav/lessons.html %}

<style>
    body {
        font-family: 'Poppins', sans-serif;
        margin: 0;
        padding: 0;
        text-align: center;
        overflow: auto; /* Enable scrolling */
        background: linear-gradient(135deg, #00c6ff, #0072ff, #00bfff, #1e90ff);
        animation: gradient 15s ease infinite;
    }

    @keyframes gradient {
        0% { background: #00c6ff; }
        25% { background: #0072ff; }
        50% { background: #00bfff; }
        75% { background: #1e90ff; }
        100% { background: #00c6ff; }
    }

    table {
        width: 90%;
        margin: 30px auto;
        border-collapse: collapse;
        background-color: #ffffff;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        border-radius: 10px;
        overflow: hidden;
    }

    th, td {
        padding: 15px;
        border: 1px solid #ddd;
        text-align: left;
    }

    th {
        background-color: #0047ab;
        color: white;
        font-weight: bold;
    }

    td {
        background-color: #f2f2f2;
    }

    td:hover {
        background-color: #e6f7ff;
    }

    td a {
        color: #0047ab;
        text-decoration: none;
        font-weight: bold;
    }

    td a:hover {
        text-decoration: underline;
    }

    h2 {
        font-size: 2em;
        color: #333;
        margin-top: 20px;
    }

    ul {
        list-style-type: disc;
        margin-left: 20px;
    }

    li {
        margin-bottom: 5px;
    }
</style>

<h2>Part 1 - Fundamentals (Quick Review)</h2>

<table>
    <thead>
        <tr>
            <th>Unit</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="https://nighthawkcoders.github.io/portfolio_2025/csp/big-idea/p2/3-1">3.1 Variables</a></td>
            <td>
                <ul>
                    <li>Variables mainly are used to store data values and they can be accessed throughout the problems.</li>
                    <li>These variables also tend to change over time(say you want to change what you store in the variable).</li>
                    <li>variables cannot have a space in between them an example is my_name = Lalita as you can see there is an underscore in the variable to not have a space in the variable.</li>
                    <li>Operations combine two strings and Repetition repeats strings over and over again</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://nighthawkcoders.github.io/portfolio_2025/csp/big-idea/p2/3-2">3.2 Data Abstraction</a></td>
            <td>
                <ul>
                    <li>The concept of Data Abstractions is basically how our computer is able to handle data structures and the computer being able to simplfy the structures</li>
                    <li>Integers are numbers that are postive, negative, and are not irrational(ex.30)</li>
                    <li>Floats do have decimial points and can be irriational (ex. pi).</li>
                    <li>Strings are normally pieces of code that have quotation marks around them and represent textual data(ex. "Lalita").</li>
                    
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://nighthawkcoders.github.io/portfolio_2025/csp/big-idea/p2/3-3">3.3 Mathematical Expressions</a></td>
            <td>
                <ul>
                    <li>Operators include +, -, *, /, and % (modulus) for calculations.</li>
                    <li>Follows order of operations: parentheses, exponents, multiplication/division, addition/subtraction (PEMDAS).</li>
                    <li>Use math libraries for complex operations like square roots and trigonometry.</li>
                    <li>Modulus (%) returns the remainder of a division.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://nighthawkcoders.github.io/portfolio_2025/csp/big-idea/p2/3-4">3.4 Strings</a></td>
            <td>
                <ul>
                    <li>Concatenation: Joining strings together with a +</li>
                    <li>String Interpolation: Putting variables into the string</li>
                    <li>Substrings: Extracting a certain phrase of part of a string</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://nighthawkcoders.github.io/portfolio_2025/csp/big-idea/p2/3-5">3.5 Booleans</a></td>
            <td>
                <ul>
                    <li>Booleans represent True or False values.</li>
                    <li>Comparison operators: ==, !=, >, <, >=, <= compare values.</li>
                    <li>Boolean logic: AND, OR, NOT used for combining conditions.</li>
                    <li>Booleans are often used in conditionals to control program flow.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://nighthawkcoders.github.io/portfolio_2025/csp/big-idea/p2/3-6">3.6 Conditionals</a></td>
            <td>
                <ul>
                    <li>With If else statements check certain condition and decide exceution is best to go with for each scenario. (ex. I am 17 so the code might say if >16: print(drive) else: print(cannot drive) since I am older than 16 mine will print can drive)</li>
                    <li>Else-if chains are used to test multiple conditions.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://nighthawkcoders.github.io/portfolio_2025/csp/big-idea/p2/3-7">3.7 Nested Conditionals</a></td>
            <td>
                <ul>
                    <li>Nested conidtionals allow for more if else statements within the if else statement. They allow for elif statements or under the if statement there can be another if else statement</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://nighthawkcoders.github.io/portfolio_2025/csp/big-idea/p2/3-8">3.8 Iteration</a></td>
            <td>
                <ul>
                    <li>For Loops: Used when you know how many times the loop should run.</li>
                    <li>While Loops: Used when the loop should run until a condition becomes false.</li>
                    <li>Do-While Loops:  Runs at least once, then checks the condition.</li>
                    <li>Break and Continue: Controls the loop flow by either stopping the loop (break) or skipping to the next iteration.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://nighthawkcoders.github.io/portfolio_2025/csp/big-idea/p2/3-10">3.10 Lists</a></td>
            <td>
                <ul>
                    <li>List Operations: Understanding how to assign, insert, append, remove, and calculate the length of lists is crucial for data management in Python.</li>
                    <li>Pseudocode for Summing Even Numbers: Using loops and conditionals allows for systematic calculations</li>
                    <li>Functions for Max and Min: Functions encapsulate the logic for finding extremes in lists, showcasing the utility of iteration.</li>
                    <li>User Input and Element Exploration: Engaging users for data input and examining list properties enhances interactivity</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

<script src="https://utteranc.es/client.js"
        repo="lalita1809/lalita_2025"
        issue-term="title"
        label="utterances"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>