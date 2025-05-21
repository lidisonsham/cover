##Ex.06 Book Front Cover Page Design
## Date: 21-04-2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>React.js Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #0d1117;
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: linear-gradient(160deg, #161b22 40%, #0d1117);
      border: 2px solid #30363d;
      border-radius: 10px;
      box-shadow: 0 0 25px rgba(97, 218, 251, 0.25);
      color: #fff;
      padding: 40px 30px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      position: relative;
    }

    .edition-badge {
      position: absolute;
      top: 20px;
      left: 20px;
      background-color: #61dafb;
      color: #0d1117;
      font-weight: bold;
      padding: 6px 14px;
      border-radius: 20px;
      font-size: 12px;
    }

    .book-title {
      font-size: 38px;
      font-weight: bold;
      line-height: 1.3;
      margin-top: 60px;
      text-align: center;
    }

    .subtitle {
      font-size: 16px;
      color: #bbb;
      margin-top: -40px;
      line-height: 1.5;
      text-align: center;
    }

    .react-icon {
      width: 150px;
      margin: 30px auto;
    }

    .author-line {
      width: 50%;
      height: 2px;
      background-color: #61dafb;
      margin: -70px auto;
      border-radius: 10px;
    }

    .author-container {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 10px;
    }

    .author-pic {
      width: 60px;
      height: 60px;
      border-radius: 50%;
      object-fit: cover;
      margin-right: 15px;
      border: 2px solid #61dafb;
    }

    .author-info {
      text-align: left;
    }

    .author {
      font-size: 16px;
      font-weight: bold;
      color: #ffffff;
    }

    .publisher {
      font-size: 14px;
      color: #61dafb;
      font-weight: bold;
      margin-top: 4px;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="edition-badge">Second Edition</div>
    <div class="book-title">Mastering React.js</div>
    <div class="subtitle">
      Build dynamic, scalable web apps using modern React techniques, hooks, and functional components.
    </div>
    
    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" alt="React Logo" class="react-icon">

    <div class="author-line"></div>

    <div class="author-container">
      <img src="https://i.pravatar.cc/150?img=12"  alt="Author Picture" class="author-pic">
      <div class="author-info">
        <div class="author">Jordan Walke</div>
        <div class="publisher">OpenSource Books</div>
      </div>
    </div>
  </div>
</body>
</html>
```


## OUTPUT:
![Screenshot 2025-04-21 195108](https://github.com/user-attachments/assets/5fa0f673-798c-41a7-a851-7c4f2e27ee20)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
