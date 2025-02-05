# machine-learning-project  
  
Più bassa media degli MSE (deve essere il più vicino possibile a zero):  
Più bassa deviazione standard degli MSE (deve essere il più vicino possibile a zero):  

Massimo batch size su GPU: 8192  
Massimo batch size su CPU: 2048  

TODO:  
- Subito dopo il training, salvare i pesi del modello in un file su Google Drive. Prima del training, controllare che un file di pesi sia disponibile. Se disponibile, carica i pesi e salta il training. Altrimenti, esegui il training.
- Chiedere al prof. Asperti se è possibile consegnare uno zip/tar.gz con il notebook (eseguito e con gli output visibili) e il file dei pesi del modello. Digli che lo vorresti fare così che il prof possa eseguire il notebook saltando il training, se necessario.
- (Se possibile) Prova a usare KerasTuner per l'ottimizzazione degli iper-parametri della rete neurale.
