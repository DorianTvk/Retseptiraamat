<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Retseptiraamat</title>
    <!-- Lisa Bootstrapi CSS-i link -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <!-- Lisa oma kohandatud CSS-i link -->
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background-color: #f2f2f2; /* Taustavärv */
        }
        .retsept {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.3); /* Lisa kaardi varjund */
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-primary">
        <a class="navbar-brand text-white" href="#">Retseptiraamat</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link text-white" href="#retsept1">Kanapasta</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-white" href="#retsept2">Caesari Salat</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-white" href="#retsept3">Õunakook</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Retsept 1 -->
    <div id="retsept1" class="container mt-4 retsept">
        <h2>Kanapasta</h2>
        <p>Lihtne ja maitsvate kanapasta retsept.</p>
        <h3>Koostisosad:</h3>
        <ul>
            <li>300g spagette</li>
            <li>250g kanarinda</li>
            <li>1 sibul</li>
            <li>2 küüslauguküünt</li>
            <li>200ml koort</li>
            <li>50g riivitud parmesani juustu</li>
            <li>Õli, sool, pipar</li>
        </ul>
        <h3>Valmistamine:</h3>
        <ol>
            <li>Keeda spagetid vastavalt pakendil olevale juhendile.</li>
            <li>Kuumuta pannil õli ja prae kanarinda, kuni see on läbinisti küps.</li>
            <li>Lisa hakitud sibul ja küüslauk, ning prae veel paar minutit.</li>
            <li>Vala juurde koor ja riivitud parmesani juust, sega hästi ning lase kastmel podiseda paar minutit.</li>
            <li>Maitsesta soola ja pipraga.</li>
            <li>Vala kaste keedetud spagettidele ja sega läbi.</li>
            <li>Serveeri soojalt.</li>
        </ol>
    </div>

    <!-- Retsept 2 -->
    <div id="retsept2" class="container mt-4 retsept">
        <h2>Caesari Salat</h2>
        <p>Classic Caesari salati retsept.</p>
        <h3>Koostisosad:</h3>
        <ul>
            <li>2 pead jääsalatit</li>
            <li>2 kanarinda</li>
            <li>1 tass krutoonid</li>
            <li>50g riivitud parmesani juustu</li>
            <li>Caesari kaste (valmis või omatehtud)</li>
            <li>Sool, pipar</li>
        </ul>
        <h3>Valmistamine:</h3>
        <ol>
            <li>Grilli kanarinda, kuni see on täielikult küps ja kuldpruun.</li>
            <li>Lõika kanarind väikesteks tükkideks.</li>
            <li>Rösti krutoonid kuldpruuniks.</li>
            <li>Peske ja rebitakse jääsalat väiksemateks tükkideks.</li>
            <li>Segage salat, grillitud kana, krutoonid ja riivitud parmesani juust suures kausis.</li>
            <li>Maitsesta soola, pipra ja Caesari kastmega.</li>
            <li>Segage hästi ja serveerige kohe.</li>
        </ol>
    </div>

    <!-- Retsept 3 -->
    <div id="retsept3" class="container mt-4 retsept">
        <h2>Õunakook</h2>
        <p>Maitsva õunakoogi retsept.</p>
        <h3>Koostisosad:</h3>
        <ul>
            <li>4 suurt õuna</li>
            <li>1 tass jahu</li>
            <li>1 tass suhkrut</li>
            <li>1 tl küpsetuspulbrit</li>
            <li>1 tl kaneeli</li>
            <li>1 muna</li>
            <li>1/2 tass sulavõid</li>
            <li>Vaniljekaste (valikuline)</li>
        </ul>
        <h3>Valmistamine:</h3>
        <ol>
            <li>Koori ja lõika õunad viiludeks.</li>
            <li>Sega omavahel jahu, suhkur, küpsetuspulber ja kaneel.</li>
            <li>Lisa lahtiklopitud muna ja sulavõi, sega ühtlaseks tainaks.</li>
            <li>Vala tainas küpsetusvormi põhja.</li>
            <li>Aseta õunaviilud taina peale.</li>
            <li>Küpseta eelsoojendatud ahjus 180 kraadi juures umbes 30-35 minutit, kuni kook on kuldpruun ja õunad pehmed.</li>
            <li>Serveeri vaniljekastmega.</li>
        </ol>
    </div>

    <!-- Lisa Bootstrapi JavaScripti ja jQuery skriptid -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
        
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Retseptiraamat</title>
    <!-- Lisa Bootstrapi CSS-i link -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <!-- Lisa oma kohandatud CSS-i link -->
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background-color: #aeefff; /* Helesinine taustavärv */
        }
        .retsept {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.3); /* Lisa kaardi varjund */
        }
    </style>
</head>
<body>
    <!-- Ülejäänud HTML sisu jääb samaks -->
    <!-- ... -->
</body>
</html>

