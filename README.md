<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Free Roof Giveaway Entry</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      padding: 30px;
      color: #333;
    }
    form {
      max-width: 600px;
      margin: 0 auto;
      background: #fff;
      padding: 25px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
      border-top: 5px solid #1F4E79;
    }
    label {
      display: block;
      margin: 15px 0 5px;
      font-weight: bold;
    }
    input[type="text"],
    input[type="email"],
    select,
    textarea {
      width: 100%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 14px;
    }
    textarea {
      resize: vertical;
      height: 100px;
    }
    .checkboxes {
      margin-top: 20px;
    }
    .checkboxes label {
      display: flex;
      align-items: center;
      font-weight: normal;
    }
    .checkboxes input {
      margin-right: 10px;
    }
    button {
      margin-top: 20px;
      background-color: #1F4E79;
      color: white;
      border: none;
      padding: 12px 20px;
      font-size: 16px;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover {
      background-color: #163b5c;
    }
  </style>
</head>
<body>

<form action="https://formspree.io/f/mqaqojlr" method="POST">
  <h2 style="color:#1F4E79;">Free Roof Giveaway Entry</h2>

  <!-- Redirect to a thank-you page after submission -->
  <input type="hidden" name="_redirect" value="https://example.com/thank-you">

  <label for="firstName">First Name *</label>
  <input type="text" id="firstName" name="First Name" required>

  <label for="lastName">Last Name *</label>
  <input type="text" id="lastName" name="Last Name" required>

  <label for="email">Email *</label>
  <input type="email" id="email" name="Email" required>

  <label for="phone">Contact Number *</label>
  <input type="text" id="phone" name="Contact Number" required>

  <label for="address">Address *</label>
  <input type="text" id="address" name="Address" required>

  <label for="hearAbout">How did you hear about us?</label>
  <select id="hearAbout" name="Heard From">
    <option value="Facebook">Facebook</option>
    <option value="Church">Church</option>
    <option value="Friend">Friend</option>
    <option value="Other">Other</option>
  </select>

  <label for="story">Tell Us Your Story And How This Roof Could Make A Difference</label>
  <textarea id="story" name="Your Story"></textarea>

  <div class="checkboxes">
    <label><input type="checkbox" name="Media Consent"> If chosen, I agree to let Elliott Roofing film the project.</label>
    <label><input type="checkbox" name="Contact Consent" required> I grant Elliott Roofing permission to reach out to me. *</label>
  </div>

  <button type="submit">Submit Entry</button>
</form>

</body>
</html>
