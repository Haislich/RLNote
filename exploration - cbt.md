multi armed non ha stati

data un'azione c'è una reward si ricomincia.

Introduciamo uno stato, contextual bandit, l'agente deve scegliere un'azione basata sul contesto, dato dallo stato.
Tutti gli stati sono considerati iid.
Un'azione in uno stato ha reward differenti rispetto ad un'altra azione in un altro stato

Le interazioni nel contextual bandit avvengono in questo modo.
L'ambiente genera uno stato, lagente fa un'azione e l reqard e' generata.

Policy: una policy è un mapping da TUTTI gli stati alle azioni, determina come l'agente seleziona azioni. Può essere deterministica (una lookup table) o stocastica, ha una distribuzione di probabilità da cui estraiamo l'azione.

L'obiettivo è ottenere la policy ottimale, la policy che ritorna il braccio che massimizza la reward in ogni stato.
Abbiamo un'expectation perché non conosciamo il mondo.

Ad ogni time step aggiorno la policy in modo che diventi ottimale.
