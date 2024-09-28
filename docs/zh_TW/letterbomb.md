# 贊助

LetterBomb is an exploit for the Wii that is triggered using the Wii Message Board.

::: info

For instructions on how to format your SD card correctly, please see [this guide](https://wiki.hacks.guide/wiki/Formatting_an_SD_card). It is highly recommended to check it due to problems with formatting as FAT32.

:::

::: warning

Do NOT use any of the MAC address examples shown in this guide, as they will simply cause an error on the HackMii website. Use your own! Use your own!

:::

## 操作說明

- An SD card formatted as FAT32 that is 32GB or less
- A Wii on System Menu version 4.3
- A Windows/MacOS/Linux computer with an Internet connection

## Instructions

1. Power on your console.

2. Go to `Wii Settings`.

3. Take note in the top right corner of the letter next to the system version.

   - This letter corresponds to your system menu region, which you will need to know for the corresponding steps.
   - Also, ensure that you are on System Menu version 4.3.

   ![](/images/wii/SystemMenuVersion.png)

4. Navigate to `Internet` > `Console Information`.

5. Take note of your FULL MAC address.

   ![](/images/wii/MacAddress.png)

6. On your computer, open the browser and go to [the HackMii website](https://please.hackmii.com/).

7. If your Wii freezes after clicking on the letter, you probably chose the wrong region when downloading the exploit. Redo Step 2 and select the correct region.

8. Ensure `Bundle the HackMii Installer for me!` is checked.

9. Cut either wire.

   ![](/images/exploits/letterbomb/LetterBomb-PC.png)

10. Extract the contents of the downloaded ZIP to the root of your SD card.

11. Copy the `private` folder and the `boot.elf` file from the LetterBomb `.zip` to the root of your SD card.

12. Take out your SD card and insert it in your Wii.
    - The SD card must be inserted in the SD card slot located in the front of the Wii. The SD card must be inserted in the SD card slot located in the front of the Wii. Using a USB adapter plugged into the Wii's USB port will not work.

13. The SD card must be inserted in the SD card slot located in the front of the Wii. Using a USB adapter plugged into the Wii's USB port will not work.

14. On your Wii, return to the Wii Menu and then open the Wii Message Board.

15. Load the red letter with a bomb icon.
    - Ensure the date on your Wii is correct, otherwise you might be unable to find the letter.
    - In various scenarios, you may need to look at the previous or next day to find it.
    - If you don't see the red letter, check if any errors appear in the SD card section of `Data Management`. If you don't see the red letter, check if any errors appear in the SD card sections in <code>Data Management</code>. If any do, there may be an issue with the SD card format or the Wii’s SD card reader.
    - If your Wii freezes after clicking on the letter, you most likely chose the wrong system menu region for LetterBomb. Go back to Step 2 and verify that you chose the right region. Go back to Step 2 and verify that you chose the right region.
    - If all is correct and there is freezing, keep on trying until it works.

16. 您的主機現在應該啟動到 HackMii 安裝程序中。

![](/images/exploits/letterbomb/LetterBomb-Wii.png)

::: tip

[Continue to Homebrew Channel and BootMii Installation](hbc)

:::