<div align="center">

# 🛡️ Kensei Guard (Alpha)

**Современный, высокоскоростной и безопасный VPN-клиент нового поколения для Android на базе ядра Xray-core.**

[![Release](https://img.shields.io/github/v/release/Kensei-Guard/Kensei-alpha?style=for-the-badge&color=gold)](https://github.com/Kensei-Guard/Kensei-alpha/releases)
[![Android](https://img.shields.io/badge/Android-8.0%2B-brightgreen.svg?style=for-the-badge&logo=android)](https://www.android.com)
[![License](https://img.shields.io/badge/License-Proprietary-blue.svg?style=for-the-badge)](#)
[![Xray-core](https://img.shields.io/badge/Core-Xray--core-orange.svg?style=for-the-badge)](https://github.com/XTLS/Xray-core)

<br/>

[📥 **Скачать последнюю версию (Releases)**](https://github.com/Kensei-Guard/Kensei-alpha/releases/latest) • [🐞 **Сообщить об ошибке (Issues)**](https://github.com/Kensei-Guard/Kensei-alpha/issues)

</div>

---

## 🌟 О проекте

**Kensei Guard** — это производительный сетевой клиент с современным интерфейсом **Glass UI**, ориентированный на максимальную скорость соединения, надежную защиту приватности и удобство использования в один клик.

Клиент разработан с нуля на стеке **Kotlin + Jetpack Compose** и обеспечивает ультра-низкие задержки при маршрутизации сетевого трафика.

---

## 🚀 Ключевые возможности

### ⚡ Современные протоколы связи
* Поддержка **VLESS (Reality)** для обхода блокировок и маскировки под доверенный трафик.
* Поддержка **WireGuard, Shadowsocks, Trojan, Hysteria / Hysteria 2, TUIC**.
* Мгновенное переключение конфигураций без разрыва активных соединений.

### 🧠 Умная маршрутизация (Smart Split Tunneling)
* **Автоматический Direct-режим для РФ-сервисов:** банки, госуслуги, маркетплейсы и службы доставки работают напрямую на максимальной скорости домашнего провайдера.
* Ручная настройка раздельного туннелирования для любых установленных приложений.

### 🔒 Безопасность и шифрование данных
* **SQLCipher Database:** локальная база данных зашифрована на уровне хранилища.
* **Kill Switch & IPv6 Leak Protection:** мгновенная блокировка утечек данных при нестабильном сигнале сети.
* **Wi-Fi Security Auditor:** автоматический аудит открытых и небезопасных Wi-Fi сетей с опцией автоподключения защиты.

### 🔗 Импорт в 1 клик (Deep Links)
* Поддержка схем `kensei://`, `happ://`, `v2rayng://` и веб-подписок.
* Моментальный импорт ключей прямо из браузера или панели управления.

### 📱 Поддержка всех типов устройств
* Полная адаптивность: смартфоны, планшеты и **Android TV / TV Box** (управление пультом и встроенный сканер QR-кодов).
* Встроенный механизм бесшовных автообновлений (**In-App OTA**).

---

## 📦 Загрузка и установка

Перейдите на страницу [**Релизов (GitHub Releases)**](https://github.com/Kensei-Guard/Kensei-alpha/releases/latest) и выберите нужный файл:

| Архитектура | Файл | Для каких устройств |
| :--- | :--- | :--- |
| **ARM64 (64-bit)** | `app-arm64-v8a-release.apk` | Подавляющее большинство современных смартфонов и планшетов (Android 8.0+) |
| **ARMv7 (32-bit)** | `app-armeabi-v7a-release.apk` | Бюджетные ТВ-боксы, старые планшеты и 32-битные устройства |

---

## 🛠️ Технологический стек

* **Language:** Kotlin
* **UI:** Jetpack Compose & Material 3
* **Core:** Xray-core (Go / JNI)
* **Security:** SQLCipher, Tink Crypto, Network Security Config
* **Architecture:** Clean Architecture + MVI/MVVM + Coroutines / Kotlin Flow

---

## ⚠️ Статус проекта: Alpha

> Приложение находится в стадии активного открытого альфа-тестирования.  
> Если вы обнаружили ошибку или хотите предложить улучшение — создайте [**Issue**](https://github.com/Kensei-Guard/Kensei-alpha/issues) или экспортируйте журнал отладки из раздела **«Настройки» ➔ «Логи»**.
