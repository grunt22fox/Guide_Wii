# BootMii 백업

BootMii를 사용하여 NAND 백업을 생성하려면 <strong x-id="1">SD 카드</strong>가 필요합니다.
백업이 없는 경우 이 페이지를 건너뛰어도 되지만, 가능하면 NAND 백업을 만드는 것이 좋습니다.

::: warning

You need an **SD card** to use BootMii at all, but especially to create a NAND backup. 백업이 없는 경우 이 페이지를 건너뛰어도 되지만, 가능하면 NAND 백업을 만드는 것이 좋습니다.

:::

## Requirements

- 적어도 512MB 이상의 SD 카드

## Instructions

::: info

BootMii를 boot2로 설치한 경우 콘솔을 재시작하여 BootMii를 시작해야 합니다. 이 경우 1단계와 2단계를 건너뜁니다.

:::

1. Power on your console.

2. Launch the Homebrew Channel, and launch the Load Priiloader app.

3. Press the HOME Button, then select "Launch BootMii".

   ![](/images/bootmii/BootMii_HBC.png)

   ::: warning

   If the `Launch BootMii` button does not appear in the Homebrew Channel, [re-launch the HackMii Installer](hackmii) and install BootMii.

   :::

   ::: warning

   화면이 검은색으로 유지되고 파란색 디스크 드라이브 표시등이 깜박이면 SD 카드에 BootMii 파일이 누락된 것입니다. Download [this zip file](/assets/files/bootmii_sd_files.zip) and extract it to the root of your SD card, then try again.

   :::

4. You should see an image similar to the below now on your screen:

   ![](/images/bootmii/BootMii_Main.png)

   ::: info

   Wii 리모컨으로는 BootMii를 탐색할 수 없습니다.
   콘솔의 전원 및 재설정 버튼 또는 포트 1에 연결된 게임큐브 컨트롤러를 사용해야 합니다.
   To navigate between options, press POWER. To select an option, press RESET.

   :::

5. 옵션 버튼 (톱니바퀴가 있는 아이콘) 을 선택합니다.

   ![](/images/bootmii/BootMii_Gears.png)

6. Select the first button to the left.

   ![](/images/bootmii/BootMii_Backup.png)

7. NAND 백업이 시작됩니다. 화면에서 진행 상황을 확인할 수 있습니다.

   - "배드 블록"은 정상적입니다. NAND 백업 중 일부가 보이더라도 걱정하지 마세요.

   ![](/images/bootmii/BootMii_NAND_Backup.png)

8. 이 단계가 끝나면, 백업을 확인합니다. Ideally, all the blocks should be green after the verification process.

   - If you have factory bad blocks with uncorrectable pages, these blocks may fail to verify. As long as all non-bad blocks are successfully verified, this should be fine.

   ![](/images/bootmii/BootMii_NAND_Backup_Verify.png)

9. BootMii를 종료하려면 뒤로 버튼 (화살표가 있는 버튼) 을 누른 다음 Wii 메뉴 버튼 또는 홈브류 채널 버튼을 눌러 원하는 위치에서 종료할 수 있습니다.

   ![](/images/bootmii/BootMii_Return.png)

::: info

Note: **restoring a NAND backup is usually a last resort**. There are often better ways to unbrick your console.

Try your best to [identify your brick condition](bricks) and reverse the action that caused it in the first place.

To restore from a NAND backup on your SD card, you can follow the instructions for [RestoreMii](bootmiirecover).
**Family edition Wiis (Wiis without GameCube ports) CANNOT restore NAND backups without hardware modification.**

:::

::: info

Two files will have been created on the root of your SD Card: `nand.bin` and `keys.bin`. `nand.bin` is a backup of your console's internal memory, while `keys.bin` are your console's keys.

:::

## Autobooting

If you were able to install BootMii as boot2, but don't want to load the BootMii screen every time you turn on the Wii, you have the option of setting it to autoboot to the system menu. This should make it so you don't even notice you have BootMii installed as boot2.

1. Open `SD:/bootmii/bootmii.ini` with a text editor, such as notepad.
2. Change `#AUTOBOOT=SYSMENU` to `AUTOBOOT=SYSMENU` by deleting the `#`.
3. Then change `#BOOTDELAY=5` to `BOOTDELAY=1` by deleting the `#` and turning the `5` into a `1`.
4. Save the file and exit.

::: info

You can also use the [BootMii Config Editor](https://oscwii.org/library/app/BootMiiConfigurationEditor) app on the Wii to change these settings.

:::

## Uploading NAND Backup to Dolphin Emulator

Your NAND backup can be utilized in Dolphin Emulator.

1. Get the latest beta or development release of Dolphin Emulator from the [Dolphin Website](https://dolphin-emu.org/) and install it to your device.
2. Open Dolphin Emulator.
3. Click on the `Tools` tab, scroll down to `Manage NAND`, then select `Import BootMii NAND backup...`.
4. Locate the `nand.bin` found on the root of your SD card and select Open.
5. If it asks for a `keys.bin`, locate it on the root of your SD and select Open.

::: tip

[Continue to Priiloader Installation](priiloader)

Priiloader adds a secondary level of brick protection, and is highly recommended even if BootMii was installed as boot2. It is especially important for users of BootMii on IOS.

:::
