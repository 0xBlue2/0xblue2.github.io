<p id = "area"></p>
<script>
    var Info = {
        height: 300,
        width: 700,
        color: "#c5c5c5",
        j2sPath: "/jsmol/j2s",
        defaultModel: ":water",
        serverURL: "https://chemapps.stolaf.edu/jmol/jsmol/php/jsmol.php",
        script: "null",
        src: "null",
    }
    document.addEventListener('DOMContentLoaded', (event) => {
        delete Jmol._tracker
        document.getElementById("area").innerHTML = Jmol.getAppletHtml("myJmol", Info)
    });

</script>