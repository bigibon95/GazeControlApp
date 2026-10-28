Добавил GitHub Actions workflow для автоматической сборки APK.

**Файлы:**
- `.github/workflows/build.yml` - workflow для сборки

**Как использовать:**
1. Загрузи папку `GazeControlApp` в GitHub репозиторий (можно через git или через веб-интерфейс)
2. При push в main ветку GitHub автоматически соберёт APK
3. Перейди в Actions → выбери запуск → скачай артефакт `app-debug`
4. Распакуй и установи `app-debug.apk` на Android

Также можно запустить вручную через `workflow_dispatch`.
