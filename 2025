<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hey, Justine!</title>
    <style>
        body {
            font-family: 'Verdana', sans-serif;
            text-align: center;
            padding: 20px;
            background-color: #f4f4f9;
            color: #333;
        }
        h1 {
            margin-bottom: 20px;
            color: #555;
        }
        button {
            padding: 12px 18px;
            font-size: 16px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            background-color: #007BFF;
            color: white;
            margin: 10px 5px;
        }
        button:disabled {
            background-color: #ccc;
            cursor: not-allowed;
        }
        .hidden {
            display: none;
        }
        .message-box {
            margin-top: 30px;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>
    <h1>Hey! Before anything else...</h1>
    <p>Happy New Year, Justine! Wow, it’s 2025 already! HAHAHA.</p>
    <div id="step1">
        <button onclick="nextStep(2)">Press to continue</button>
    </div>

    <div id="step2" class="hidden">
        <div class="message-box">
            <p>Alright, here goes nothing. I’ve got some confessions to make:</p>
            <p>1. That time I called you? Yeah, it was me. Nobody forced me; I just didn’t know how else to make the first move. (Dumb, I know.)</p>
            <p>2. I’ve been stalking you—not in a creepy way! It’s just that your posts don’t show up on my feed, and I wanted to react to them. HAHAHA.</p>
            <button onclick="nextStep(3)">Next confession</button>
        </div>
    </div>

    <div id="step3" class="hidden">
        <div class="message-box">
            <p>On a more serious note, I’ve been reflecting a lot lately.</p>
            <p>Relationships are a big responsibility—not a burden, but a commitment. I want to make sure I’m ready for it before stepping in.</p>
            <p>And with what you mentioned about transferring back to CDO for senior high, I got concerned. Not that I assume you’ll be my girlfriend—just thinking positively, you know?</p>
            <p>Anyway, here’s the big one:</p>
            <button onclick="nextStep(4)">Continue</button>
        </div>
    </div>

    <div id="step4" class="hidden">
        <div class="message-box">
            <p>Justine Charm Cabarliza, I like you. Somehow, the idea of being in a relationship doesn’t feel so daunting anymore. And that’s because of you.</p>
            <button onclick="nextStep(5)">Click if you feel the same</button>
        </div>
    </div>

    <div id="step5" class="hidden">
        <div class="message-box">
            <p>Can I court you?</p>
            <button onclick="finalResponse('yes')">Yes</button>
            <button onclick="finalResponse('no')">No</button>
        </div>
    </div>

    <script>
        function nextStep(step) {
            document.querySelectorAll('div').forEach(div => div.classList.add('hidden'));
            document.getElementById('step' + step).classList.remove('hidden');
        }

        function finalResponse(answer) {
            if (answer === 'yes') {
                alert("Thank you! You've made my day. 😊");
            } else {
                alert("Oops, this button is disabled. Maybe you should reconsider? 😅");
            }
        }
    </script>
</body>
</html>
