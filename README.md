<h1 align="center">📅 Calendar Day Finder 2026</h1>

<p align="center">
  A beginner-friendly Python project that finds the day name for any date in the year <b>2026</b> 
  without using advanced libraries like <code>datetime</code> or <code>calendar</code>.
</p>

---

<h2>🚀 Project Overview</h2>

<p>
This project calculates the weekday (Monday, Tuesday, etc.) using pure Python logic.
The user enters:
</p>

<ul>
  <li>Month Number</li>
  <li>Date</li>
</ul>

<p>
The program then calculates the correct day name manually using:
</p>

<ul>
  <li>Dictionaries</li>
  <li>Loops</li>
  <li>Modulo Logic</li>
  <li>Object-Oriented Programming (OOP)</li>
  <li>Exception Handling</li>
</ul>

---

<h2>📂 Repository Structure</h2>

<pre>
calendar-day-finder-2026/
│
├── calendar2026.py
└── README.md
</pre>

---

<h2>🧠 Core Logic</h2>

<h3>1️⃣ Store Month Information</h3>

<p>
A dictionary stores the number of days in each month.
</p>

<pre><code>
self.month_days = {
    1: 31,
    2: 28,
    3: 31,
    ...
}
</code></pre>

---

<h3>2️⃣ Calculate Total Days</h3>

<p>
The program adds:
</p>

<ul>
  <li>Days from previous months</li>
  <li>Current entered date</li>
</ul>

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

<h3>3️⃣ Find the Day Name</h3>

<p>
The project uses modulo operation:
</p>

<pre><code>
(total_days - 1) % 7
</code></pre>

<p>
Because a week contains 7 days, the remainder gives the correct weekday index.
</p>

---

<h2>⚙️ Features</h2>

<ul>
  <li>✅ Finds day names for 2026 dates</li>
  <li>✅ No external libraries used</li>
  <li>✅ Input validation</li>
  <li>✅ Exception handling</li>
  <li>✅ Beginner-friendly logic</li>
  <li>✅ OOP-based structure</li>
</ul>

---

<h2>💻 Technologies Used</h2>

<p>
<img src="https://img.shields.io/badge/Python-Programming-blue?style=for-the-badge&logo=python">
</p>

---

<h2>📌 Example Output</h2>

<pre><code>
Enter Month Number (1-12): 1
Enter Date: 1

1 / 1 / 2026 is Thursday
</code></pre>

---

<h2>❌ Invalid Input Example</h2>

<pre><code>
Enter Month Number (1-12): 15

Invalid Month
</code></pre>

---

<h2>📖 What I Learned</h2>

<ul>
  <li>Python Classes & Objects</li>
  <li>Problem Solving Logic</li>
  <li>Date Calculation Concepts</li>
  <li>Exception Handling</li>
  <li>GitHub Project Structure</li>
</ul>

---

<h2>🔮 Future Improvements</h2>

<ul>
  <li>Support for all years</li>
  <li>Leap year handling</li>
  <li>GUI version</li>
  <li>Web application version</li>
  <li>Advanced calendar algorithms</li>
</ul>

---

<h2>👨‍💻 Author: JANARDHAN M</h2>

<p>
Created by an aspiring Data Scientist while learning Python and problem-solving.
</p>

<p>
⭐ If you like this project, consider giving it a star on GitHub!
</p>
