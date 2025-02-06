Hackintosh EFI - Dell OptiPlex 5060 SFF (macOS Sequoia)

Descrizione

Questa repository contiene la configurazione EFI per eseguire macOS Sequoia su un Dell OptiPlex 5060. La configurazione include supporto completo per l'accelerazione grafica, audio funzionante, e un suono di avvio personalizzato per un'esperienza autentica.

Specifiche Hardware Testate

Modello: Dell OptiPlex 5060

CPU: Intel Core i5-8500

GPU: Intel UHD Graphics 630

RAM: 32gb 2666Mhz

Storage: SSD Kingstone

Wi-Fi & Bluetooth: Disponibile

Audio: Funzionante tramite alcid=11

Ethernet: Funzionante

Caratteristiche

✅ Bootloader OpenCore [Versione Attuale]✅ Accelerazione Grafica Intel UHD 630✅ Audio funzionante con Boot Sound✅ Supporto USB Mapping per una gestione ottimizzata delle porte✅ Sleep/Wake funzionante✅ iServices (iCloud, iMessage, FaceTime) completamente funzionanti✅ SMBIOS configurato come iMac19,1

Configurazione e Installazione

1. Preparazione della chiavetta USB

Scaricare macOS Sequoia dall'App Store.

Creare una chiavetta USB avviabile con createinstallmedia.

Copiare la cartella EFI in EFI della chiavetta USB.

2. Configurazione OpenCore

Verificare che tutte le kexts siano aggiornate.

3. Installazione macOS

Avviare il sistema da USB e procedere con l'installazione di macOS Sequoia.

Dopo l'installazione, montare la partizione EFI e copiare la cartella EFI nel disco principale.

Boot Sound Abilitato

Crediti

OpenCore Team

Acidanthera (per le kexts)

Hackintosh Community

Giacomo Ls (Creatore Efi Personalizzata)

Fabrizio G. (CoBug Fixer)

Immagine di installazione Utilizzata: Olarilla Mac Os sequoia

⚠️ Disclaimer: Questa configurazione è fornita senza garanzia. L'uso è a proprio rischio. Assicurarsi di fare un backup dei propri dati prima di procedere con l'installazione.
