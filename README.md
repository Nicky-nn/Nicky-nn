<!-- Incluye la acción GitHub Profile README -->
<details>
<summary>:zap: GitHub Stats</summary>

<!--START_SECTION:profile-readme-generator-->
<!--END_SECTION:profile-readme-generator-->

<!-- Calcula y muestra la edad -->
<script>
    // Fecha de nacimiento de Nick Russell
    var fechaNacimiento = new Date('2003-08-29');

    // Fecha actual
    var fechaActual = new Date();

    // Calcula la edad
    var edad = fechaActual.getFullYear() - fechaNacimiento.getFullYear();

    // Ajusta la edad si aún no ha pasado su cumpleaños este año
    if (fechaActual.getMonth() < fechaNacimiento.getMonth() || (fechaActual.getMonth() === fechaNacimiento.getMonth() && fechaActual.getDate() < fechaNacimiento.getDate())) {
        edad--;
    }

    // Imprime la edad
    document.write("<p>La edad de Nick Russell es: " + edad + " años.</p>");

    // Calcula y muestra el progreso del año
    var diasEnElAno = 365; // Cambia esto si es un año bisiesto
    var progresoAnual = ((fechaActual - new Date(fechaActual.getFullYear(), 0, 1)) / (1000 * 60 * 60 * 24)) / diasEnElAno * 100;
    document.write("<p>⏳ **Year Progress** { " + "■".repeat(Math.floor(progresoAnual)) + "▢".repeat(100 - Math.floor(progresoAnual)) + " } " + progresoAnual.toFixed(2) + " % as on ⏰ " + fechaActual.toDateString() + "</p>");
</script>

---

<h3 align="left">Connect with me:</h3>
<p align="center">
<a href="https://dev.to/nickynn" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/devto.svg" alt="nickynn" height="30" width="40" /></a>
<a href="https://twitter.com/nick_russell_in" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="nick_russell_in" height="30" width="40" /></a>
<a href="https://linkedin.com/in/nickynn/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="nickynn/" height="30" width="40" /></a>
</p>

</details>
