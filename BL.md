# Encrypted Advertising Data


## Paring dispositivi wearable

### Analisi teorica del protocolli di paring
    - Teoria generale dei protocolli odierni di paring
    - Differenze nella procedura di paring tra vari dispositivi/contesti crittografici:
        - mouse
        - tastiere
        - cuffiette
        - dispositivi Apple
    *Analisi di vari dump wireshark*


## Bluetooth 5.4

### Introduzione struttura e tipi
    - Struttura AD
    - Additional Controller Advertising Data (ACAD)
    - Scambi Out-Of-Band (OOB)

### Encryption
    - Natura e composizione della cifratura introdotta
    - Cifratura dei pacchetti EIR
        - Quali sono i contesti che è necessario cifrarli
            - contesti di connection oriented vs connectionless
        - Come le versioni precedenti adottavano dei workaround per cifrarli in mancanza di un vero standard definito nel protocollo
        - Come la procedura viene standardizzata nel protocollo 5.4
    - Sharing del materiale crittografico - GAP
        - Introduzione del servizio Generic Access Profile (GAP) per lo sharing key material
        - Come viene effettuato lo sharing col modello GAP
            - Focus appunto del supporto di GAP per gli standard crittografici introdotti in 5.4
        - Livelli di sicurezza LE di GATT
            - (proposta) discussione degli attacchi MitM che hanno come target GATT e se possono essere riproposti in 5.4 nel modello GAP
    *Cito il servizio GATT in questa sezione perché il servizio GAP necessità dell'implementazione di alcuni servizi GATT per funzionare, quindi ha una base di GATT*
