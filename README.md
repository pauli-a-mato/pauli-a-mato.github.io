<!DOCTYPE html>
<html lang="sk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Naša Svadba</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #ffffff;
            color: #4a4a4a;
            margin: 0;
            padding: 0;
        }
        #logo img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 20px;
            border: 4px solid #7b1fa2;
        }
        header {
            background-color: #f8f8f8;
            color: #333;
            padding: 20px 0;
            text-align: center;
            border-bottom: 1px solid #e0e0e0;
            position: relative;
        }
        #logo img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 20px;
            border: 4px solid #7b1fa2;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        .language-switch {
            position: absolute;
            top: 20px;
            right: 20px;
        }

        .language-switch img {
            width: 30px;
            margin: 0 10px;
            cursor: pointer;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #f1f1f1;
            padding: 15px;
        }

        nav a {
            color: #555;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.2rem;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #333;
        }

        .section {
            padding: 60px 20px;
            text-align: center;
        }

        h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: #444;
        }

        .content-sk, .content-en {
            display: none;
        }

        .details-list {
            list-style: none;
            padding: 0;
            color: #555;
        }

        .details-list li {
            font-size: 1.2rem;
            padding: 10px 0;
        }

        footer {
            background-color: #f8f8f8;
            color: #333;
            text-align: center;
            padding: 20px;
            border-top: 1px solid #e0e0e0;
        }

        footer p {
            margin: 0;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px;
            background-color: #555;
            color: #fff;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            font-size: 1rem;
        }

        .button:hover {
            background-color: #333;
        }

        input, button {
            margin: 10px 0;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ddd;
            width: 80%;
            max-width: 400px;
        }

        button {
            background-color: #555;
            color: white;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: #333;
        }

        /* Show the Slovak content by default */
        .content-sk {
            display: block;
        }
    </style>
</head>
<body>
<img src="logo.png" alt="logo" id="logo" align="middle">
    <header>
        <h1>Pauli a Maťo</h1>
        <div class="language-switch">
            <img src="sk-flag.png" alt="Slovak" id="sk-flag">
            <img src="us-flag.png" alt="English" id="en-flag">
        </div>
        <p class="content-sk">10.5.2025, Drevenice Terchová</p>
        <p class="content-en">10.5.2025, Drevenice Terchová</p>
    </header>

    <nav>
        <a href="#how-to-get-there">Ako sa k nám dostať</a>
        <a href="#what-to-do">Čo robiť v Terchovej</a>
        <a href="#timeline">Harmonogram</a>
        <a href="#rsvp">RSVP</a>
    </nav>

    <section id="how-to-get-there" class="section">
        <h2 class="content-sk">Ako sa dostať</h2>
        <h2 class="content-en">How to Get There</h2>
        <p class="content-sk">Miesto svadby sa nachádza na The Grand Venue, 123 Wedding St, Mesto, Krajina. Nižšie sú uvedené pokyny na cestovanie autom a verejnou dopravou:</p>
        <p class="content-en">The wedding venue is located at The Grand Venue, 123 Wedding St, City, Country. Below are driving directions and public transport options:</p>
        <ul class="details-list content-sk">
            <li>Autom: Na mieste je k dispozícii bezplatné parkovanie.</li>
            <li>Autobusom: Choďte autobusom 42A na Wedding St.</li>
            <li>Vlakom: Najbližšia vlaková stanica je Wedding Central, 10 minút pešo od miesta konania.</li>
        </ul>
        <ul class="details-list content-en">
            <li>By Car: Free parking available on-site.</li>
            <li>By Bus: Take the 42A bus to Wedding St.</li>
            <li>By Train: The nearest train station is Wedding Central, a 10-minute walk from the venue.</li>
        </ul>
    </section>

    <section id="what-to-do" class="section">
        <h2 class="content-sk">Čo robiť</h2>
        <h2 class="content-en">What to Do</h2>
        <p class="content-sk">Preskúmajte tieto zaujímavé aktivity počas pobytu:</p>
        <p class="content-en">Explore these exciting things to do while you’re here:</p>
        <ul class="details-list content-sk">
            <li>Navštívte miestne svadobné trhy v blízkosti.</li>
            <li>Preskúmajte známe historické pamiatky mesta.</li>
            <li>Užite si miestne kaviarne a reštaurácie pred svadbou.</li>
        </ul>
        <ul class="details-list content-en">
            <li>Visit the local wedding markets nearby.</li>
            <li>Explore the city’s famous historical landmarks.</li>
            <li>Enjoy local cafes and restaurants for a pre-wedding treat.</li>
        </ul>
    </section>

    <section id="timeline" class="section">
        <h2 class="content-sk">Harmonogram</h2>
        <h2 class="content-en">Wedding Timeline</h2>
        <ul class="details-list content-sk">
            <li>16:00 – Príchod hostí a uvítací drink</li>
            <li>16:30 – Začiatok obradu</li>
            <li>18:00 – Svadobná večera</li>
            <li>20:00 – Prvý tanec a párty</li>
            <li>23:00 – Ukončenie udalosti</li>
        </ul>
        <ul class="details-list content-en">
            <li>4:00 PM – Guests Arrive & Welcome Drinks</li>
            <li>4:30 PM – Ceremony Begins</li>
            <li>6:00 PM – Reception Dinner</li>
            <li>8:00 PM – First Dance & Party</li>
            <li>11:00 PM – Event Ends</li>
        </ul>
    </section>

    <section id="rsvp" class="section">
        <h2 class="content-sk">RSVP</h2>
        <h2 class="content-en">RSVP</h2>
        <p class="content-sk">Prosím potvrďte svoju účasť vyplnením nižšie uvedeného formulára:</p>
        <p class="content-en">Please RSVP by filling out the form below:</p>
        <form action="#" method="POST">
            <input type="text" name="name" placeholder="Vaše meno" required class="content-sk">
            <input type="text" name="name" placeholder="Your Name" required class="content-en">
            <input type="email" name="email" placeholder="Váš e-mail" required class="content-sk">
            <input type="email" name="email" placeholder="Your Email" required class="content-en">
            <input type="number" name="guests" placeholder="Počet hostí" required class="content-sk">
            <input type="number" name="guests" placeholder="Number of Guests" required class="content-en">
            <button type="submit" class="button content-sk">Odoslať RSVP</button>
            <button type="submit" class="button content-en">Submit RSVP</button>
        </form>
    </section>

    <footer>
        <p class="content-sk">&copy; 2024 Naša Svadba. Všetky práva vyhradené.</p>
        <p class="content-en">&copy; 2024 Our Wedding. All rights reserved.</p>
    </footer>

    <script>
        // Get the flag elements and all content sections
        const skFlag = document.getElementById('sk-flag');
        const enFlag = document.getElementById('en-flag');
        const skContent = document.querySelectorAll('.content-sk');
        const enContent = document.querySelectorAll('.content-en');

        // Function to show Slovak content and hide English content
        skFlag.addEventListener('click', () => {
            skContent.forEach(item => item.style.display = 'block');
            enContent.forEach(item => item.style.display = 'none');
        });

        // Function to show English content and hide Slovak content
        enFlag.addEventListener('click', () => {
            enContent.forEach(item => item.style.display = 'block');
            skContent.forEach(item => item.style.display = 'none');
        });
    </script>

</body>
</html>