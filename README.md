<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Shree Lokpriya School - Admission Open for 2082">
  <title>Shree Lokpriya School | Admission</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #74ebd5, #acb6e5);
      color: #333;
      min-height: 100vh;
      margin: 0;
    }

    .container {
      margin-top: 50px;
      background: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    .form-header {
      text-align: center;
      margin-bottom: 30px;
    }

    .form-header h1 {
      color: #4b4cf6;
    }

    .form-header p {
      font-size: 1.1rem;
      color: #555;
    }

    footer {
      margin-top: 30px;
      text-align: center;
      font-size: 0.9rem;
      color: #fff;
    }

    .login-section {
      margin-top: 50px;
      text-align: center;
    }

    .login-section button {
      margin-top: 10px;
    }
  </style>
</head>

<body>
  <!-- Admission Form Section -->
  <div class="container">
    <div class="form-header">
      <h1>Shree Lokpriya School</h1>
      <h3>Admission Open - 2082</h3>
      <p>We are here to support students to fill their detail information for school management system</p>
    </div>

    <form action="process_form.php" method="post" enctype="multipart/form-data">
      <div class="row g-3">
        <!-- Full Name -->
        <div class="col-md-6">
          <label for="fullName" class="form-label">Full Name</label>
          <input type="text" class="form-control" id="fullName" name="fullName" placeholder="Enter full name" required>
        </div>

        <!-- Class -->
        <div class="col-md-6">
          <label for="class" class="form-label">Class</label>
          <select class="form-select" id="class" name="class" required>
            <option selected disabled value="">Choose...</option>
            <option value="Play Group">Play Group</option>
            <option value="Nursery">Nursery</option>
            <option value="UKG">UKG</option>
            <option value="1">Class 1</option>
            <option value="2">Class 2</option>
            <option value="3">Class 3</option>
            <option value="4">Class 4</option>
            <option value="5">Class 5</option>
            <option value="6">Class 6</option>
            <option value="7">Class 7</option>
            <option value="8">Class 8</option>
            <option value="9">Class 9</option>
            <option value="10">Class 10</option>
            <option value="11">Class 11</option>
            <option value="12">Class 12</option>
          </select>
        </div>

        <!-- Date of Birth -->
        <div class="col-md-6">
          <label for="dob" class="form-label">Date of Birth</label>
          <input type="date" class="form-control" id="dob" name="dob" required>
        </div>

        <!-- Permanent Address -->
        <div class="col-md-6">
          <label for="address" class="form-label">Permanent Address</label>
          <input type="text" class="form-control" id="address" name="address" placeholder="Enter permanent address" required>
        </div>

        <!-- Parent and Guardian Details -->
        <div class="col-md-6">
          <label for="fatherName" class="form-label">Father's Name</label>
          <input type="text" class="form-control" id="fatherName" name="fatherName" placeholder="Enter father's name" required>
        </div>
        <div class="col-md-6">
          <label for="motherName" class="form-label">Mother's Name</label>
          <input type="text" class="form-control" id="motherName" name="motherName" placeholder="Enter mother's name" required>
        </div>
        <div class="col-md-6">
          <label for="guardianName" class="form-label">Guardian's Name</label>
          <input type="text" class="form-control" id="guardianName" name="guardianName" placeholder="Enter guardian's name" required>
        </div>
        <div class="col-md-6">
          <label for="guardianContact" class="form-label">Guardian's Contact Number</label>
          <input type="tel" class="form-control" id="guardianContact" name="guardianContact" placeholder="Enter guardian's contact number" required>
        </div>

        <!-- File Uploads -->
        <div class="col-md-6">
          <label for="photo" class="form-label">Upload Passport Size Photo</label>
          <input type="file" class="form-control" id="photo" name="photo" accept="image/*" required>
        </div>
        <div class="col-md-6">
          <label for="birthCertificate" class="form-label">Upload Birth Certificate</label>
          <input type="file" class="form-control" id="birthCertificate" name="birthCertificate" accept="application/pdf, image/*" required>
        </div>
        <div class="col-md-6">
          <label for="passedCertificate" class="form-label">Upload Previous Class Passed Certificate</label>
          <input type="file" class="form-control" id="passedCertificate" name="passedCertificate" accept="application/pdf, image/*" required>
        </div>

        <!-- Submit Button -->
        <div class="col-12">
          <button type="submit" class="btn btn-primary w-100">Submit</button>
        </div>
      </div>
    </form>
  </div>

  <!-- Login Section -->
  <div class="container login-section">
    <h3>Admin Login</h3>
    <form action="login.php" method="post">
      <div class="mb-3">
        <label for="username" class="form-label">Username</label>
        <input type="text" class="form-control" id="username" name="username" placeholder="Enter username" required>
      </div>
      <div class="mb-3">
        <label for="password" class="form-label">Password</label>
        <input type="password" class="form-control" id="password" name="password" placeholder="Enter password" required>
      </div>
      <button type="submit" class="btn btn-success">Login</button>
    </form>
  </div>

  <footer>
    <p>Contact us at <strong>066440134</strong> | <a href="mailto:schoollokpriya@gmail.com">schoollokpriya@gmail.com</a> | <a href="https://www.facebook.com/profile.php?id=100091678849960">Facebook</a></p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
