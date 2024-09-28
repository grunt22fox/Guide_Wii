# Priiloader

[Priiloader](https://github.com/DacoTaco/priiloader) is an essential tool authored by [DacoTaco](https://github.com/DacoTaco) that adds a level of brick protection to your Wii. It loads before the Wii Menu does (hence the name). The tool can also apply hacks that are used to enhance, unlock, and fix many System Menu features.

Additionally, it can be used to quickly launch any Title or Homebrew, or change the way Wii autoboots.

## 필요한 것

- SD 카드 및 USB 드라이브
- [Priiloader Installer](https://oscwii.org/library/app/priiloader) (the `.zip` file)
- [Load Priiloader](https://oscwii.org/library/app/loadpriiloader) (the `.zip` file)

### Optional Requirements for vWii (highly recommended)

- SD 카드
- [Priiloader Wii U Forwarder](https://github.com/DacoTaco/priiloader/releases/download/0.10.0/PriiloaderWiiUForwarder.zip) (direct download)
  - [Aroma](https://wiiu.hacks.guide/#/aroma/getting-started) must be installed on your console for Priiloader Wii U Forwarder to function.

## 진행 방법

### Section I - Prep Work

1. 콘솔의 전원을 꺼 주세요.
2. Extract both apps to the root of your SD card or USB drive.
3. Copy the `apps` folder from the LoadPriiloader `.zip` to the root of your SD card or USB drive.
4. Copy the `apps` folder from the priiloader `.zip` to the root of your SD card or USB drive.
5. (vWii only) Copy the `wiiu` folder from the PriiloaderWiiUForwarder `.zip` to the root of your SD card.
6. Wii에 SD 카드를 연결하고, 홈브류 채널에서 CleanRip을 실행합니다.

### 섹션 II - Priiloader 설치하기

1. 콘솔의 전원을 켜 주세요.

2. Launch the Homebrew Channel, and launch the Load Priiloader app.

3. Launch Priiloader Installer from the list of homebrew.

   ![](/images/hbc/priiloader-and-loadpriiloader.png)

4. Press the + Button on Wii Remote or the A Button on a GameCube controller.

   ![](/images/priiloader/installer.png)

   ![](/images/priiloader/installing.png)

5. Press A to return to the Homebrew Channel.

### Section III - Entering Priiloader

1. Press the HOME button, then select Exit to System Menu to exit the Homebrew Channel.
2. Your device will have loaded the Priiloader menu.

   ![](/images/priiloader/menu.png)

Later on, to enter it you can:

- Holding RESET on a Wii while turning it on.
  - Wii Only
- Holding the ESC key on a USB keyboard while turning on the console.
  - Wii, vWii and Mini
- Run the "Load Priiloader" tool from the HBC
  - Wii, vWii and Mini
- Wii에서 홈브류 채널을 실행합니다.
  - vWii Only

### Priiloader 구성

1. Scroll down to `System Menu Hacks` and press `A`.

   ![](/images/priiloader/menu_hacks.png)

   ::: warning

   If you have put the Priiloader installer on your USB drive, make sure you do not have an SD card inserted at the same time. <br>
   Doing so will cause Priiloader to fail to find the `hacks_hash.ini` file.

   :::

2. For the following options, enable the options according to your console:
   - Wii:
     - If you are using 480p mode: `480p graphics fix in the system menu`
     - Block Disc Updates
     - Block Online Updates
     - If you are NOT using a CRT display: `Remove Deflicker`
   - vWii:
     - Block Online Updates
     - Wii System Settings via Options Button
     - If you are NOT using a CRT display: `Remove Deflicker`
   - Wii mini:
     - Block Disc Updates
     - If you are NOT using a CRT display: `Remove Deflicker`

3. Scroll down to `save settings` and press A.

4. Press `B` to return to the main menu.

::: info

You can see the [Priiloader Usage](priiloader-usage) page for more information about Priiloader's additional options and System Menu Hacks.

:::

::: info

[View the Brick Prevention Guidelines](bricks#brick-prevention)

These guidelines list ways that will help avoid bricking your Wii, beyond just having BootMii and Priiloader installed.

:::

## Wii: Next Steps

::: tip

Continue to [cIOS](cios)

This guide provides steps on how to get a basic set of cIOS installed on your Wii, enabling functionality on apps like USB loaders.

:::

## vWii: Next Steps

::: tip

Continue to [vWii cIOS](cios-vwii)

This guide provides steps on how to get a basic set of cIOS installed on the vWii, enabling functionality on apps like USB loaders.

:::

## Wii mini: Next Steps

::: tip

Continue to [Wii mini cIOS](cios-mini)

This guide provides steps on how to get a basic set of cIOS installed on your Wii mini, enabling functionality on apps like USB loaders.

:::