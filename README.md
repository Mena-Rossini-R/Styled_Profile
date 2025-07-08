# Styled_Profile_Card
## Date:8/7/2025

## Objective:
To practice HTML and CSS fundamentals by designing a visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques.

## Tasks:
#### 1. Create the HTML Structure:
Use ```<!DOCTYPE html>, <html>, <head>, and <body>``` to define the structure.
Add a ```<title>``` like "My Profile Card".

#### 2. Add Content:
Include name, title (e.g., Developer, Student), and a short bio using semantic tags such as ```<h1>```, ```<h2>```, and ```<p>```.

#### 3. Add a Profile Image:
Use the ```<img>``` tag to include a profile picture with appropriate alt, width, and height attributes.

#### 4. Apply Background Color:
Use a CSS class to style the card with a background color.

#### 5. Style Typography:
Use CSS to apply different font families, sizes, and text colors for the name and bio.

#### 6. Add Spacing:
Apply margin and padding to improve spacing between elements using CSS.

#### 7. Center the Card:
Use flexbox or margin: auto to center the card vertically and horizontally on the page.

#### 8. Add Hover Effects:
Enhance interactivity with simple hover effects like border changes or background transition using CSS.

## HTML Code:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>My Profile</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="profile-card">
        <section>
            <img src="image.png" alt="Profile Picture" width="150" height="150">
            <h1>Mena Rossini R</h1>
            <h2>Student | Web Developer</h2>
        </section>

        <hr>

        <section class="bio">
            <p>
                Hello! I'm a passionate Computer Science student who loves building web applications and solving
                logical problems. I enjoy participating in hackathons, learning new technologies, and
                contributing to meaningful projects. In my free time, I knit, read detective books,
                and explore the world of anime.
            </p>
        </section>
    </div>

</body>
</html>

```

## CSS Code:

```
body {
    background-color: #f0f0f0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
}

.profile-card {
    max-width: 500px;
    margin: 50px auto;
    background-color: #ffffff;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
    padding: 30px;
    border-radius: 15px;
}

.profile-card img {
    display: block;
    margin: 0 auto 20px auto;
    border-radius: 50%;
    border: 3px solid #ccc;
}

.profile-card h1 {
    text-align: center;
    color: #2c3e50;
    font-size: 2em;
    margin: 0;
}

.profile-card h2 {
    text-align: center;
    color: #6c757d;
    font-size: 1.2em;
    margin-top: 10px;
}

.bio {
    background-color: #fafafa;
    padding: 20px;
    border-left: 4px solid #4caf50;
    border-radius: 8px;
    line-height: 1.6;
    margin-top: 20px;
}

hr {
    margin: 25px 0;
    border: none;
    border-top: 1px solid #ddd;
}
```

## Output:

![image](https://github.com/user-attachments/assets/1d6b9d2b-b107-44f6-89cd-fa3995c5ff50)


## Result:
A visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques is designed.
