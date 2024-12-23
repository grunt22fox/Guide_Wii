---
layout: home
title: Wii 가이드
hero:
  text: Wii 가이드
  tagline: 완벽한 Wii, vWii, Wii mini 해킹 가이드.
  image:
    src: /images/main-pages/home-page-feature.jpg
---

::: info

Since this guide has just been published, translations are a work-in-progress. Thank you for your patience!

:::

::: warning

To get the most out of this guide, you should read this page before proceeding.

:::

## "홈브류"가 무엇인가요?

**Homebrew** refers to software that was not authorized by the original creator of a piece of hardware - in this case, Nintendo. 여기에는 게임, 유틸리티, 에뮬레이터 등이 포함될 수 있습니다!

Here are some common examples of what homebrew can do for your Wii:

- [Backup](bootmii) and [restore](bootmiirecover) your Wii's NAND (system memory)
- Enhance the [brick protection](priiloader) of your Wii
- Download new homebrew apps with the [Open Shop Channel](osc)
- [Patch game disc contents](https://wiki.hacks.guide/wiki/Wii:Riivolution) to load game modifications
- Install [themes](themes) on the Wii Menu and in commonly used homebrew apps
- Back up your [discs](dump-games) and [other installed titles](dump-wads)
- Watch [DVDs](recommended-homebrew#entertainment) and play external media files on your Wii
- Install a [USB loader](wii-loaders) to launch Wii (and other console) backups from an external storage device
- Restore online functionality to both [WiiConnect24](wiiconnect24) and [Nintendo Wi-Fi Connection](wiimmfi)

## 이 가이드는 무엇을 설치하는 가이드입니까?

This guide aims to do the following, including optional sections:

- Modify your Wii using one of many exploits, with the end goal of reaching the HackMii installer
- Install BootMii and the Homebrew Channel
- Make a backup of critical system files
- Install Priiloader
- Install the Open Shop Channel
- Recommended homebrew to use on your Wii
- Restore functionality to WiiConnect24 and Nintendo Wi-Fi Connection

## What should I know before starting?

- Wii 소프트웨어의 버그를 이용하면 무료로 닌텐도 Wii에서 홈브류를 실행할 수 있습니다. Anyone trying to convince you otherwise is likely attempting to [scam you](https://hbc.hackmii.com/scam).
- This guide works on all system menu versions depending on the exploit, but **it is recommended that you update to 4.3 (the latest firmware)** if possible.
- **This guide applies to retail/consumer Wiis ONLY!** This means that development units are not covered.
- Depending on what you intend to do with your modded Wii, you may have to make some modifications to the system memory that have a risk of bricking (rendering the console inoperable). As long as you follow this guide exactly, you should be fine, but for general brick prevention tips see [this](bricks#brick-prevention) page.
- The differences between the Wii and Wii mini are quite significant. This means that in some cases, something that is normally harmless to the Wii could cause a [severe brick](bricks#wi-fi-brick) to the Wii mini. Tread carefully if you are planning to mod one!
- Be extremely careful when modifying a [Korean Wii](bricks#koreankii-error-003-brick).

## 준비됐나요?

The guide has nine sections in total. These are listed below:

1. Choosing and using an exploit (REQUIRED)
2. Installing the Homebrew Channel and BootMii (REQUIRED)
3. Making a NAND backup with BootMii (REQUIRED)
4. Installing Priiloader (REQUIRED)
5. Installing the Open Shop Channel (RECOMMENDED)
6. Installing cIOS (RECOMMENDED)
7. Discovering Recommended Homebrew (RECOMMENDED)
8. Regaining WiiConnect24 Functionality (OPTIONAL)
9. Regaining Nintendo Wi-Fi Connection Functionality (OPTIONAL)

::: tip

[시작하기](get-started)로 계속합니다

:::
