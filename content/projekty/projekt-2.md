---
date: 2025-01-20
title: "Individuální semestrální projekt, část druhá"
---
<html>
<head>
  <style>
    .basic-text {
      font-size: 20px;
      text-align: center;
      margin: 20px;
    }
  figcaption {
    font-size: 12px;
    color: gray;
    text-align: center;
  }
  </style>
</head>
<body>  
    <div class="basic-text">
        <h1>Přídavný motorizovaný zoom na fotoaparát
        </h1>
        <p>Konec období pro práci na projektech je už za rohem, takže je třeba zdokumentovat aktuální, téměř zfinalizovaný stav našich semestrálních projektů. Po opožděném startu jsem v posledních týdnech konečně opustil fázi plánování a pustil jsem se do stádia testování fyzického prototypu.
        </p>
        <figure>
            <img src="https://267962.github.io/267962_ZPC_2025/images/proj1.jpg" alt="">
             <figcaption></figcaption>
        </figure> 
        <p>Před modelováním jednotlivých dílů a tiskem na 3D tiskárně, bylo ještě nutné vyzkoušet zapojení elektrického obvodu. Hlavními komponenty jsou: Arduino Nano, kontinuální servo MG995, joystick z PS2, dva dvoupólové páčkové spínače a senzor proudu ACS712. Napájení serva zajišťují 4 baterie typu AA v dolní části krabičky, Arduino je poháněno 9V baterií. Na základě velikostí a tvarů komponent byla navrhnuta krabička tak, aby vše kompaktně pojmula. Zbytek dílů se pak už vytvářel kolem této hlavní struktury.
        </p>
        <figure>
            <img src="https://267962.github.io/267962_ZPC_2025/images/proj2.jpg" alt="">
             <figcaption></figcaption>
        </figure>
        <p>Celkem se sestava skládá z osmi tištěných dílů: již zmíněná krabička, horní a dolní kryt, tyčka, kroužek pro upevnění serva, ozubené kolo na servu, ozubený kroužek na objektiv a přidržovací čelist. Přidržovač původně nebyl v plánu, ale testování ukázalo, že samotný stativový šroub nestačí na pevné udržení těla kamery. To znamená, že zařízení není možné snadno a okamžitě adaptovat na jiný fotoaparát, musí se přidělat příslušná vyhovující čelist.
        </p>
        <figure>
            <img src="https://267962.github.io/267962_ZPC_2025/images/proj3.jpg" alt="">
             <figcaption></figcaption>
        </figure>
        <p>Ovládání je řešeno jednoduchým joystickem omezeným na pohyb v jedné ose. Pod ním se nachází dvě páčky, pravá slouží k zapnutí a vypnutí, levá k spuštění poloautomatické funkce (zatím nefinalizovaná). Senzor proudu monitoruje zátěž serva a při detekci dorazu na objektivu vypne servo, aby se zamezilo poškození. Systém se tak sám reguluje a je snadné ho používat.
        </p>
        <figure>
            <img src="https://267962.github.io/267962_ZPC_2025/images/proj4.jpg" alt="">
             <figcaption></figcaption>
        </figure>
        <p>
        </p>
    </div>

</body>
</html>
