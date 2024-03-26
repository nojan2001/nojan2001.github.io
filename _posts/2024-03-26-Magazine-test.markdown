---
layout: post
title:  "Welcome to Jekyll!"
date:   2024-03-11 15:27:14 +0100
categories: jekyll update
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Magazine Style Layout</title>
    <style>
        .container {
            display: flex;
            justify-content: space-between;
            margin: 20px auto;
            max-width: 1200px;
        }

        .column {
            flex: 1;
            margin-right: 20px;
        }

        .column:last-child {
            margin-right: 0;
        }

        .column figure {
            margin-bottom: 20px;
        }

        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }

            .column {
                margin-right: 0;
                margin-bottom: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="column">
            <h2>Column 1</h2>
            <p>This is the content of column 1.</p>
            <iframe src="/output.html" width="100%" height="300px"></iframe>
        </div>
        <div class="column">
            <h2>Column 2</h2>
            <p>This is the content of column 2.</p>
            <iframe src="/output.html" width="100%" height="300px"></iframe>
        </div>
        <div class="column">
            <h2>Column 3</h2>
            <p>This is the content of column 3.</p>
            <iframe src="/output.html" width="100%" height="300px"></iframe>
        </div>
    </div>
</body>
</html>

