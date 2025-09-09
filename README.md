# Registration-form-


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>User Registration Form document 
  </title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f6f9;
      margin: 0;
      padding: 20px;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #333;
    }

    form {
      max-width: 700px;
      margin: auto;
      background: #fff;
      padding: 20px 30px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    fieldset {
      border: 1px solid #ccc;
      border-radius: 8px;
      margin-bottom: 20px;
      padding: 15px;
    }

    legend {
      font-weight: bold;
      color: #444;
      padding: 0 8px;
    }

    label {
      display: block;
      margin-bottom: 10px;
      color: #333;
    }

    input, select, textarea {
      width: 100%;
      padding: 8px;
      margin-top: 4px;
      border: 1px solid #ccc;
      border-radius: 5px;
      box-sizing: border-box;
    }

    input[type="radio"], 
    input[type="checkbox"] {
      width: auto;
      margin-right: 6px;
    }

    input[type="color"], 
    input[type="range"],
    input[type="file"] {
      padding: 3px;
      width: auto;
    }

    textarea {
      resize: vertical;
    }

    .buttons {
      text-align: center;
    }

    button {
      padding: 10px 20px;
      margin: 10px 5px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 16px;
    }

    button[type="submit"] {
      background: #28a745;
      color: white;
    }

    button[type="reset"] {
      background: #dc3545;
      color: white;
    }

    button:hover {
      opacity: 0.9;
    }
  </style>
</head>
<body>
  <h2>User Registration Form</h2>

  <form action="#" method="post" enctype="multipart/form-data">
    <!-- Personal Information -->
    <fieldset>
      <legend>Personal Information</legend>
      <label>First Name: <input type="text" name="first_name" required></label>
      <label>Last Name: <input type="text" name="last_name" required></label>
      <label>Date of Birth: <input type="date" name="dob"></label>
      <label>Age: <input type="number" name="age" min="0"></label>
      
      Gender:  
      <label><input type="radio" name="gender" value="male"> Male</label>
      <label><input type="radio" name="gender" value="female"> Female</label>
      
      <label>Profile Photo: <input type="file" name="profile_photo"></label>
    </fieldset>

    <!-- Contact & Address Information -->
    <fieldset>
      <legend>Contact & Address Information</legend>
      <label>Email Address: <input type="email" name="email" required></label>
      <label>Phone Number: <input type="tel" name="phone"></label>
      <label>Personal Website: <input type="url" name="website" placeholder="https://example.com"></label>
      <label>Street Address: <input type="text" name="street"></label>
      <label>City: <input type="text" name="city"></label>
      
      <label>Country: 
        <select name="country">
          <option value="">Select Country</option>
          <option value="us">United States</option>
          <option value="uk">United Kingdom</option>
          <option value="ke">Kenya</option>
          <option value="in">India</option>
        </select>
      </label>
      
      <label>ZIP/Postal Code: <input type="text" name="zip"></label>
      <label>Preferred Contact Time: <input type="time" name="contact_time"></label>
    </fieldset>

    <!-- Preferences & Interests -->
    <fieldset>
      <legend>Preferences & Interests</legend>
      <label>Favorite Color: <input type="color" name="fav_color"></label>
      <label>Experience Level (1–10): <input type="range" name="experience" min="1" max="10"></label>
      <label>Birth Month: <input type="month" name="birth_month"></label>
      <label>Available Week: <input type="week" name="available_week"></label>
      <label>Search Keywords: <input type="search" name="keywords" placeholder="Enter keywords..."></label>
    </fieldset>

    <!-- Interests -->
    <fieldset>
      <legend>Interests (Select all that apply)</legend>
      <label><input type="checkbox" name="interests" value="technology"> Technology</label>
      <label><input type="checkbox" name="interests" value="sports"> Sports</label>
      <label><input type="checkbox" name="interests" value="music"> Music</label>
      <label><input type="checkbox" name="interests" value="travel"> Travel</label>
      <label><input type="checkbox" name="interests" value="reading"> Reading</label>
      <label><input type="checkbox" name="interests" value="cooking"> Cooking</label>
    </fieldset>

    <!-- Education & Password -->
    <fieldset>
      <legend>Education & Security</legend>
      <label>Education Level: 
        <select name="education">
          <option value="">Select Education Level</option>
          <option value="highschool">High School</option>
          <option value="bachelor">Bachelor's</option>
          <option value="master">Master's</option>
          <option value="phd">PhD</option>
        </select>
      </label>
      <label>Create Password: <input type="password" name="password" required></label>
      <label>Confirm Password: <input type="password" name="confirm_password" required></label>
    </fieldset>

    <!-- Feedback -->
    <fieldset>
      <legend>Feedback & Additional Information</legend>
      <label>Tell us about yourself:
        <textarea name="about" rows="4" placeholder="Write a brief description about yourself..."></textarea>
      </label>
      <label>Suggestions for improvement:
        <textarea name="suggestions" rows="4" placeholder="Any suggestions or feedback..."></textarea>
      </label>
    </fieldset>

    <!-- Buttons -->
    <div class="buttons">
      <button type="submit">Register</button>
      <button type="reset">Reset</button>
    </div>
  </form>
</body>
</html>
