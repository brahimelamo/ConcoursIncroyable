# ConcoursIncroyable
Le meilleur
<div>
    <h1>Concours pour Gagner un Voyage à New York !</h1>
    <p>Participez à notre concours pour avoir la chance de gagner un voyage à New York, rencontrer Trump et faire une soirée inoubliable avec lui !</p>

    <label for="fullName">Nom et Prénom :</label>
    <input type="text" id="fullName" name="fullName" placeholder="Nom Prénom" required><br><br>

    <label for="age">Âge :</label>
    <input type="number" id="age" name="age" min="16" required><br><br>

    <label for="numberChoice">Choisir un numéro entre 1 et 10 :</label>
    <input type="number" id="numberChoice" name="numberChoice" min="1" max="10" required><br><br>

    <button onclick="submitForm()">Se Connecter</button>

    <div id="result">
        <!-- Le message du concours apparaîtra ici -->
    </div>
</div>
