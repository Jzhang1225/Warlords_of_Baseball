<html>
    <head>
        <title>Warlords of Baseball</title>
        <link rel="stylesheet" href="Warlords.css">
    </head>
    <body>
        <header>Warlords of Baseball by Position</header>
        <h1>Outfield</h1>
        <section class = outfield>
            <div id = left>
                Left Field
                <div class = 'pic'></div>
                <p>
                    Barry Bonds born July 24, 1964 has 162.7 WAR <br>
                    He has the third most WAR in MLB History <br><br>
                    Active leader is Brett Gardner with 44.3 WAR
                </p>
            </div>
            <div id = center>
                Center Field
                <div class = 'pic'></div>
                <p>
                    Willie Mays born May 6, 1931 has 156.1 WAR <br><br>
                    Active leader is Mike Trout with 76.1 WAR
                </p>
            </div>
            <div id = right>
                Right Field
                <div class = 'pic'></div>
                <p>
                    Babe Ruth born February 6, 1895 has 182.5 WAR <br>
                    He has the most WAR in MLB history <br><br>
                    Active leader is Mookie Betts with 50.0 WAR
                </p>
            </div>
        </section>
        <h1>Middle Infield</h1>
        <section class = middle_infield>
            <div id = short>
                Shortstop
                <div class = 'pic'></div>
                <p>
                    Honus Wagner born February 24, 1874 has 130.8 WAR <br><br>
                    Active leader is Andrelton Simmons with 37.3 WAR
                </p>
            </div>
            <div id = second>
                Second Base
                <div class = 'pic'></div>
                <p>
                    Rogers Hornsby born April 27, 1896 has 127.3 WAR <br><br>
                    Active leader is Robinson Cano with 69.6 WAR
                </p>
            </div>
        </section>
        <h1>Corner Infield and Pitcher</h1>
        <section class = corner_pitcher>
            <div id = third>
                Third Base
                <div class = 'pic'></div>
                <p>
                    Mike Schmidt born September 27, 1949 has 106.9 WAR <br><br>
                    Active leader is Evan Longoria with 57.4 WAR
                </p>
            </div>
            <div id = pitcher>
                Pitcher
                <div class = 'pic'></div>
                <p>
                    Walter Johnson born November 6, 1887 has 164.8 WAR <br>
                    He has the second most WAR in MLB History <br><br>
                    Active leader is Zack Greinke with 73.1 WAR
                </p>
            </div>
            <div id = first>
                First Base
                <div class = 'pic'></div>
                <p>
                    Lou Gehrig born June 19, 1903 has 113.7 WAR <br><br>
                    Active leader is Albert Pujols with 99.6 WAR
                </p>
            </div>
        </section>
        <h1>Catcher and DH</h1>
        <section class = catcher_dh>
            <div id = dh>
                DH
                <div class = 'pic'></div>
                <p>
                    Edgar Martinez born January 2, 1963 has 58.4 WAR <br><br>
                    Active leader is Shohei Ohtani with 10.2 WAR
                </p>
            </div>
            <div id = catcher>
                Catcher
                <div class = 'pic'></div>
                <p>
                    Johnny Bench born December 7, 1947 has 75.1 WAR <br><br>
                    Active leader is Yadier Molina with 42.1 WAR
                </p>
            </div>
        </section>
    </body>
</html>
*{
    box-sizing: border-box;
    text-align: Center;
}
body{
    font-family: 'Times New Roman', Times, serif;
    font-size: 20px;
}
header{
    font-weight: bold;
    font-size: 50px;
}
h1{
    text-decoration: underline;
}
section > div{
    display: inline-block;
    width: calc(100%/4);
    margin: 1rem;
    border: solid 1px black
}
section > div> .pic{
    background-size: cover;
}
.pic{
    background-size: 50%;
    height: 200px;
}
#left{
    background-color: brown;
}
#left > .pic{
    background-image: url(BarryBonds.jpeg);
}
#right{
    background-color: gold;
}
#right > .pic{
    background-image: url(BabeRuth.jpeg);
}
#center > .pic{
    background-image: url(WillieMays.jpeg);
}
#short > .pic{
    background-image: url(HonusWagner.jpeg);
}
#second > .pic{
    background-image: url(RogersHornsby.jpeg);
}
#third > .pic{
    background-image: url(MikeSchmidt.png);
}
#first > .pic{
    background-image: url(LouGehrig.jpeg);
}
#pitcher{
    background-color: greenyellow;  
}
#pitcher > .pic{
    background-image: url(WalterJohnson.jpeg);
}
#catcher > .pic{
    background-image: url(JohnnyBench.jpeg);
}
#dh > .pic{
    background-image: url(EdgarMartinez.png);
}
