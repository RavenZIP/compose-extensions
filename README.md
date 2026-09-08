<p align="center">

<img alt="Logo" src="images/logo.png" width="100%">

<img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-2.3.10-A831F5">
<img alt="Compose Multiplatform" src="https://img.shields.io/badge/Compose Multiplatform-1.10.1-3b83f8">
<img alt="Static Badge" src="https://img.shields.io/badge/API-24+-39ad31">
<a href="https://jitpack.io/#RavenZIP/compose-extensions">
  <img src="https://jitpack.io/v/RavenZIP/compose-extensions.svg">
</a>
</p>

> 🌐 **Languages:**  
> [Русский](README.md) | [English](docs/README-EN.md)

## 🔎 Что такое compose-extensions?

Это Compose Multiplatform библиотека,
которая предоставляет удобные обертки для компонентов из библиотек material3 и bereza-ui.

## 🌍 Поддерживаемые платформы

| Платформа | Статус               |
|-----------|----------------------|
| Windows   | ✅ Поддерживается    |
| Linux     | ❓ Неизвестно        |
| macOS     | ❓ Неизвестно        |
| Web       | ✅ Поддерживается    |
| Android   | ✅ Поддерживается    |
| iOS       | ❌ Не поддерживается |

macOS, iOS временно не поддерживаются, так как невозможно проверить работоспособность библиотеки на данных платформах.

## 🌳 Структура проекта

### - compose-extensions

Основной и единственный модуль библиотеки.

### - docs

Документация проекта.

### - images

Изображения, используемые в README и документации.

## 🚀 Установка

**settings.gradle.kts**

```
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        ...
        maven ("https://jitpack.io")
    }
}
```

**build.gradle.kts**

```
dependencies {
    implementation("com.github.RavenZIP.compose-extensions:compose-extensions:$version") 
}
```

Если вы используете libs.versions.toml

**libs.versions.toml**

```
[versions]
ravenzip-compose-extensions = "$version"

[libraries]
ravenzip-compose-extensions = { module = "com.github.RavenZIP.compose-extensions:compose-extensions", version.ref = "ravenzip-compose-extensions" }
```

**build.gradle.kts**

```
dependencies {
    implementation(libs.ravenzip.compose.extensions)
}
```

## 🤝 Интеграции

[kotlin-reactive-forms](https://github.com/RavenZIP/kotlin-reactive-forms)

## 🚬 Примеры использования

В разработке... Смотрите berezaApp модуль

## 📚 Документация

В разработке...

## 📜 Лицензия

Эта библиотека распространяется по лицензии Apache 2.0. Подробности смотрите в файле [ЛИЦЕНЗИЯ](LICENSE).

## 👾 Разработчик

**Черных Александр**

- [Telegram](https://t.me/RavenZIP)
