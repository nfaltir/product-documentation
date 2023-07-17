<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #f9f9f9;
    }

    .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
    }

    h1 {
        font-size: 3rem;
        font-weight: bold;
        text-transform: uppercase;
        text-align: center;
        margin-top: 50px;
    }

    p {
        text-align: center;
    }

    .card-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        margin-top: 50px;
    }

    .card {
        width: 350px;
        margin: 20px;
        padding: 20px;
        background-color: #fafafa;
        border-radius: 10px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        text-align: center;
    }

    .card h1 {
        font-size: 1.8rem;
        margin-bottom: 10px;
    }

    .card p {
        margin-bottom: 20px;
    }

    .card a {
        display: block;
        width: 200px;
        margin: 0 auto;
        padding: 10px;
        background-color: rebeccapurple;
        color: white;
        border-radius: 5px;
        text-decoration: none;
        text-align: center;
    }

    @media (max-width: 768px) {
        .card-container {
            justify-content: flex-start;
        }

        .card {
            width: 100%;
            margin: 20px 0;
        }
    }
</style>

<body>
    <div class="container">
        <h1>Products</h1>
        <p>Please select a product to view all documentation and release notes.</p>
        <div class="card-container">
            <div class="card">
                <h1>Product One</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit minima quidem ex tempore quisquam sapiente
                    quia sed eaque molestias? Repudiandae!</p>
                <a href="kba/#product-one">View Docs</a>
            </div>
            <div class="card">
                <h1>Product Two</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit minima quidem ex tempore quisquam sapiente
                    quia sed eaque molestias? Repudiandae!</p>
                <a href="kba/#product-two">View Docs</a>
            </div>
            <div class="card">
                <h1>Product Three</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit minima quidem ex tempore quisquam sapiente
                    quia sed eaque molestias? Repudiandae!</p>
                <a href="kba/#product-three">View Docs</a>
            </div>
            <div class="card">
                <h1>Product Four</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit minima quidem ex tempore quisquam sapiente
                    quia sed eaque molestias? Repudiandae!</p>
                <a href="kba/#product-four">View Docs</a>
            </div>
        </div>
    </div>
</body>
