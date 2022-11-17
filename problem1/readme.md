
##Problema 1

Bob sta cercando di consegnare dei pacchi in un grande condominio, ma non riesce a trovare il piano giusto: le indicazioni ricevute sono un po' confuse. Inizia dal piano terra (piano `0`) e segue le istruzioni un personaggio alla volta.

Una parentesi di apertura, `(`, significa che deve salire di un piano, mentre una parentesi di chiusura, `)`, significa che deve scendere di un piano.

Il condominio è molto alto e il seminterrato è molto profondo; non troverà mai il piano superiore o inferiore.

**Ad esempio:**
```
(()) e ()() danno entrambi come risultato il piano 0.
((( e (()(()( danno entrambi come risultato il piano 3.
))((((( anch'esso dà come risultato il piano 3.
()) e ))( entrambi danno come risultato il piano -1 (il primo livello interrato).
))) e )())()) risultano entrambi al piano -3.
```

A che piano portano le istruzioni per Bob?