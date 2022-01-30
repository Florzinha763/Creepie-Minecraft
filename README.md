# Creepie-Minecraft
Creepie Minecraft
<canvas width="600" height="400"></canvas>

<script>
    var tela = document.querySelector('canvas');
    var pincel = tela.getContext('2d');

    /*Head*/
    pincel.fillStyle = 'darkgreen';
    pincel.fillRect(200,50,350,300);

    /*Eyes*/
    pincel.fillStyle = 'black';
    pincel.fillRect(250, 110, 90, 90);
    pincel.fillRect(410, 110, 90, 90);

    /*Nose*/
    pincel.fillRect(340, 200, 70, 100);

    /*Mouth*/
    pincel.fillRect(300, 240, 40, 110);
    pincel.fillRect(410, 240, 40, 110);    
</script>
