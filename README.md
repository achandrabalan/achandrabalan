<!DOCTYPE html>
<html>
<head>
    <style>
        .container {
            display: flex; /* Use flexbox */
        }

        .widget {
            flex: 1; /* Equal flex distribution to both widgets */
            border: 1px solid #ccc;
            padding: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="widget">
            <!-- Widget 1 content goes here -->
            <h2>Widget 1</h2>
            <p>Widget 1 content goes here.</p>
        </div>
        <div class="widget">
            <!-- Widget 2 content goes here -->
            <h2>Widget 2</h2>
            <p>Widget 2 content goes here. It will have the same height as Widget 1.</p>
        </div>
    </div>
</body>
</html>
