<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
    <style>
        /* Standard-Header-Styles */
        header {
            padding: 20px;
            background: #f0f0f0;
        }

        /* Apple Watch Optimierung */
        @media only screen and (max-device-width: 396px) and (max-device-height: 484px) {
            header {
                padding: 8px 10px;
                font-size: 14px;
            }
            nav {
                flex-direction: column;
            }
            .menu-button {
                padding: 12px;
                min-width: 48px;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <button class="menu-button">Menü</button>
        </nav>
    </header>
</body>
</html>