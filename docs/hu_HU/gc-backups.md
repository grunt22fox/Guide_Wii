# GameCube-másolatok kezelése

Ebben az útmutatóban bemutatjuk, hogyan használhatod a GameCube Backup Managert a GameCube-másolataid kezelésére. It functions similar to [Wii Backup Manager](wii-backups#using-wii-backup-manager).

## Követelmények

- Egy SD kártya vagy pendrive
- [GameCube Backup Manager](https://github.com/AxionDrak/GameCube-Backup-Manager/releases)

::: info

Ha több játékot akarsz játszani, javasoljuk egy külső merevlemez használatát a Wiihez. Bármilyen külső merevlemez a legtöbb modern piactérről működni fog a Wii-jal.

:::

::: info

Ellenőrizd, hogy a külső háttértárad FAT32-fájlrendszerre van-e formázva. Ne formázd más típusokra, mint NTFS, exFAT, extFS, vagy WBFS, az utolsó egyidejátmúlt fájlrendszer Wii játékok tárolására.

:::

## Útmutató

### I. rész - Letöltés

1. Csomagold ki és indítsd el a GameCube Backup Manager-t.
2. Csatlakoztasd a pendrive-ot a számítógépedbe!

### II. rész – Játékok átmásolása

1. Nyisd meg az alkalmazást és keresd meg a mappa gombot a jobb alsó sarokban. Kattints rá a Fájlkezelő ablak megnyitásához.

   ![](/images/desktop-apps/GCBM/folderbutton.png)

2. Keresd meg a mappa helyét, ami a játékot tartalmazza, amit át szeretnél vinni. Ez lehet a számítógéped merevlemezén vagy egy külső tároló eszközön. Ha megtaláltad a mappát, válaszd ki.

   ![](/images/desktop-apps/GCBM/selectfolder.png)

3. Click on the `Files (Destination)` tab, then select the `Inactive` option from the dropdown menu. Ez lehetővé teszi, hogy kiválaszd a drive-ot. amire át szeretnéd vinni a játékot. Válaszd ki a megfelelő drive betút a listából.

   ![](/images/desktop-apps/GCBM/selectdrive.png)

4. Next, go back to the `Files (Source)` tab, select the game you want to transfer, and then click either `Install Game (1:1)` or `Install Game (Scrub)`.

   ![](/images/desktop-apps/GCBM/installgame.png)

::: info

Selecting `Install Game (Scrub)` will remove unnecessary data from the game, reducing the game's file size. Ez bizonyos játékoknál jelentős csökkené, például az Animal Crossing 1.3GB-ról 26MB-ra megy le.

:::

::: tip

[Click here to go back to the site index.](site-navigation)

:::