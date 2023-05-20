# LandingPage
<!DOCTYPE html>
<html>
<head>
    <title>Query String Example</title>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script>
        $(document).ready(function() {
            // Get the query string from the current URL
            var queryString = window.location.search;

            // Print the query string to the HTML element with id "output"
            $("#output").text(queryString);
        });
    </script>
</head>
<body>
    <h1>Query String Example</h1>
    <p id="output"></p>
</body>
</html>
