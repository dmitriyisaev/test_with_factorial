GET  /       все факториалы - готовые и в работе


GET  /factorial?number=<num>  где num - число, для которого необходимо посчитать факториал


GET  /websocket/factorial?number=<num>  где num - число, для которого необходимо посчитать факториал. 
Выдает все посчитанные факториалы и обновляет их по соккету. 
//TODO если гонять по соккету большие портянки данных соккет отваливается, а восстановление коннекта не написано.
