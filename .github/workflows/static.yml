<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laissez votre avis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 50px;
        }
        .container {
            max-width: 400px;
            margin: auto;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }
        textarea {
            width: 100%;
            height: 100px;
            margin-bottom: 10px;
        }
        button {
            background-color: #28a745;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        button:disabled {
            background-color: #ccc;
        }
        .link {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Laissez votre avis sur notre restaurant</h2>
        <textarea id="commentaire" placeholder="Écrivez votre avis ici..."></textarea>
        <br>
        <button id="submitBtn" onclick="enregistrerAvis()">Envoyer</button>
        <div class="link">
            <p><a href="https://www.google.com/search?sa=X&sca_esv=218665eea446f0ac&rlz=1CAOERN_enFR894&tbm=lcl&q=Au+Vieux+Ch%C3%A2telet+Avis&rflfq=1&num=20&stick=H4sIAAAAAAAAAONgkxIwNDcxMjUwNDM3NTE0NLAw3sDI-IpR3LFUISwztbRCwTnj8KKS1JzUEgXHssziRay4ZABReiB1SwAAAA&rldimm=1742501675411083&hl=fr-FR&ved=2ahUKEwjdgYnfqKuMAxWLVaQEHZFjMAEQ9fQKegQIKxAH&cshid=1743114861301259&biw=1242&bih=629&dpr=1.1#lkt=LocalPoiReviews" target="_blank">Visitez notre site</a></p>
        </div>
    </div>
    <script>
        function enregistrerAvis() {
            let commentaire = document.getElementById("commentaire").value.trim();
            if (commentaire.length < 5) {
                alert("Merci de laisser un avis d'au moins 5 caractères avant de continuer.");
            } else {
                alert("Merci pour votre avis ! Vous allez être redirigé vers notre roue de la fortune.");
                // Simuler un enregistrement d'avis (à remplacer par un stockage réel si besoin)
                localStorage.setItem("dernierAvis", commentaire);
                window.location.href = "https://spinthewheel.io/wheels/ZaBwXxZu6cI0oB8YupPLcz0xJmU9MA=="; // Redirection vers la roue personnalisée
            }
        }
    </script>
</body>
</html>
