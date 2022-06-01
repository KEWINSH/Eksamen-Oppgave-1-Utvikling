# Eksamen-Oppgave-1-Utvikling
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Jeg startet med å lage en navigation-bar på toppen av siden med <nav> tagget og en av de 4 logoene jeg kunne velge mellom. 
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
nav class="navigation-bar">
        <img class="logo" src="/images/logo1.png">
        <a href="#">Bli Medlem</a>
        <a href="#">Kontakt Oss</a>
        <a href="#">Om Oss</a>
    </nav>
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Jeg støttet naturligvis på et problem med hvordan navigation-baren min så ut. Derfor addet jeg en god mende Css og en liten del flexbox for å gjøre nav baren min fin.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
 .navigation-bar {
    width: 100%; 
    height: 80px;
    border: solid black; 
}
.logo {
    vertical-align: top;
    width: 250px;
    height: 50px;
    margin-left: 20px;
    margin-top: 15px;    
}
.navigation-bar > a {
    float: right;
    vertical-align: top;
    margin-right: 20px;
    height: 80px;        
    line-height: 80px;   
}
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Når Navigation-baren min var ferigjort kunne jeg starte på hovedinnholdet på nettsiden. Som var en guide på hva HTML, CSS og JS er. Jeg startet på dette med en Container og 3 <Div> bokser. I disse div boksene skulle jeg ha en rekke tags <Img> <H1> <P>. <Img> tagene skulle ha 3 forsjellige bilder av HTML, CSS og JS logoene. <p> og <H1> skulle bare ha Lorem Ipsum. 
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
    <div class="container"> 
        <div class="Boxene"> 
           <img src="/images/html.png"> 
           <h1>What it HTML?</h1>
           <p> (╯°□°）╯︵ ┻━┻ Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ratione veniam neque expedita quas voluptas quam odit nam ea soluta recusandae.</p> 
        </div> 
        <div class="Boxene"> 
           <img src="/images/css.png"> 
            <h1>What is CSS?</h1>
           <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic mollitia natus neque soluta ¯\_(ツ)_/¯ tenetur blanditiis.</p>
        </div> 
        <div class="Boxene"> 
           <img src="/images/javascript.png "> 
           <h1>What is JavaScript?</h1>
           <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Kewin er Kul Repellat laboriosam ad dolore odio. Porro quo non amet dolore consequatur? Minus possimus illum odit blanditiis cum?</p> 
        </div> 
     </div> 
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Naturligvis ser alt hoved innholdet på nettsiden veldig rottete ut uten litt CSS. Så det var det neste og siste steget for denne nettsiden. Cssen min var veldig simpel og veldig effektiv. 
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
  .container {
    display: flex;
 }
 .Boxene {
    flex:1;
    text-align: center;
    margin: 5px;
    margin-top: 15vh;
 }
 img {
    width: 128px;
 }
