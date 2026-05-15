<h1 align="center">📅 Calendar Day Finder 2026</h1>

<p align="center">
  A Python-based calendar project that calculates the weekday for any date in the year <b>2026</b>
  without using built-in calendar libraries such as <code>datetime</code> or <code>calendar</code>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Project-Beginner%20Friendly-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/OOP-Python-orange?style=for-the-badge">
</p>

---

<h2>📖 About The Project</h2>

<p>
This project was created to practice Python programming fundamentals and logical problem solving.
The main objective is to determine the correct day name (Monday, Tuesday, etc.)
for any valid date in the year <b>2026</b> using custom logic instead of advanced Python libraries.
</p>

<p>
The project demonstrates:
</p>

<ul>
  <li>Object-Oriented Programming (OOP)</li>
  <li>Dictionary usage</li>
  <li>Looping concepts</li>
  <li>Modulo arithmetic</li>
  <li>Input validation</li>
  <li>Exception handling</li>
  <li>Real-world logic building</li>
</ul>

---

<h2>🗂️ Repository Structure</h2>

<pre>
calendar-day-finder-2026/
│
├── calendar2026.py
└── README.md
</pre>

---

<h2>⚙️ How the Program Works</h2>

<h3>Step 1️⃣ : User Input</h3>

<p>
The user enters:
</p>

<ul>
  <li>Month Number (1–12)</li>
  <li>Date Number</li>
</ul>

<pre><code>
Enter Month Number (1-12): 5
Enter Date: 14
</code></pre>

---

<h3>Step 2️⃣ : Store Month Data</h3>

<p>
The program stores the number of days in each month using a Python dictionary.
</p>

<pre><code>
self.month_days = {
    1: 31,
    2: 28,
    3: 31,
    4: 30,
    ...
}
</code></pre>

---

<h3>Step 3️⃣ : Validate Input</h3>

<p>
The program checks:
</p>

<ul>
  <li>Whether the month exists</li>
  <li>Whether the entered date is valid for that month</li>
</ul>

<p>
Example:
</p>

<pre><code>
Month = 15 ❌ Invalid
Date = 40 in April ❌ Invalid
</code></pre>

---

<h3>Step 4️⃣ : Calculate Total Days</h3>

<p>
The program calculates the total number of days from January 1st, 2026
up to the entered date.
</p>

<p><b>Example:</b> 14 May 2026</p>

<pre><code>
January  = 31
February = 28
March    = 31
April    = 30
May      = 14
----------------
Total    = 134
</code></pre>

---

<h3>Step 5️⃣ : Find Weekday Using Modulo</h3>

<p>
The project uses modulo arithmetic:
</p>

<pre><code>
(total_days - 1) % 7
</code></pre>

<p>
Since a week contains 7 days, the remainder determines the weekday index.
</p>

<p>
The year 2026 starts on:
</p>

<pre><code>
1 January 2026 = Thursday
</code></pre>

<p>
So the weekday list becomes:
</p>

<pre><code>
["Thursday","Friday","Saturday",
 "Sunday","Monday","Tuesday","Wednesday"]
</code></pre>

---

<h2>🧠 Algorithm</h2>

<pre><code>
1. Take month and date input
2. Validate month
3. Validate date
4. Add days from previous months
5. Add current date
6. Apply modulo (% 7)
7. Find weekday index
8. Print day name
</code></pre>

---

<h2>💻 Example Output</h2>

<pre><code>
Enter Month Number (1-12): 8
Enter Date: 15

15 / 8 / 2026 is Saturday
</code></pre>

---

<h2>❌ Invalid Input Example</h2>

<pre><code>
Enter Month Number (1-12): 13

Invalid Month
</code></pre>

---

<h2>🛡️ Exception Handling</h2>

<p>
The project includes exception handling using:
</p>

<pre><code>
try:
except:
</code></pre>

<p>
This prevents the program from crashing when invalid input is entered.
</p>

---

<h2>📊 Time Complexity</h2>

<table>
  <tr>
    <th>Operation</th>
    <th>Complexity</th>
  </tr>
  <tr>
    <td>Month Traversal</td>
    <td>O(12)</td>
  </tr>
  <tr>
    <td>Overall Program</td>
    <td>O(1)</td>
  </tr>
</table>

<p>
The program is very efficient because the number of months is fixed.
</p>

---

<h2>🚀 Features</h2>

<ul>
  <li>✅ Finds weekday names for 2026 dates</li>
  <li>✅ Pure Python logic</li>
  <li>✅ No external libraries</li>
  <li>✅ Beginner-friendly structure</li>
  <li>✅ OOP implementation</li>
  <li>✅ Error handling</li>
  <li>✅ Real-world logic building</li>
</ul>

---

<h2>📚 Concepts Practiced</h2>

<ul>
  <li>Python Classes & Objects</li>
  <li>Dictionaries</li>
  <li>Loops</li>
  <li>Conditional Statements</li>
  <li>Modulo Arithmetic</li>
  <li>Exception Handling</li>
  <li>Logic Building</li>
</ul>

---

<h2>🔮 Future Improvements</h2>

<ul>
  <li>Support all years</li>
  <li>Add leap year calculation</li>
  <li>Create graphical user interface (GUI)</li>
  <li>Build web version using Flask or Django</li>
  <li>Add automatic calendar generation</li>
  <li>Export results to file</li>
</ul>

---

<h2>👨‍💻 Author</h2>
<p>
Developed by <b>JANARDHAN M</b>
</p>

<p>
Created while learning Python programming and problem-solving.
</p>

<p>
This project reflects hands-on practice with logical thinking and Python fundamentals.
</p>

---

<h2>⭐ Support</h2>

<p>
If you found this project useful or interesting,
consider giving this repository a ⭐ on GitHub.
</p>
