# Project-Web<!DOCTYPE html>
<html lang="nl">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>Login</title>
		<link rel="stylesheet" href="css/stylelogin.css">
		
	</head>
	<body>
		<header>
            <img src="assets/image/logo.png" alt="Logo van de NS">
            <h1>NS Reisverhalen</h1>


            <nav>
                

                <ul>
                    <li><a href="index.html">Overzicht</a></li>
                    <li><a href="index.html">Mijn lijst</a></li>
                </ul>
            </nav>

           
            <input type="text" name="zoeken" placeholder="Jouw zoekopdracht">
            <img src="assets/image/zoeken_icon.png" alt="zoeken icoon">
            <a href="login.html"><img src="assets/image/login_icon.png" alt="login icoon"></a>
        </header>
	  <!-- <!Moet H1 zijn -->
		<main>
			
			<section>
				<h2>NS verhalen reist met je mee</h2>
				<form action="index.html">
					<fieldset>
						<legend>Aanmelden</legend>
						
						<div>
						<label for="email" class="login">E-mail</label>
						<input type="text" Id=email name="E-mail" title="E-mail adres" placeholder="vul hier je e-mail adres in">
						<label for="password" class="login">Wachtwoord</label>
						<input type="text" Id=password name="Wachtwoord" title="E-mail adres" placeholder="vul hier je wachtwoord in">
						</div>
						
					</fieldset>
					
					
					<button>Inloggen</button>
					
					
					<a href="register.html">Aanmelden?</a>
					<a href="popupfacebook.html">Aanmelden met Facebook</a>
				</form>
				
			</section>
			
		</main>
		 <footer>
            <a href="index.html">Overzicht</a>
            <a href="index.html">Terug</a>
        </footer>
	</body>
</html>
