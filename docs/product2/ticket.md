<style>
    body {
        background-color: #f9f9f9;
        font-family: Arial, sans-serif;
    }

    .product-one-ticket{
        text-align:center;
        font-weight:bold;
    }

    .form-container {
        max-width: 500px;
        margin: 10% auto;
        background-color: #fff;
        border-radius: 8px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        padding: 30px;
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .form-title {
        font-size: 24px;
        font-weight: bold;
        color: #333;
        margin-bottom: 20px;
        text-align: center;
    }

    .form-label {
        font-size: 16px;
        color: #666;
        margin-bottom: 5px;
    }

    .form-input {
        font-size: 16px;
        padding: 10px;
        width: 100%;
        border: 1px solid #ccc;
        border-radius: 5px;
        margin-bottom: 15px;
    }

    .form-textarea {
        font-size: 16px;
        padding: 10px;
        width: 100%;
        height: 150px;
        border: 1px solid #ccc;
        border-radius: 5px;
        resize: vertical;
        margin-bottom: 15px;
    }

    .form-button {
        font-size: 16px;
        padding: 10px 20px;
        border: none;
        background-color: steelblue;
        color: #fff;
        border-radius: 5px;
        cursor: pointer;
        width: 100%;
    }
</style>

<body>
    <h1 class="product-one-ticket">Product Two Service Request</h1>
    <div class="form-container">
        <h2 class="form-title">Contact Us</h2>
        <form action="#">
            <label class="form-label" for="fullName">Full Name:</label>
            <input id="fullName" class="form-input" type="text" placeholder="Enter Full Name">
            <label class="form-label" for="email">Email:</label>
            <input id="email" class="form-input" type="email" placeholder="Enter Email">
            <label class="form-label" for="problemDescription">Problem Description:</label>
            <textarea id="problemDescription" class="form-textarea" placeholder="Describe your Product Two problem"></textarea>
            <button class="form-button" type="submit">Submit</button>
        </form>
    </div>
</body>
