# AURA 1.3 FLOW — test download

Тестовая AURA 1.3 FLOW: нативный интерфейс AURA Liquid, переработанные плеер, библиотека, Studio и настройки. Flow экспериментален: точность анализа и проверки на физическом телефоне пока не прошли критерии стабильного релиза. Публикация в GitHub Releases ожидает одобрения владельца. Android 8.0+; постоянная подпись сохранена. После миграции Room3 возврат к 1.2 не поддерживается; следующие обновления должны иметь versionCode≥6.

This preview branch is not a GitHub Release and does not change the stable updater/latest channel.

Signed R8 source: `95bd9a8fd19a8cc3d655ac048537363db2e291cd`; [successful CI](https://github.com/kandykbayevtagir-wq/aura-music-player/actions/runs/37200258371).

APK SHA256: `0dbe0214cd045637cc96ab4af2497bfa92e58c51a6dae803d2f9edb8191bebc3`.

Performance acceptance remains open: full-glass SwiftShader p95 spans255.84–780.02ms; Surface fallback is faster but not60Hz. Warm startup regressed on this emulator. Physical GPU and manual listening checks are outstanding; this is not an accepted stable release.

[Implementation and all19 report subjects](https://github.com/kandykbayevtagir-wq/aura-music-player/blob/codex/native-android/android/docs/FLOW-1.3.md). Source/report access belongs to the owner; binary download is public.
