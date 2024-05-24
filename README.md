<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coaching Hemsida</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffffff;
            color: #000000;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        header {
            text-align: center;
            padding: 50px 0;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        section {
            margin: 50px 0;
        }
        .services, .testimonials, .booking {
            background-color: #f7f7f7;
            padding: 20px;
            border-radius: 10px;
        }
        .booking form {
            display: flex;
            flex-direction: column;
        }
        .booking label {
            margin: 10px 0 5px;
        }
        .booking input, .booking textarea {
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .booking button {
            padding: 15px;
            background-color: #000;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .booking button:hover {
            background-color: #333;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Välkommen till Din Coachnings Hemsida</h1>
            <p>Din partner för viktminskning, muskelökning och viktökning</p>
        </header>

        <section class="about">
            <h2>Om Mig</h2>
            <p>Hej! Jag är din personliga coach med flera års erfarenhet inom hälsa och fitness. Jag har hjälpt många klienter att nå sina mål, oavsett om det handlar om att gå ner i vikt, bygga muskler eller gå upp i vikt på ett hälsosamt sätt. Min metod är baserad på evidensbaserad praktik och personlig anpassning för att möta dina unika behov och mål.</p>
        </section>

        <section class="testimonials">
            <h2>Klientreferenser</h2>
            <div class="testimonial">
                <p>"Jag har lyckats gå ner 10 kilo och känner mig starkare än någonsin tack vare min coach!" - Anna</p>
            </div>
            <div class="testimonial">
                <p>"Min coach har hjälpt mig att bygga muskler på ett sätt jag aldrig trodde var möjligt. Rekommenderas starkt!" - Erik</p>
            </div>
        </section>

        <section class="services">
            <h2>Tjänster</h2>
            <ul>
                <li>Viktminskningsprogram</li>
                <li>Muskelbyggande program</li>
                <li>Viktökningsprogram</li>
                <li>Personlig träningsplan</li>
                <li>Kostrådgivning</li>
            </ul>
        </section>

        <section class="booking">
            <h2>Boka en Konsultation</h2>
            <form>
                <label for="name">Namn:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">E-post:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="goal">Vad är ditt mål?</label>
                <textarea id="goal" name="goal" rows="4" required></textarea>
                
                <button type="submit">Boka Nu</button>
            </form>
        </section>
    </div>
</body>
</html>
