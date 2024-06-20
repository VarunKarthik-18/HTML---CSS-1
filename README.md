<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>InstiOLX Selling Interface</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="header">
        <img src="HP_Shop.png" alt="Happy Shopping Logo" class="logo">
        <img src="InstiOLX_wall2.01.png" alt="InstiOLX Logo" class="logo">
    </div>
    <div class="container">
        <h1>Sell Your Item</h1>
        <form>
            <div class="form-group">
                <label for="title">Title</label>
                <input type="text" id="title" name="title" required>
            </div>
            <div class="form-group">
                <label for="description">Description</label>
                <textarea id="description" name="description" rows="4" required></textarea>
            </div>
            <div class="form-group">
                <label for="price">Price</label>
                <input type="number" id="price" name="price" required>
            </div>
            <div class="form-group">
                <label for="buying-date">Buying Date</label>
                <input type="date" id="buying-date" name="buying-date" required>
            </div>
            <div class="form-group">
                <label for="buying-price">Buying Price</label>
                <input type="number" id="buying-price" name="buying-price" required>
            </div>
            <div class="form-group">
                <label for="photos">Upload Photos</label>
                <input type="file" id="photos" name="photos" multiple accept="image/*">
            </div>
            <div class="form-group">
                <label for="details">Your Details</label>
                <textarea id="details" name="details" rows="2" required></textarea>
            </div>
            <div class="form-group">
                <label for="phone">Phone Number</label>
                <input type="tel" id="phone" name="phone" required>
            </div>
            <div class="form-group">
                <label for="location">Location</label>
                <input type="text" id="location" name="location" required>
            </div>
            <div class="form-group">
                <button type="submit">Post</button>
            </div>
        </form>
    </div>
</body>
</html>




/* styles.css */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

.header {
    text-align: center;
    margin: 20px 0;
}

.header .logo {
    width: 150px;
    height: auto;
    margin: 0 20px;
}

.container {
    max-width: 600px;
    margin: 20px auto;
    padding: 20px;
    background: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

h1 {
    text-align: center;
    margin-bottom: 20px;
    color: #333;
    font-family: 'Georgia', serif;
}

.form-group {
    margin-bottom: 15px;
}

.form-group label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
    color: #555;
    font-family: 'Verdana', sans-serif;
}

.form-group input,
.form-group textarea,
.form-group button {
    width: 100%;
    padding: 10px;
    font-size: 16px;
    border: 1px solid #ddd;
    border-radius: 4px;
    font-family: 'Arial', sans-serif;
}

.form-group button {
    background-color: #28a745;
    color: #fff;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.form-group button:hover {
    background-color: #218838;
}

/* Responsive Design */
@media (max-width: 768px) {
    .container {
        padding: 15px;
    }

    .form-group input,
    .form-group textarea,
    .form-group button {
        font-size: 14px;
    }

    .header .logo {
        width: 100px;
        margin: 10px 10px;
    }
}

