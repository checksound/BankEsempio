# ESEMPIO BANCA

Nel package [unsynch](./src/main/java/unsynch) c'è la versione non sincronizzata in cui si vede che si verifica la race condition.

Nel package [synch](./src/main/java/synch) c'è la versione che utilizza 
`java.util.concurrent.locks.Lock` e `java.util.concurrent.locks.Condition`.

Nel package [synch2](./src/main/java/synch2) c'è la versione che utilizza `synchronized`, `wait` e `notify`.
