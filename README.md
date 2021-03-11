![cooltext378252683269641-removebg-preview](https://user-images.githubusercontent.com/72200995/110104365-5c828480-7da7-11eb-8aa6-4867c4a71823.png)

Lo scopo del gioco è quello di allenare l'equilibrio di una persona.
Rimanendo fermi sul posto bisogna infatti spostare il busto a destra e a sinistra per schivare degli ostacoli che compaiono sullo schermo
Il giocatore deve essere munito di un marker di colore rosso da attacare sul petto.
Il gioco sfrutta due librerie: OpenCV e PyGame.


# Software utilizzati
![alt text](https://user-images.githubusercontent.com/61046970/110098840-ec710000-7da0-11eb-83b8-0da86a2f2e64.png):     https://www.pygame.org/news

![opencv](https://user-images.githubusercontent.com/61046970/110098845-eda22d00-7da0-11eb-9bb6-d17dafc2c0d3.png):     https://opencv.org/

Gli Sprites e le PixelArt sono state disegnate con:
https://make8bitart.com/

https://github.com/4arob-error404/Immagini

# Funzionamento gioco:

Tramite opencv, libreria che utilizza la fotocamera del nostro dispositivo, si rilevano gli oggetti di colore rosso e si ricavano le coordinate di questi ultimi.

![schermateVideocamera](https://user-images.githubusercontent.com/61046970/110099029-23dfac80-7da1-11eb-9668-405f0178cd51.png)

Sfruttando le coordinate rilevate si sposta una macchina sull'asse delle ascisse tramite la libreria PyGame.
Gli ostacoli da evitare sono file di macchine che vengono generate sullo schermo in posizioni e con skins randomiche.
Ogni volta che il giocatore supera un ostacolo viene incrementato il punteggio, ma ATTENZIONE: la velocità degli ostacoli aumenta!!!

![immagineGioco](https://user-images.githubusercontent.com/61046970/110769162-300fb200-8258-11eb-8c44-b902fa0e04b3.png)

Sei troppo lento? Non ti preoccupare, abbiamo pensato che magari potrebbe farti comodo un po' di turbo.

![Turbo](https://user-images.githubusercontent.com/61046970/110602632-7ac0f980-8186-11eb-9d46-24f1dd4eec3f.png) 
![turbo](https://user-images.githubusercontent.com/61046970/110769245-40c02800-8258-11eb-8125-62861bb0d9e3.png)

Il punteggio viene calcolato in base alle file di macchine che superi e in base alla quantità di turbo che sfrutti.

![punteggio](https://user-images.githubusercontent.com/61046970/110769210-39991a00-8258-11eb-8eb2-92f3ab046dc2.png)

Hai tre vite.

![vita](https://user-images.githubusercontent.com/61046970/110760420-fbe3c380-824e-11eb-99f0-e07c7e04e85e.png)

Ma occhio a non colpire gli ostacoli se non vuoi perdere!!!

![gameOver](https://user-images.githubusercontent.com/61046970/110099083-335ef580-7da1-11eb-90b5-28fecd024ed3.png)

# Componenti del gruppo:
1. La Valle Nicolò: team leader
2. Seimandi Alessandro: programmatore
3. Alladio Michele: programmatore
4. Forneris Samuele: grafico

# Ringraziamenti
IIT (Carlo Canali, Giacinto Barresi)

Associazione Italiana Sclerosi Multipla (Jessica Podda)

Università di Genova (Prof. Riccardo Berta)

Wondertech (Giuseppe Gioco, Ivan Carmosino)

