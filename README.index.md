# Project-Web

<!DOCTYPE html>
<html lang="nl">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <link rel="stylesheet" type="text/css" href="css/style.css">
        <title>NS Reisverhalen</title>
    </head>
    <body>
        <header>
            <img src="assets/image/logo.png" alt="Logo van de NS">
            <h1></h1>


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

        <section>
            <h1>NS verhalen reist met je mee</h1>
        </section>

        <aside>
            <h2>Filter opties</h2>

<form>
<fieldset>


<!--           vertreklocatie-->
                    <label for="input-search" class="filteren">Jouw vetrek locatie</label>

                        <input type="text" id=input-search name="invoer" title="vertreklocatie" placeholder="Typ uw vertreklocatie">



<!--     DEZE BUTTON MOET EIGENKIJK ZO:-->
        <input type="submit" value="Zoeken" id="resulaten-tonen">


 <!--    MAAR DE BUTTON WAS ZO:-->
<!--       <button type="submit" id="resulaten-tonen">Zoeken!</button> -->

<button>Meer opties</button>
                        <div id="options">



<!--Leesduur-->
            <label for="radio-leesduur" class="tijdkeuze">
            Filter op leesduur
</label>


      <input id="radio-leesduur0min" type="radio" name="changeOverTime" value="0">
      <label for="radio-leesduur0min" class="minuten">0 tot 5 min</label>


<input id="radio-leesduur5min" type="radio" name="changeOverTime" value="5">
       <label for="radio-leesduur5min" class="minuten">5 tot 10 min</label>

<input id="radio-leesduur10min" type="radio" name="changeOverTime" value="10">
    <label for="radio-leesduur10min" class="minuten"> 10 tot 15 min</label>

<!--Voorkeuren-->
<!--  Checkbox -->

<label for="Preferences" class="voorkeur">Voorkeuren</label>
<input type="checkbox" name="sorteren" value="ongelezen" ID="Preferences">Toon alleen ongelezen
<input type="checkbox" name="sorteer" value="goed beoordeelde" ID="Preferences">Toon alleen goed beoordeeld


     </div>

     </fieldset>

<!--

            DIT IS DE DROPDOWN VERSIE FILTEREN OP LEESDUUR
                    <label>
                        Filter op leesduur
                            <label for="time-input" class="timebutton_inputlabel">
                            <img src="assets/image/login_icon.png" alt="login icoon">

                    <select>
                            <option value="1">0-5 min</option>
                            <option value="2">5-10 min</option>
                            <option value="3">10-15 min</option>
                        </select>
                    </label>
-->

 </form>
    </aside>
        <main>
            <section>
                <h2>Uitgelicht</h2>
            </section>

                <article>
                    <h3>Jeroen Krabbé</h3>
                    <p>Op het stationsplein stap ik de bus uit. Heb ik al jaren niet meer in gezeten, in de bus. De mensen doen hun best om niet naar me te kijken. Maar allemaal kijken ze toch. Stiekem. Ik hoor ze fluisteren. ‘Kijk, daar gaat Jeroen Krabbé. De grote acteur/regisseur/schilder.’ ... 
                    </p>
                    <footer>
                        <span>3 min</span>
                        <a href="index.html">Bekijk dit verhaal</a>
                        <div>
                            <img src="assets/image/download_icon.png" alt="downloaden">
                            <img src="assets/image/opslaan_icon.png" alt="opslaan">
                        </div>
                    </footer>

                </article>

                <article>
                <h3>Geert Wilders</h3>
                <p>Een tsunami van forenzen loopt van en naar het Centraal Station in Amsterdam. Ik ben net uit bus 21 gestapt, een prachtige, roomblanke bus 21 die ontsierd werd door foeilelijke kopvodden waaronder potentiële terroristenvrouwtjes met hun onderdrukte gezichtjes verveeld naar buiten zaten te staren. Het is dat ik mijn bodyguards bij me had...</p>
                <footer>
                        <span>3 min</span>
                        <a href="index.html">Bekijk dit verhaal</a>
                        <div>
                         <img src="assets/image/download_icon.png" alt="downloaden">
                            <img src="assets/image/opslaan_icon.png" alt="opslaan">
                        </div>
                    </footer>
                </article>

                <article>
                <h3>De passie van Max</h3>
                <p>Ik klamp me vast aan het wagentje van mijn zoon. Hij slaapt. De busrit heb ik overleefd. Het is rond het middaguur, de mensen lopen langs ons heen, zonder ons op te merken. Niemand steekt een hand uit. Ik sleep me voort. De pijn zo goed als mogelijk negerend...  </p>
                <footer>
                        <span>3 min</span>
                        <a href="mijnverhalen_lijden.html">Bekijk dit verhaal</a>
                        <div>
                           <img src="assets/image/download_icon.png" alt="downloaden">
                            <img src="assets/image/opslaan_icon.png" alt="opslaan">
                        </div>
                    </footer>
                </article>
                
                <section>
                <h2>Aangepast op jouw reisgedrag</h2>
            </section>

                <article>
                <h3>De verwarde man</h3>
                <footer>3 min</footer>
                <p>Vroem. Tuut tuut. Whèèèh!! Die! Die! Whèèèh! Die! Die! Hjumhjumhjum. Zzzzzzzzzz.* Zzzzzzz.* Zzzzzzz. Hjumhjumhjum. Zzzzzzz. Grumbl. Huh? Whèèèh. Die! Die! Papa? Hjmwhumwhum. Boe?Boe? Hjmwhumwhum. Whèèèh!!! Die!* Zjjoemmm. Vroem. Tuut tuut. Schoe!* * We zitten in zo’n enorme auto, samen met een aantal andere mensen. Ik voel dat ik elk moment in slaap kan vallen. Ik […]</p>
                <footer>
                        <span>3 min</span>
                        <a href="mijnverhalen_lijden.html">Bekijk dit verhaal</a>
                        <div>
                           <img src="assets/image/download_icon.png" alt="downloaden">
                            <img src="assets/image/opslaan_icon.png" alt="opslaan">
                        </div>
                    </footer>
                </article>
            

                <article>
                <h3>Het kind</h3>
                <footer>3 min</footer>
                <p>Vroem. Tuut tuut. Whèèèh!! Die! Die! Whèèèh! Die! Die! Hjumhjumhjum. Zzzzzzzzzz.* Zzzzzzz.* Zzzzzzz. Hjumhjumhjum. Zzzzzzz. Grumbl. Huh? Whèèèh. Die! Die! Papa? Hjmwhumwhum. Boe?Boe? Hjmwhumwhum. Whèèèh!!! Die!* Zjjoemmm. Vroem. Tuut tuut. Schoe!* * We zitten in zo’n enorme auto, samen met een aantal andere mensen. Ik voel dat ik elk moment in slaap kan vallen. Ik […]</p>
                <footer>
                        <span>3 min</span>
                        <a href="mijnverhalen_lijden.html">Bekijk dit verhaal</a>
                        <div>
                           <img src="assets/image/download_icon.png" alt="downloaden">
                            <img src="assets/image/opslaan_icon.png" alt="opslaan">
                        </div>
                    </footer>
                </article>

                <article>
                <h3>Zoon</h3>
                <footer>3 min</footer>
                <p>Vroem. Tuut tuut. Whèèèh!! Die! Die! Whèèèh! Die! Die! Hjumhjumhjum. Zzzzzzzzzz.* Zzzzzzz.* Zzzzzzz. Hjumhjumhjum. Zzzzzzz. Grumbl. Huh? Whèèèh. Die! Die! Papa? Hjmwhumwhum. Boe?Boe? Hjmwhumwhum. Whèèèh!!! Die!* Zjjoemmm. Vroem. Tuut tuut. Schoe!* * We zitten in zo’n enorme auto, samen met een aantal andere mensen. Ik voel dat ik elk moment in slaap kan vallen. Ik […]</p>
                <footer>
                        <span>3 min</span>
                        <a href="mijnverhalen_lijden.html">Bekijk dit verhaal</a>
                        <div>
                           <img src="assets/image/download_icon.png" alt="downloaden">
                            <img src="assets/image/opslaan_icon.png" alt="opslaan">
                        </div>
                    </footer>
                
                </article>



        </main>
        <footer>
         <a href="index.html">Overzicht</a>
        <a href="http://www.ns.ns">Naar de NS-website</a>
        </footer>
</body>
<script src="js/index.js"></script>
</html>
