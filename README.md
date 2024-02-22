# Welfare as a Service per i Comuni - (WaaS per i Comuni)

Questo repository contiene le specifiche tecniche per le API di popolamento del SIUSS ([Sistema Informativo Unitario dei Servizi Sociali](https://www.inps.it/it/it/dati-e-bilanci/siuss--ex-casellario-dell-assistenza.html)) da parte dei Comuni.

## Procedura di adesione al servizio

Per abilitare il servizio di alimentazione, l'Ente aderente deve:

1. Implementare l'api di alimentazione in accordo alle specifiche [openapi del servizio](https://github.com/INPS-it/WaaS.Comuni/blob/main/002%20-%20OpenAPI/api-comuni.yaml);
2. Aderire alla piattaforma PDND, se gia' non effettuato, come da indicazioni presenti sulla [guida all'adesione di PagoPA](https://docs.pagopa.it/interoperabilita-1/manuale-operativo/guida-alladesione) e verificare la presenza degli indirizzi e-mail istituzionali a cui essere contattati;
3. Registrare come eService su PDND la API implementata con nome `WAAS-SIUSS-Alimentazione` negli ambienti di collaudo e produzione;
4. Inviare una richiesta di adesione a progettowelfareasaservice@inps.it indicando: 
   * Il nome dell'Ente; 
   * Il codice belfiore dell'Ente;
   * IP o range di IP di erogazione del servizio in ambiente di collaudo e produzione;
5. Accettare la conseguente richiesta di fruizione del servizio da parte di INPS tramite portale PDND di Collaudo;
6. Dare seguito alle eventuali segnalazioni inviate da INPS ai contatti dell'Ente derivanti dalle verifiche di corretta implementazione del servizio di alimentazione;
7. Accettare la richiesta di fruizione del servizio da parte di INPS tramite portale PDND di Produzione; 

## Struttura del repository

### Documentazione Tecnica

Contiene i file `.xsd` che descrivono i flussi SIUSS e la specifica OpenAPI in formato `.yaml` per le API che andranno pubblicate dai Comuni su PDND.

## Licenze

I file `.xsd`e `.yaml` sono contenuti tecnici rilasciati con licenza MIT.

Il file `.pdf` di descrizione del progetto è rilasciato con licenza CC-BY 4.0
