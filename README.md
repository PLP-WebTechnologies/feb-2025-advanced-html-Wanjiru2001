<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Advanced HTML5 Elements and Forms</title>
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>Welcome to My HTML5 Page</h1>
  </header>

  <!-- Ordered List with Roman Numerals -->
  <section>
    <h2>My Favorite Activities</h2>
    <ol type="I">
      <li>Reading</li>
      <li>Traveling</li>
      <li>Photography</li>
      <li>Cooking</li>
    </ol>
  </section>

  <!-- External Image from Pexels -->
  <section>
    <h2>Beautiful View</h2>
    <img src="https://images.pexels.com/photos/417173/pexels-photo-417173.jpeg" alt="Beautiful landscape" width="600">
  </section>

  <!-- Table of Contacts -->
  <section>
    <h2>Contact List</h2>
    <table border="1" cellpadding="8">
      <thead>
        <tr>
          <th>Name</th>
          <th>Address</th>
          <th>Mobile</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>John Doe</td>
          <td>123 Main St</td>
          <td>0712345678</td>
          <td>john@example.com</td>
        </tr>
        <tr>
          <td>Jane Smith</td>
          <td>456 Park Ave</td>
          <td>0723456789</td>
          <td>jane@example.com</td>
        </tr>
        <tr>
          <td>Mike Johnson</td>
          <td>789 Ocean Rd</td>
          <td>0734567890</td>
          <td>mike@example.com</td>
        </tr>
        <tr>
          <td>Alice Brown</td>
          <td>321 Hill St</td>
          <td>0745678901</td>
          <td>alice@example.com</td>
        </tr>
        <tr>
          <td>Emily White</td>
          <td>654 River Rd</td>
          <td>0756789012</td>
          <td>emily@example.com</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Registration Form -->
  <section>
    <h2>Registration Form</h2>
    <form action="#" method="POST">
      <!-- Name -->
      <label for="name">Full Name:</label><br>
      <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

      <!-- Email -->
      <label for="email">Email Address:</label><br>
      <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

      <!-- Password -->
      <label for="password">Password:</label><br>
      <input type="password" id="password" name="password" placeholder="Enter password" minlength="6" required><br><br>

      <!-- Date -->
      <label for="dob">Date of Birth:</label><br>
      <input type="date" id="dob" name="dob" required><br><br>

      <!-- Dropdown -->
      <label for="course">Choose a course:</label><br>
      <select id="course" name="course" required>
        <option value="">--Select a course--</option>
        <option value="web">Web Development</option>
        <option value="design">Graphic Design</option>
        <option value="data">Data Science</option>
      </select><br><br>

      <!-- Radio Buttons -->
      <p>Gender:</p>
      <input type="radio" id="male" name="gender" value="male" required>
      <label for="male">Male</label><br>
      <input type="radio" id="female" name="gender" value="female">
      <label for="female">Female</label><br><br>

      <!-- Checkboxes -->
      <p>Hobbies:</p>
      <input type="checkbox" id="reading" name="hobbies" value="reading">
      <label for="reading">Reading</label><br>
      <input type="checkbox" id="traveling" name="hobbies" value="traveling">
      <label for="traveling">Traveling</label><br>
      <input type="checkbox" id="music" name="hobbies" value="music">
      <label for="music">Music</label><br><br>

      <!-- Submit Button -->
      <button type="submit">Register</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 My HTML5 Project</p>
  </footer>

</body>
</html>
