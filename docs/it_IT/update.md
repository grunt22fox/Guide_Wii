# Aggiornamento del Menu Wii alla versione 4.3

Questa guida spiegherà come aggiornare il tuo Menu Wii alla versione 4.3, se hai una Wii già softmoddata.

::: warning

It is much safer to use [ModMii](modmii) (Windows only) to update your Wii to 4.3.

:::

## Requisiti

- a Wii with The Homebrew Channel 1.0.8 or later
  - If you do not have the Homebrew Channel or it is out of date, please [start here](get-started) to (re)install it first.
- Una scheda SD o dispositivo USB
- Un computer Windows
- [NUS Downloader](https://github.com/WiiDatabase/nusdownloader/releases/latest)
- [Priiloader](priiloader)
- [YAWM ModMii Edition](https://oscwii.org/library/app/yawmme)

## Istruzioni

### Sezione I - Download

1. Estrai il file .zip per NUS Downloader Wii e apri l'applicazione.
2. Go to `Database...` > `System` > `0000000100000002 - System Menu` and select the version corresponding to your region as shown in the table below.
3. Make sure `Pack WAD` is checked.
4. Press `Start NUS Download!`.
5. Open the `titles` -> `0000000100000002` -> (Wii Menu version) and copy the .wad file to a folder called `wad` on your SD Card or USB drive.
6. Repeat steps 2-5 with `IOS` -> `000000010000003A` -> `Latest Version` and `IOS` -> `0000000100000050` -> `Latest Version`.
7. After you have copied all 3 `.wad` files, eject your SD card/USB drive from your PC and put it back into your Wii.

| Regione  | Versione Menu Wii                              |
| -------- | ---------------------------------------------- |
| Giappone | v512 (4.3J) |
| USA      | v513 (4.3U) |
| Europa   | v514 (4.3E) |
| Corea    | v518 (4.3K) |

### Sezione II - Installazione

1. Spegni la console. Tieni premuto RESET, poi accendila di nuovo.
2. In the Priiloader menu, select `Homebrew Channel`.
   - If the Priiloader menu does not appear, please [install it immediately](priiloader). Priiloader è obbligatorio per questa guida.
3. Avvia YAWM ModMii Edition.
4. Seleziona la tua scheda SD o dispositivo USB.
5. Press `+` to one the IOS80 and IOS58 WADs to highlight them, then press A twice to install.
6. Naviga sulla WAD del Menu Wii e premi A due volte per installarla.
7. Quando viene richieste di mantenere Priiloader installato, premere A per confermare.
8. Dopo aver installato tutti i file, premi il bottone HOME per ritornare all'Homebrew Channel.

::: tip

[Click here to go back to the site index.](site-navigation)

:::