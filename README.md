<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plener Roślinny</title>
    <style> 
        @font-face {
            font-family: 'Magical Signature';
            src: url("D:\Pobrane\workshop-code-master\fonts\Magical Signature.ttf") format('truetype');
            font-weight: normal;
            font-style: normal;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
        }

        header {
            text-align: center;
            color: #2f594f;
            margin-bottom: 20px;
        }

        header h1 {
            font-size: 3.5em;
            margin: 0;
            font-family: 'Magical Signature';
        }

        header h2 {
            font-size: 1.5em;
            font-weight: 400;
            font-family: 'Courier New', Courier, monospace;
        }

        main { 
            display: flex;
            gap: 20px;
            width: 80%;
            max-width: 800px;
        }

        .left-column, .right-column {
            width: 50%;
        }

        .form-group {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }

        label {
            width: 40%;
            font-size: 1.1em;
            color: #2f594f;
            font-family: 'Montserrat', Arial, sans-serif;
        }

        input, textarea {
            width: 60%;
            padding: 8px;
            font-size: 1em;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        textarea {
            height: 100px;
            resize: none;
        }
    </style>
</head>

<body>
    <div>
        <header>
            <h1>Planer Paszczaka</h1>
            <h2>Karta Rośliny</h2>
        </header>
        <main>
            <div class="left-column">
                <div class="form-group">
                    <label>Nazwa rośliny</label>
                    <input type="text" placeholder="Wpisz nazwę rośliny">
                </div>
                <div class="form-group">
                    <label>Nazwa łac. rośliny</label>
                    <input type="text" placeholder="Wpisz nazwę łacińską">
                </div>
                <div class="form-group">
                    <label>Data i miejsce zakupu</label>
                    <input type="text" placeholder="Wpisz datę i miejsce zakupu">
                </div>
                <div class="form-group">
                    <label>Cena</label>
                    <input type="text" placeholder="Wpisz cenę">
                </div>
                <div class="form-group">
                    <label>Rodzaj podłoża</label>
                    <input type="text" placeholder="Wpisz rodzaj podłoża">
                </div>
            </div>

            <div class="right-column">
                <div class="form-group">
                    <label>Metoda propagacji</label>
                    <input type="text" placeholder="Opisz metodę propagacji">
                </div>
                <div class="form-group">
                    <label>Przycinanie i szczepki</label>
                    <input type="text" placeholder="Opisz przycinanie i szczepki">
                </div>
                <div class="form-group">
                    <label>Przesadzanie</label>
                    <input type="text" placeholder="Opisz przesadzanie">
                </div>
                <div class="form-group">
                    <label>Notatki</label>
                    <textarea placeholder="Dodaj swoje notatki tutaj..."></textarea>
                </div>
            </div>  
        </main>
    </div>
</body>
</html>

