# Skyler follow-up 2026-10-17 (ENCRYPTED)

Файлы зашифрованы 7z AES-256. Пароль передан отдельным каналом.

| Файл | Что внутри | Как открыть |
|---|---|---|
| `Skyler_source_snapshot.tar.gz.7z` | git archive HEAD (чистый, без tracker/tmp/bak) | `7z x -p'<PASS>' Skyler_source_snapshot.tar.gz.7z` → `tar xzf Skyler_source_snapshot.tar.gz` |
| `Skyler_Critical_Followup.zip.7z` | zip с EVIDENCE/ | `7z x -p'<PASS>' Skyler_Critical_Followup.zip.7z` → `unzip Skyler_Critical_Followup.zip` |
| `ytm-session-2026-10-17.session.7z` | сессия (уже зашифрован) | `7z x -p'<PASS>' ytm-session-2026-10-17.session.7z` |

Проверка целостности: `7z t -p'<PASS>' <файл>`.
