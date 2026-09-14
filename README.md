# Increment-Decrement
<!DOCTYPE html>
<html>
<head>
    <title>Counter App</title>
</head>
<body style="text-align: center; font-family: sans-serif;">

    <!-- This represents the text on the chalkboard -->
    <h1>Count: <span id="counter">0</span></h1>

    <!-- These represent the buttons on the chalkboard -->
    <button onclick="increment()" style="padding: 15px; margin: 10px; font-size: 18px;">Increment</button>
    <button onclick="decrement()" style="padding: 15px; margin: 10px; font-size: 18px;">Decrement</button>

    <script>
        // This is our 'Count' variable, starting at 0
        let count = 0;

        // This is the "Increment" function
        function increment() {
            count++;
            document.getElementById("counter").innerText = count;
        }

        // This is the "Decrement" function
        function decrement() {
            count--;
            document.getElementById("counter").innerText = count;
        }
    </script>

</body>
</html>
