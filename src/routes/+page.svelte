<script>
    
    $:  screen = "1";
    let screen1 = "block";
    let screen2 = "none";
    let screen3 = "none";
    function changeScreen(){
        if(screen == "1"){
            screen1 = "none";
            screen2 = "block";
            screen3 = "none";
            screen = "2";
        }else if(screen == "2"){
            screen1 = "none";
            screen2 = "none";
            screen3 = "block";
            screen = "3";
        }
    }
</script>
<div class="screen1" style="display:{screen1}">
    <h1 class="heading">MONSOON FOOTBALL LEAGUE</h1>
    <img src="https://cdn.discordapp.com/attachments/996128745473708032/1114492983258140742/WhatsApp_Image_2023-06-02_at_16.30.53.jpg" alt="">
<button  class="main-button" on:click="{()=>{ changeScreen()}}">Lets play!</button>

</div>
<div class="screen2" style="display: {screen2};">
    <h1 class="heading2">About us</h1>
    <p class="maintext">The Monsoon League offers a
unique opportunity to participate
in short-format amateur sports
leagues that foster collaboration and
mmunity building. With a focus on
per localized events, participants
an connect with like-minded
individuals who share their passion
for competitive sports. TML
provides a platform for individuals
to come together and play in a fun
and supportive environment. As
part of a growing and enthusiastic
community, participants can expect
to make lasting connections and
build relationships with other sports
enthusiasts. Join MONSOON league
and experience the excitement
of competitive sports in a new
and innovative way.</p>
    <a class="secondary-btn" href="https://forms.gle/8nibKAzKoKxfEc4z7" target="_blank">Register</a>
</div>

<style>
.screen1{
    position: absolute;
    top: 0;
    left: 0;
    background-image: url("https://cdn.discordapp.com/attachments/996128745473708032/1114492983027433512/WhatsApp_Image_2023-06-02_at_16.30.20.jpg");
    height: 100%;
    width: 100%;
}
.screen2{
    position: absolute;
    top: 0;
    left: 0;
    background-image: url("https://cdn.discordapp.com/attachments/996128745473708032/1114492983027433512/WhatsApp_Image_2023-06-02_at_16.30.20.jpg");
    height: 100%;
    width: 100%;
}

.main-button{
    position: absolute;
    margin-left: auto;
    background-color:#dacbff;
    color:#8975b7;
    font-size: 20px;
    left: 50%;
    transform: translate(-50%, -50%);
    bottom:10%;
    height: 50px;
    width: 150px;
    border-radius: 20px;
}
img{
    height: 200px;
    width: 200px;
    border-radius: 100%;
    position: absolute;
    left: 50%;
    transform: translate(-50%, -50%);
    bottom: 15%;
}
.heading{
    position: absolute;
    left: 50%;
    text-align: center;
    transform: translate(-50%, -50%);
    bottom: 46%;
    color: white;
    font-size: 50px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.secondary-btn{
    position: absolute;

    background-color:#dacbff;
    color:#8975b7;
    font-size: 25px;
    left: 50%;
    transform: translate(-50%, -50%);
    bottom:5%;
    height: 50px;
    width: 150px;
    border-radius: 20px;
    text-align: center;
    vertical-align: middle;
    line-height: 50px;
    text-decoration: none;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.heading2{
    padding-left:15px;
    padding-right: 15px;
    color: white;
    font-size: 30px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.maintext{
    color: white;
    font-size: 17px;
    padding-left:15px;
    padding-right: 15px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    text-align: left;
}
</style>