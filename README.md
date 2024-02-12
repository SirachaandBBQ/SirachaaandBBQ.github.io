<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Valentine, Mala?</title>
    <style>
        body {
            background-color: lavender;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        h1 {
            color: #333;
        }
        .cat-gif {
            max-width: 100%;
            height: auto;
        }
        .response {
            font-size: 18px;
            margin-top: 20px;
        }
        #yes {
            font-size: 105%;
        }
    </style>
</head>
<body>
    <h1>Will You Be My Valentine, Mala?</h1>
    <img class="cat-gif" src="https://gifdb.com/images/high/cat-begging-its-owner-fqm721e0abbe562d.gif" alt="Cute cat begging">
    <div class="response">
        <p id="no">No</p>
        <p id="yes">Yes</p>
    </div>

    <script>
        const noResponses = [
            "Please, pookie.",
            "I'll bite your toes if you don't tap Yes.",
            "How dare you?",
            "You're breaking my heart.",
            "I'm taking custody of Timon and Cheetos.",
            "You're on academic and love probation now, hmph.",
            "Good girls click Yes, ueue.",
            "Pookie is no good girl.",
            "You wanna die?",
            "Ill ask sisi then smh",
            "Come onnnnnnnn buba ill buy you choco",
            "How about sushi?",
            "If you click yes youll get a video",
            "My goodlooking girl it's time to click yes",
            "coding takes forever come on",
            "we might as well talk here then smh",
            "did you eat my love?",
            "may your bumbum be always pink",
            "sisi the mexican egyptian will come for you",
            "i love you darling click yes",
            "goddamn woman you are stubborn arent we my love?",
            "istg when i come ill bite your cheeks, all 4 of them",
            "my love for you is like diarehea, i cant hold it in",
            "fine may my dad jokes begin",
            "gurl you're like arthritis, no punchline",
            "gurl youre so sweet you gave me diabetes",
            "gurl youre like appendicitis, my love for you explodes",
            "wifey just tap yes ueueu",


        ];

        const yesResponse = "Thank you for being my valentine, my love. I love you more than anything in this world.";

        const noButton = document.getElementById("no");
        const yesButton = document.getElementById("yes");

        noButton.addEventListener("click", () => {
            const randomIndex = Math.floor(Math.random() * noResponses.length);
            noButton.textContent = noResponses[randomIndex];
        });

        yesButton.addEventListener("click", () => {
            yesButton.textContent = "🐻🐻 " + yesResponse;
        });
    </script>
</body>
</html>
