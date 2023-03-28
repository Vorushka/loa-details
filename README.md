<p align="center">
  <img src="https://user-images.githubusercontent.com/29287377/170220154-a521b32b-6727-422b-bf69-01b4faaa31da.png" />

  <br />
  <br />

  <a href="https://github.com/razielqt/loa-details/releases/latest">
    <img src="https://img.shields.io/github/downloads/razielqt/loa-details/total?style=for-the-badge" />
  </a>
  <a href="https://discord.gg/E3ffRfWBuV">
    <img src="https://img.shields.io/discord/1088415616278474782?color=%235865F2&label=Discord&style=for-the-badge" />
  </a>

  <br />

  <img src="https://img.shields.io/github/package-json/v/razielqt/loa-details?style=flat-square" />
  <img src="https://img.shields.io/github/license/razielqt/loa-details?style=flat-square" />
</p>

<p align="center">Инструмент для отслеживания урона в реальном времени (версия Lost Ark от Mail.ru)</p>

![small](https://user-images.githubusercontent.com/29287377/173195460-cf8da1b4-abfa-4ed3-8dec-648eb1ffaf87.png)

---
Данный репозиторий является форком [loa-details для EU серверов](https://github.com/lost-ark-dev/loa-details) и был расширен для работы на серверах от Mail.ru.

# Зависимости

- Windows [Npcap with WinPcap compatibilities](https://npcap.com/#download)

### Во время установки Npcap для Windows:

- Необходимо отметить `Install Npcap in WinPcap API-compatible Mode`
- Если вы не хотите запускать loa-details от администратора каждый раз, вам НЕ НУЖНО выбирать `Restrict Npcap driver's access to Administrators only`

![npcap-install](./public/npcap.png)

## Пользовательская инструкция

- Убедитесь что вы установили зависимости
- Скачайте последнюю версию [здесь](https://github.com/razielqt/loa-details/releases/latest)
- Следуйте инструкциям по установке
- Наслаждайтесь

## Dev

- Clone with `git clone --recurse-submodules https://github.com/lost-ark-dev/loa-details`
- Install dependencies with `npm install`
- You can run loa-details in dev mode with the command `npm run dev`
- You can build a release-ready binary with the command `npm run build`. Output will be located in `./dist/electron` directory.

---

# Credits

This repository is a clone of the [original interface](https://github.com/karaeren/loa-details) from [@karaeren](https://github.com/karaeren).
It has been modified to work as a standalone program, without the need of any 3rd party logger.

The packet sniffing part has been made from scratch by [@Herysia](https://github.com/Herysia) and [@Mathicha](https://github.com/Mathicha), however, we can't help but thank [@Shalzuth](https://github.com/Shalzuth) for his work on [LostArkLogger](https://github.com/shalzuth/LostArkLogger).
