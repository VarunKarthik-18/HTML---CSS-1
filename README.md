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
