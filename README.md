<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>User Registration Form</title>
</head>
<body>
  <h2>User Registration Form</h2>

  <form action="#" method="post" enctype="multipart/form-data">
    <!-- Personal Information -->
    <fieldset>
      <legend>Personal Information</legend>
      <label>First Name: <input type="text" name="first_name" required></label><br><br>
      <label>Last Name: <input type="text" name="last_name" required></label><br><br>
      <label>Date of Birth: <input type="date" name="dob"></label><br><br>
      <label>Age: <input type="number" name="age" min="0"></label><br><br>
      
      Gender:  
      <label><input type="radio" name="gender" value="male"> Male</label>
      <label><input type="radio" name="gender" value="female"> Female</label><br><br>
      
      <label>Profile Photo: <input type="file" name="profile_photo"></label>
    </fieldset>

    <!-- Contact & Address Information -->
    <fieldset>
      <legend>Contact & Address Information</legend>
      <label>Email Address: <input type="email" name="email" required></label><br><br>
      <label>Phone Number: <input type="tel" name="phone"></label><br><br>
      <label>Personal Website: <input type="url" name="website" placeholder="https://example.com"></label><br><br>
      <label>Street Address: <input type="text" name="street"></label><br><br>
      <label>City: <input type="text" name="city"></label><br><br>
      
      <label>Country: 
        <select name="country">
          <option value="">Select Country</option>
          <option value="us">United States</option>
          <option value="uk">United Kingdom</option>
          <option value="ke">Kenya</option>
          <option value="in">India</option>
          <!-- add more -->
        </select>
      </label><br><br>
      
      <label>ZIP/Postal Code: <input type="text" name="zip"></label><br><br>
      <label>Preferred Contact Time: <input type="time" name="contact_time"></label>
    </fieldset>

    <!-- Preferences & Interests -->
    <fieldset>
      <legend>Preferences & Interests</legend>
      <label>Favorite Color: <input type="color" name="fav_color"></label><br><br>
      <label>Experience Level (1–10): <input type="range" name="experience" min="1" max="10"></label><br><br>
      <label>Birth Month: <input type="month" name="birth_month"></label><br><br>
      <label>Available Week: <input type="week" name="available_week"></label><br><br>
      <label>Search Keywords: <input type="search" name="keywords" placeholder="Enter keywords..."></label>
    </fieldset>

    <!-- Interests -->
    <fieldset>
      <legend>Interests (Select all that apply)</legend>
      <label><input type="checkbox" name="interests" value="technology"> Technology</label><br>
      <label><input type="checkbox" name="interests" value="sports"> Sports</label><br>
      <label><input type="checkbox" name="interests" value="music"> Music</label><br>
      <label><input type="checkbox" name="interests" value="travel"> Travel</label><br>
      <label><input type="checkbox" name="interests" value="reading"> Reading</label><br>
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
      </label><br><br>
      <label>Create Password: <input type="password" name="password" required></label><br><br>
      <label>Confirm Password: <input type="password" name="confirm_password" required></label>
    </fieldset>

    <!-- Feedback -->
    <fieldset>
      <legend>Feedback & Additional Information</legend>
      <label>Tell us about yourself:<br>
        <textarea name="about" rows="4" cols="40" placeholder="Write a brief description about yourself..."></textarea>
      </label><br><br>
      <label>Suggestions for improvement:<br>
        <textarea name="suggestions" rows="4" cols="40" placeholder="Any suggestions or feedback..."></textarea>
      </label>
    </fieldset>

    <br>
    <button type="submit">Register</button>
    <button type="reset">Reset</button>
  </form>
</body>
</html>
