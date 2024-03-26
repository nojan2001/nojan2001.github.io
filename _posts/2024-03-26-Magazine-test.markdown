---
layout: post
title:  "Magazine Test"
date:   2024-03-26 23:50:39 +0100
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
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent in malesuada magna, non faucibus augue. Fusce at lacus id dolor molestie malesuada. Nam aliquam turpis porta fermentum volutpat. Cras lobortis diam lorem, id aliquam ante sagittis a. Sed cursus ut velit nec sagittis. Etiam congue eu libero at egestas. Nunc ornare in felis nec placerat.Nullam lacinia rhoncus eleifend. Nam quis purus risus. Mauris eget vulputate nisi, at aliquet ipsum. Nunc id ex quam. Sed finibus arcu a libero fermentum luctus. Sed eu condimentum sapien. Pellentesque sed sem ac erat finibus faucibus id accumsan dui. Cras aliquam mauris non neque luctus aliquet. Nunc congue ex sit amet metus bibendum sodales. Integer sodales eros eget neque luctus, ut rutrum nulla condimentum. Integer volutpat neque eget elementum iaculis. Aliquam vel aliquam quam. Mauris et mauris nec lectus sagittis porttitor et non ipsum. Curabitur tempor mi risus. Nam sagittis purus vel iaculis aliquam. Fusce eget eleifend est.</p>
            <iframe src="/output.html" width="100%" height="300px"></iframe>
        </div>
        <div class="column">
            <h2>Column 2</h2>
            <p>Vestibulum luctus nulla ac massa venenatis, eu tristique nisl porta. Nulla ut risus nisi. Vestibulum quis mauris neque. Vestibulum feugiat laoreet lacus eu semper. Proin fringilla tempus libero, non posuere libero blandit a. Sed gravida lacinia feugiat. Curabitur non imperdiet urna, a dignissim mi. In sem nulla, semper sit amet libero et, vestibulum rhoncus leo. Duis vitae consequat magna. Phasellus vel ultricies nulla. Duis aliquam mollis molestie. Morbi volutpat risus in turpis maximus vulputate. Praesent et maximus massa, a facilisis purus. Vivamus vestibulum arcu in erat accumsan, vitae commodo purus mollis. Vivamus ullamcorper ligula tincidunt neque hendrerit, at eleifend sapien porttitor.Sed rhoncus, libero ac ullamcorper varius, nunc lorem condimentum ante, ut iaculis est lacus at felis. Duis luctus mauris at est efficitur lacinia. Sed rutrum vel nisl ac pulvinar. Phasellus dapibus massa id diam gravida, eget eleifend odio ultrices. Donec blandit libero ut nisi volutpat porttitor. Pellentesque erat nunc, luctus id maximus lacinia, interdum et diam. Praesent dapibus mauris ipsum, vitae bibendum quam tempus vitae. Cras a lectus a odio dapibus iaculis. Phasellus consectetur velit ultricies purus scelerisque, non finibus sem mollis. Suspendisse quis tellus mi.</p>
            <iframe src="/output.html" width="100%" height="300px"></iframe>
        </div>
        <div class="column">
            <h2>Column 3</h2>
            <p>Cras interdum nec erat sit amet elementum. Aliquam mattis urna in nisl elementum euismod. Donec in varius eros, volutpat pulvinar nibh. Praesent a blandit justo. Vivamus nec sapien metus. Aenean sem purus, semper nec laoreet ac, sollicitudin vitae libero. Nullam tincidunt leo non dignissim fermentum. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer vel lacinia augue, in sollicitudin lectus. Curabitur sit amet leo egestas, laoreet velit interdum, volutpat neque. Suspendisse interdum nulla sit amet enim vulputate, eu tincidunt est pulvinar. Vestibulum egestas facilisis mauris. Aenean facilisis viverra tristique. Nam in lorem eleifend, viverra urna eget, mollis mauris. Donec eget mauris in est elementum auctor accumsan faucibus nulla.</p>
            <iframe src="/output.html" width="100%" height="300px"></iframe>
        </div>
    </div>
</body>
</html>

