# Coding-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weight Converter</title>
    <link rel="stylesheet" href="style.css">
    <!-- Google Fonts for a nicer look -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
</head>
<body>

    <div class="converter-wrapper">
        <h1>Weight Converter</h1>

        <div class="converter-body">
            <div class="input-group">
                <label for="input-value">Value</label>
                <input type="number" id="input-value" value="1" min="0">
            </div>

            <div class="converter-row">
                <!-- "From" Unit Selection -->
                <div class="input-group">
                    <label for="from-unit">From</label>
                    <select id="from-unit">
                        <option value="kg">Kilogram (kg)</option>
                        <option value="lbs">Pound (lbs)</option>
                        <option value="g">Gram (g)</option>
                        <option value="oz">Ounce (oz)</option>
                        <option value="st">Stone (st)</option>
                    </select>
                </div>

                <!-- Swap Button -->
                <div class="swap-button-container">
                    <button id="swap-button" title="Swap Units">
                        ⇆ <!-- Unicode for arrows -->
                    </button>
                </div>

                <!-- "To" Unit Selection -->
                <div class="input-group">
                    <label for="to-unit">To</label>
                    <select id="to-unit">
                        <option value="kg">Kilogram (kg)</option>
                        <option value="lbs" selected>Pound (lbs)</option>
                        <option value="g">Gram (g)</option>
                        <option value="oz">Ounce (oz)</option>
                        <option value="st">Stone (st)</option>
                    </select>
                </div>
            </div>
        </div>

        <div class="result-box">
            <h2>Result</h2>
            <p id="result-text">2.20462 lbs</p>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
