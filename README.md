Creating a multimedia-rich webpage with audio and video elements
Designing a registration form with validation attributes # Week-3day-2-assignment-
My assignment for week 3day 2 


Multimedia-Rich Webpage (Audio and Video Elements)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multimedia Page</title>
</head>
<body>
    <h1>Welcome to My Multimedia Page</h1>
    
    <h2>Audio Section</h2>
    <audio controls>
        <source src="audio-file.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
    
    <h2>Video Section</h2>
    <video controls width="600">
        <source src="video-file.mp4" type="video/mp4">
        Your browser does not support the video element.
    </video>
</body>
</html>

Registration Form with Validation Attributes

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
</head>
<body>
    <h1>Registration Form</h1>
    <form action="/submit" method="POST">
        <!-- Name Field -->
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" required>
        <br><br>

        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <br><br>

        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" minlength="8" required>
        <br><br>

        <!-- Age Field -->
        <label for="age">Age:</label>
        <input type="number" id="age" name="age" min="18" required>
        <br><br>

        <!-- Gender Selection -->
        <label for="gender">Gender:</label>
        <select id="gender" name="gender" required>
            <option value="">Select</option>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select>
        <br><br>

        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>
</body>
</html>

