<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #f9f9f9;
    }

    .container {
        max-width: 600px;
        margin: 10% auto;
        background-color: #fafafa;
        box-shadow: 0 10px 15px rgba(179, 179, 179, 0.7);
        padding: 30px;
        display: flex;
        flex-direction: column;
        align-items: center;
        border-radius: 10px;
    }

    h1 {
        font-size: 2rem;
        text-align: center;
        margin-bottom: 20px;
    }

    form {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 100%;
    }

    input,
    textarea {
        font-size: 16px;
        padding: 10px;
        width: 100%;
        border: 1px solid #ccc;
        border-radius: 5px;
        margin-bottom: 15px;
    }

    textarea {
        height: 150px;
        resize: vertical;
    }

    button {
        font-size: 16px;
        padding: 10px 20px 13px;
        border: none;
        background-color: #827397;
        color: white;
        border-radius: 5px;
        cursor: pointer;
        width: 100%;
    }
</style>

<body>
    <div class="container">
        <h1>Product One Feedback</h1>
        <form action="#">
            <input type="text" placeholder="Enter Full Name">
            <input type="email" placeholder="Enter Email">
            <legend>--------</legend>
            <textarea placeholder="Give Product One Feedback"></textarea>
            <button type="submit">Submit</button>
        </form>
    </div>
</body>
