# testrum

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Webpage Title</title>
    <!-- Add the Middleware RUM script tag to the head section -->
    <script src="https://cdnjs.middleware.io/browser/libs/0.0.1/middleware-rum.min.js" type="text/javascript"></script>
    <!-- Add your custom script -->
    <script>
        if (window.Middleware){
            Middleware.track({
                serviceName: "testrum",
                projectName: "testrum",
                accountKey: "vxouhntdkrtedihzwejydfeshhpbpkczhjfc",
                target: "https://rp7tv69.middleware.io",
            });
        }
    </script>
</head>
<body>
    <!-- Your webpage content goes here -->
</body>
</html>
