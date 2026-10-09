# Pokémon Platino Kaizo — patch italiana

Traduzione italiana di **Pokémon Platinum Kaizo — Nightmare Update Final**.

**Alpha 0.1:** la traduzione è incompleta. Restano 1.842 messaggi da tradurre o revisionare e il gioco deve ancora essere testato in DeSmuME.

## Come usare la patch

La patch italiana si applica a una ROM **già patchata con Kaizo Nightmare Update Final**.

1. Scarica [platino-kaizo-it-alpha-0.1.xdelta](platino-kaizo-it-alpha-0.1.xdelta). Se hai scaricato l’intero repository come ZIP, estrailo prima.
2. Apri [Xdelta patcher](https://kotcrab.github.io/xdelta-wasm/).
3. In **Source file**, seleziona la tua ROM Kaizo `.nds`.
4. In **Patch file**, seleziona `platino-kaizo-it-alpha-0.1.xdelta`.
5. Premi **Apply Patch** e attendi il download del file `.nds` risultante.
6. Rinominalo, ad esempio, `Platino Kaizo IT alpha.nds` e aprilo in DeSmuME.

Conserva la ROM di partenza e una copia del tuo salvataggio durante le prove.

### Se parti da Pokémon Platino US Rev 1

Devi applicare prima la patch originale di Kaizo:

1. Apri lo stesso [Xdelta patcher](https://kotcrab.github.io/xdelta-wasm/).
2. In **Source file**, scegli la ROM di Pokémon Platinum **US Rev 1**. In **Patch file**, scegli `Pokemon Platinum Kaizo Nightmare Update Final.xdelta` e premi **Apply Patch**.
3. Usa la ROM appena ottenuta come **Source file** e applica la patch italiana seguendo i passaggi sopra.

L’ordine è: **Platino US Rev 1 → Kaizo Nightmare Update Final → patch italiana**.

Questo repository contiene la patch italiana. La ROM e la patch originale di Kaizo vanno procurate separatamente.

## Compatibilità

La patch è stata verificata sulla ROM Kaizo con questo SHA-256:

```text
8afefe06be640aa17ffcd2debc1434ea0e2e338a38db198cf634c573bca189df
```

Se il patcher segnala un errore di checksum, controlla di avere la versione corretta di Kaizo e di aver applicato le patch nell’ordine indicato. Lascia attiva la verifica del checksum.

## Stato della traduzione

Questa alpha include i testi originali recuperati dalla versione italiana di Platino e adattamenti per nuove mosse, descrizioni, menu e modalità di difficoltà. Alcuni dialoghi personalizzati sono ancora in inglese. La grafica con testo incorporato non è stata tradotta.

La patch modifica l’archivio dei testi. Gli altri dati di gioco sono rimasti identici alla ROM Kaizo di partenza. La generazione e l’applicazione della patch sono state verificate; la resa dei testi e il funzionamento nell’emulatore restano da controllare.

Nei nomi delle mosse, **IF** significa **Introforza**: per esempio, `IF Acqua`.

## Crediti

Platinum Kaizo è opera di **SinisterHoodedFigure**, **Mr.Keating** e dei collaboratori indicati nei crediti dell’hack. I testi italiani originali provengono dalla localizzazione di Pokémon Platino.
