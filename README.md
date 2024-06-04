Вот инструкция для запуска сервиса на Tauri с использованием Angular:

### Этап 1: Установка программ

1. Установите Visual Studio Build Tools, Rustup, Rust Nightly и Node.js, если они еще не установлены в вашей системе:
   - `https://visualstudio.microsoft.com/ru/visual-cpp-build-tools/`
   - `https://www.rust-lang.org/tools/install`
   - `https://users.rust-lang.org/t/psa-a-new-nightly-is-out/8606`
   - `https://nodejs.org/en`

### Этап 2: Подготовка проекта

1. Склонируйте или загрузите проект, если у вас его нет.
2. Откройте терминал и перейдите в папку с проектом.

### Этап 3: Установка зависимостей

1. В терминале выполните команду для установки зависимостей npm:
   ```
   npm install
   ```

### Этап 4: Запуск сервиса

1. После установки зависимостей запустите Tauri Development Server, используя следующую команду:
   ```
   npm run tauri dev
   ```

После выполнения этих шагов ваше приложение на Angular будет запущено с использованием Tauri. Вы сможете разрабатывать и тестировать его локально.