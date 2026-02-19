<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            background-color: #f5f7fa;
            display: flex;
            justify-content: center;
            padding: 20px;
        }

        .quiz-container {
            background-color: #ffffff;
            width: 100%;
            max-width: 500px;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            text-align: center;
        }

        .quiz-title {
            color: #0070ba;
            font-size: 28px;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .quiz-subtitle {
            font-size: 14px;
            color: #666;
            margin-bottom: 30px;
        }

        .question-block {
            text-align: left;
            margin-bottom: 25px;
        }

        .question-text {
            font-size: 16px;
            font-weight: 500;
            color: #333;
            margin-bottom: 12px;
            display: block;
        }

        /* Styliser l-input (Optional: kikhallik t-cliqui 3la l-khana) */
        .options-group {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
        }

        .option-item {
            display: flex;
            align-items: center;
            font-size: 15px;
            color: #555;
            cursor: pointer;
        }

        .option-item input {
            margin-right: 8px;
            accent-color: #0070ba; /* PayPal Blue */
        }

        .claim-btn {
            background-color: #0070ba;
            color: white;
            border: none;
            width: 100%;
            padding: 15px;
            border-radius: 30px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            transition: background 0.3s ease;
            margin-top: 10px;
        }

        .claim-btn:hover {
            background-color: #005ea6;
        }
    </style>
</head>
<body>

<div class="quiz-container">
    <div class="quiz-title">Quiz</div>
    <div class="quiz-subtitle">This is the most important step to "warm up" the client:</div>

    <div class="question-block">
        <span class="question-text">Do you have a valid PayPal account?</span>
        <div class="options-group">
            <label class="option-item"><input type="radio" name="q1"> Yes</label>
            <label class="option-item"><input type="radio" name="q1"> No</label>
        </div>
    </div>

    <div class="question-block">
        <span class="question-text">How often do you shop online?</span>
        <div class="options-group">
            <label class="option-item"><input type="radio" name="q2"> Daily</label>
            <label class="option-item"><input type="radio" name="q2"> Weekly</label>
            <label class="option-item"><input type="radio" name="q2"> Rarely</label>
        </div>
    </div>

    <div class="question-block">
        <span class="question-text">Would a $100 credit help your next purchase?</span>
        <div class="options-group">
            <label class="option-item"><input type="radio" name="q3"> Absolutely!</label>
            <label class="option-item"><input type="radio" name="q3"> Maybe</label>
        </div>
    </div>

    <button class="claim-btn">Claim Your Prize Now</button>
</div>

</body>
</html>
