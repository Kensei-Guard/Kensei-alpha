<div align="center">

# PROJECT PHANTOM

**Кроссплатформенный сетевой клиент для защищенного туннелирования и маршрутизации трафика на базе Xray-core.**

[![Release](https://img.shields.io/github/v/release/Kensei-Guard/Kensei-alpha?style=flat-square&color=18181b&labelColor=09090b)](https://github.com/Kensei-Guard/Kensei-alpha/releases)
[![Platforms](https://img.shields.io/badge/Platforms-Android%20%7C%20iOS%20%7C%20macOS%20%7C%20Windows-18181b?style=flat-square&labelColor=09090b)](#)
[![Core](https://img.shields.io/badge/Core-Xray--core-18181b?style=flat-square&labelColor=09090b)](https://github.com/XTLS/Xray-core)
[![License](https://img.shields.io/badge/License-Proprietary-18181b?style=flat-square&labelColor=09090b)](#)

<br/>

[**Скачать релиз**](https://github.com/Kensei-Guard/Kensei-alpha/releases/latest)  ·  [**Баг-репорты и предложения**](https://github.com/Kensei-Guard/Kensei-alpha/issues)

</div>

---

## О проекте

**Project Phantom** — производительный сетевой клиент, спроектированный для организации защищенных каналов связи, удаленного доступа к закрытой инфраструктуре и работы в сетях со сложной маршрутизацией и жесткими ограничениями ресурсов мобильных систем.

В основе клиента лежит единая кроссплатформенная бизнес-логика на **Kotlin Multiplatform** и нативный UI на **Jetpack Compose**, что обеспечивает минимальные задержки при обработке пакетов и предсказуемое потребление памяти под высокой нагрузкой.

---

## Ключевые возможности

**Современные транспортные протоколы**
* Поддержка **VLESS (XTLS-Reality, Vision, XHTTP)** для инкапсуляции и криптографической защиты транспортного канала.
* Поддержка **Hysteria / Hysteria 2, TUIC, Trojan, Shadowsocks и WireGuard** для работы в нестабильных мобильных сетях с высоким процентом потерь пакетов.
* Бесшовное переключение между профилями без обрыва активных сетевых сессий.

**Интеллектуальная маршрутизация (Split Tunneling)**
* Автоматическая локальная маршрутизация: доверенные отечественные сервисы, банковские клиенты и государственные порталы работают напрямую через локальный шлюз провайдера без лишних задержек.
* Гранулярные правила раздельного туннелирования на уровне отдельных приложений.

**Защита соединения и утечек**
* **Kill Switch & IPv6 Leak Protection** — мгновенная блокировка нешифрованного трафика при обрыве туннеля или смене сетевого интерфейса (Wi-Fi / LTE).
* **Wi-Fi Security Auditor** — фоновый анализ открытых беспроводных сетей с автоматической активацией защищенного канала при подключении к недоверенным точкам доступа.

**Интеграция и мультидевайс**
* Быстрый импорт конфигураций и корпоративных подписок по deep-link схемам (`phantom://`, `kensei://`, `happ://`, `v2rayng://`).
* Адаптивный интерфейс с поддержкой смартфонов, планшетов и **Android TV / TV Box** (навигация с пульта и встроенный QR-сканер).
* Встроенная система доставки обновлений (**In-App OTA**).

---

## Установка (Android)

Актуальные сборки доступны на странице [GitHub Releases](https://github.com/Kensei-Guard/Kensei-alpha/releases/latest). Поддержка десктопных систем и iOS находится на этапе закрытого тестирования.

| Архитектура | Сборка | Совместимость |
| :--- | :--- | :--- |
| **ARM64 (`arm64-v8a`)** | `app-arm64-v8a-release.apk` | Современные смартфоны и планшеты (Android 8.0+) |
| **ARMv7 (`armeabi-v7a`)** | `app-armeabi-v7a-release.apk` | Бюджетные ТВ-приставки и 32-битные устройства |

---

## Технологический стек

* **Cross-Platform & Native:** Kotlin Multiplatform (KMP), Rust, Go, Swift
* **UI Framework:** Jetpack Compose, Material 3
* **Network Engine:** Xray-core (Go / JNI)
* **Security:** Google Tink, Network Security Config
* **Architecture:** Clean Architecture, MVI / MVVM, Kotlin Coroutines & Flow

---

## Статус разработки

> Проект находится в стадии открытого альфа-тестирования. Архитектура и сетевые модули активно дорабатываются.  
> При возникновении проблем со связью выгрузите журнал работы через **Настройки → Логи** и прикрепите его к новому [Issue](https://github.com/Kensei-Guard/Kensei-alpha/issues).
