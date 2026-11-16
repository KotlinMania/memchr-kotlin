# memchr in Kotlin

[![GitHub link](https://img.shields.io/badge/GitHub-KotlinMania%2Fmemchr--kotlin-blue.svg)](https://github.com/KotlinMania/memchr-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.kotlinmania/memchr-kotlin)](https://central.sonatype.com/artifact/io.github.kotlinmania/memchr-kotlin)
[![Build status](https://img.shields.io/github/actions/workflow/status/KotlinMania/memchr-kotlin/ci.yml?branch=main)](https://github.com/KotlinMania/memchr-kotlin/actions)

This is a Kotlin Multiplatform transliteration port of [`BurntSushi/memchr`](https://github.com/BurntSushi/memchr) (`memchr 2.8.0`).

**Original Project:** This port is based on [`BurntSushi/memchr`](https://github.com/BurntSushi/memchr). All design credit and project intent belong to the upstream authors; this repository is a faithful port to Kotlin Multiplatform with no behavioural changes intended.

---

## About this Kotlin port

### Installation

```kotlin
dependencies {
    implementation("io.github.kotlinmania:memchr-kotlin:0.1.0")
}
```

### Building

```bash
./gradlew build
./gradlew test
```

### Targets

- macOS arm64
- Linux x64 / arm64
- Windows mingw-x64
- iOS arm64 / simulator-arm64 (Swift export + XCFramework)
- tvOS / watchOS
- JS (browser + Node.js)
- Wasm-JS (browser + Node.js) & Wasm-WASI (Node.js)
- Android (API 24+) & Android Native x64 / arm64

### License

Dual-licensed under the Unlicense or MIT license, matching upstream [`BurntSushi/memchr`](https://github.com/BurntSushi/memchr). See [LICENSE](LICENSE) and [UNLICENSE](UNLICENSE).
