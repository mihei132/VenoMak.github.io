#VenoMak
VenoMak
<html>

<head>

    <style>
        body{
            margin: 0;
            height: 100%;
            background: url(VenomAvaaa.png);
            background-size: cover;
        }
        table{
            background-color: rgba(13, 22, 99, 0);
        }
        p {
            font-size: 16pt;
        }
        p{
            font-family: Arial, Helvetica, sans-serif;
            background-color: rgba(255, 255, 255, 0);
            color: rgb(253, 253, 253);
        }
        h2{
            font-family:monospace;
            background-color: rgb(255, 255, 255);
        }
        button{
            font-size: 20px;
            background-color: rgb(0, 0, 0);
            color:white;
            border: none;
            padding: 10px 15px;
            border-radius: 15px;
            cursor: pointer;
            transition: 1.0s;
        }
        .button:hover{
            background-color: rgba(255, 255, 255, 0.342);
            color: black;
        }
    </style>

<script>
    function toLizards(){
        const mySite = document.getElementById('info');
        mySite.src = 'VenomViki.html';
    }
    function toMain(){
        const mySite = document.getElementById('info');
        mySite.src = 'VonoMak.html';
    }
    function toAbout(){
        const mySite = document.getElementById('info');
        mySite.src = 'About.html';
    }

</script>
</head>

<body>

<table width = 100% height = "100%">
<tr>
    <td width="15%" height = "20%" align=center><img src="Venom.png" width="80%"></td>
    <td width="100%" align="center"><p><big><big><big><big><big><big><big><big>Кто такой</big></big></big></big></big></big></big></big> <br> <big><big><big><big>Venom?</big></big></big></big></p></td>
</tr>
<tr>
    <td align="right">
        <br>
        <button onclick="toMain()" class = "button">Главная страница</button><br> <br>
        <button onclick="toLizards()" class = "button">Расширенная информация</button><br><br>
        <button onclick="toAbout()" class = "button">Об атворе</button><br><br>
        
    </td>

    <td><iframe id="info" src="VonoMak.html" width="100%" height="100%"></iframe></td>

</tr>
<tr><td colspan="2" align="center">Выполнили Михеев Д.К. и Каратаскова К.В.</td></tr>

</table>

</body>

</html>
