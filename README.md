# machine-learning-project  
  
Più bassa media degli MSE (deve essere il più vicino possibile a zero):  
Più bassa deviazione standard degli MSE (deve essere il più vicino possibile a zero):  

Massimo batch size su GPU: 8192  
Massimo batch size su CPU: 2048  

TODO:  
- Subito dopo il training, salvare i pesi del modello in un file su GitHub. Prima del training, controllare che un file di pesi sia disponibile. Se disponibile, carica i pesi e salta il training. Altrimenti, esegui il training.
- (Se possibile) Prova a usare KerasTuner per l'ottimizzazione degli iper-parametri della rete neurale.
