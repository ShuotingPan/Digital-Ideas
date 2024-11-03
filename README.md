<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Ideas Evaluation Tool</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            display: flex;
            flex-direction: column;
        }
        .iframe-container {
            flex: 1;
            display: flex;
            flex-direction: column;
        }
        iframe {
            width: 100%;
            border: none;
            flex: 1;
        }
        .tabs {
            height: 40px;
            background-color: #f0f0f0;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 14px;
        }
        .tabs a {
            margin: 0 10px;
            text-decoration: none;
            color: #333;
        }
    </style>
</head>
<body>

    <!-- Tabs navigation (simplified) -->
    <div class="tabs">
        <a href="副本Digital%20Ideas%20Evaluation%20Tool%20(1).fld/sheet001.htm" target="content-frame">Sheet 1</a>
        <!-- Add other tabs as needed -->
    </div>

    <!-- Content iframe -->
    <div class="iframe-container">
        <iframe src="副本Digital%20Ideas%20Evaluation%20Tool%20(1).fld/sheet001.htm" name="content-frame"></iframe>
    </div>

</body>
</html>
