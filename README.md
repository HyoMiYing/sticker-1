Sticker
=======

Opis razreda igra
--------------------

V razredu igra so naslednje funkcije:  

1. move(vrstica v kateri so bile kate oduzete (int), število oduzetih kart (int)) vrne: 'Input is valid', če sta vrstica in število veljavna sicer pa 'Row invalid' ob naveljavni vrstici in 'Num invalid' ob neveljavnem številu oduzetih kart
2. end() - vrne:(če je igra končana True sicer pa False (boolean))
3. change_player() - zamenja igralca in ne vrne ničesar  

Razredne spremenjivke:  

1. position (list) - po vrsti število kart v posamezni vrstici
2. player (str) - 'player1' oz. 'player2'

Validacijske funkcije:

1. validation_num(row, num) -  Preveri ali je vnos številski, če ga lahko brez krajšanj pretvorimo v celo število (int) in če je v pravilnih mejah. Vrne stringa 'Num is valid' oz. 'Num invalid'
2. validation_row(row) -  Preveri ali je vnos številski, če ga lahko brez krajšanj pretvorimo v celo število (int) in če je v pravilnih mejah. Vrne stringa 'Row is valid' oz. 'Row invalid'




