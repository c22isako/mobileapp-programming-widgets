
# Rapport

**Skriv din rapport här!**

_Du kan ta bort all text som finns sedan tidigare_.

## Följande grundsyn gäller dugga-svar:

- Ett kortfattat svar är att föredra. Svar som är längre än en sida text (skärmdumpar och programkod exkluderat) är onödigt långt.
- Svaret skall ha minst en snutt programkod.
- Svaret skall inkludera en kort övergripande förklarande text som redogör för vad respektive snutt programkod gör eller som svarar på annan teorifråga.
- Svaret skall ha minst en skärmdump. Skärmdumpar skall illustrera exekvering av relevant programkod. Eventuell text i skärmdumpar måste vara läsbar.
- I de fall detta efterfrågas, dela upp delar av ditt svar i för- och nackdelar. Dina för- respektive nackdelar skall vara i form av punktlistor med kortare stycken (3-4 meningar).

Programkod ska se ut som exemplet nedan. Koden måste vara korrekt indenterad då den blir lättare att läsa vilket gör det lättare att hitta syntaktiska fel.

LinearLayout

Lade till en LinearLayout via kodraden nedan.
```
<LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical"
        tools:ignore="MissingConstraints">
```
Lade till en knapp via "<Button", vilket gav mig ett par options. Dessa bygdes på under projektets gång, där de markanta kodraderna
kan sägas vara de nedan (notera att det finns mer kod till knappen). Här flyttar vi knappen till "mitten", ändrar dess bakgrund till blått,
Sätter text-färgen i knappen till vit, samt ger knappen ett id.
```
            android:layout_marginHorizontal="150dp"
            android:background="#68A7BD"
            android:textColor="@android:color/white"
            android:id="@+id/theButton"
```
Detta id:t används sedan i MainActivity för att registrera knapptryck via en 
listener. (for the sake of future implementation)
```
springButton.setOnClickListener(new View.OnClickListener() { ... }
```

Lade till en inteagerbar text-flik, genom "<EditText". Även här använde jag mig utav margin för att 



Lade till en png genom att gå in på View > Tool windows > Resource manager, och drog sedan in png:n till fönstret.
Efter detta skrev jag in pngs filväg (innehållande namnet) i ImageView, genom kodraden nedan. Notera att namnet är art.
```
app:srcCompat="@drawable/art"
```
Då Bilden och appens bakgrund inte passade, passade jag även på att ändra bakgrundsfärg på appen genom att lägga till kodraden
nedan till LinearLayout.
```
android:background="#99D9EA"
```
Bilder läggs i samma mapp som markdown-filen.

![](android.png)

Läs gärna:

- Boulos, M.N.K., Warren, J., Gong, J. & Yue, P. (2010) Web GIS in practice VIII: HTML5 and the canvas element for interactive online mapping. International journal of health geographics 9, 14. Shin, Y. &
- Wunsche, B.C. (2013) A smartphone-based golf simulation exercise game for supporting arthritis patients. 2013 28th International Conference of Image and Vision Computing New Zealand (IVCNZ), IEEE, pp. 459–464.
- Wohlin, C., Runeson, P., Höst, M., Ohlsson, M.C., Regnell, B., Wesslén, A. (2012) Experimentation in Software Engineering, Berlin, Heidelberg: Springer Berlin Heidelberg.
