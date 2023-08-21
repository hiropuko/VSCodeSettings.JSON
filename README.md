# КАК УСТОНОВИТЬ ОЧЕНЬ БЫСТРО СРЕДУ РАЗРАБОТКИЙ VISUAL STUDIO CODE НА WINDOWS 10 / 11 ДЛЯ PYTHON

  1. Установка Python: После установки VS Code необходимо установить интерпретатор Python. Перейдите на официальный сайт Python (https://www.python.org/) и загрузите последнюю версию Python для Windows. Установочный процесс интуитивно понятен – следуйте инструкциям.

  2. Установка Visual Studio Code: Первым шагом является скачивание и установка Visual Studio Code с официального сайта (https://code.visualstudio.com/). Загрузите версию, совместимую с вашей операционной системой (Windows).

  3. Установка расширений для Python в VS Code: Откройте VS Code после установки. Перейдите во вкладку "Extensions" (расширения), в поисковой строке введите "Python" и установите официальное расширение от Microsoft. Это обеспечит   поддержку Python в среде разработки.

Установка пакетов для VSCode:
  - Code Runner
  - Bluloco Dark Theme
  - Material Icon Theme
  - autopep8

Настройки VSCode
  - Ctrl+,
  - импорт настроек JSON

  https://github.com/repackScript/VSCodeSettings.JSON/blob/main/VSCodeSettings.JSON


4. Настройка виртуальной среды: Рекомендуется создать виртуальное окружение для каждого проекта, чтобы изолировать зависимости. В терминале VS Code используйте команду python -m venv имя_окружения для создания виртуальной среды.

    - pip install pipenv (установка виртуалной среды на хост машину, толь один раз)

5. Создание для проекта в папке собственую виртуальню среду.

   -  python -m venv имя_окружения: python -m venv .venv
   -  We noticed a new environment has been created. Do you want to select it for the workspace folder? YES
   -  установка пакетов, только для виртуальной среды: pipenv install numpy
   -  удалить пакет: pipenv uninstall numpy
   -  запуск виртуальной среды и воход в терминал через VSCode (pipevn shell)
         -  внутри среди VSCode терминал:
             -  pip list
             -  pip install пакет
             -  pip uninstall пакет (https://pypi.org/)    
   


  



