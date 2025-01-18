<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .carousel {
            display: flex;
            overflow-x: auto;
            scroll-snap-type: x mandatory;
        }
        .carousel img {
            scroll-snap-align: center;
            max-width: 100%;
            max-height: 100%;
            width: 301.5px;
            height: 655.5px;
        }
        .carousel::-webkit-scrollbar {
            display: none;
        }
    </style>
</head>
<body>
    <div class="carousel">
        <img src="https://github.com/kawin101/flutter_cupertino_ios_app/blob/main/screenshots/Simulator%20Screenshot%20-%20iPhone%2016%20Pro%20-%202025-01-18%20at%2016.09.22.png" alt="Simulator Screenshot 1">
        <img src="https://github.com/kawin101/flutter_cupertino_ios_app/blob/main/screenshots/Simulator%20Screenshot%20-%20iPhone%2016%20Pro%20-%202025-01-18%20at%2016.09.26.png" alt="Simulator Screenshot 2">
        <img src="https://github.com/kawin101/flutter_cupertino_ios_app/blob/main/screenshots/Simulator%20Screenshot%20-%20iPhone%2016%20Pro%20-%202025-01-18%20at%2016.09.29.png" alt="Simulator Screenshot 3">
    </div>

    # flutter_cupertino_ios_app

    A new Flutter project.

    ## Getting Started

    This project is a starting point for a Flutter application.

    A few resources to get you started if this is your first Flutter project:

    - [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
    - [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
</body>
</html>