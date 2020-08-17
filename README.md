  # Кроссплатформенный драйвер весов (scales_drv_ng)

  В этом репозитории распространяются сборки драйвера scales_drv_ng и осуществляется поддержка.  
  [Обратная связь](https://github.com/shtrih-m/scales_drv_ng/issues)

  ## Общие
  #### Поддерживаемые ОС
  * Windows XP и выше
  * Linux glibc 2.27 и выше

  ## Настройки
  #### 1C
  ![1c_image](https://github.com/shtrih-m/scales_drv_ng/blob/master/img/settings.png?raw=true)
  #### Логгирование
  Лог глобальный и включен всегда.
  Настройки логгирования можно установить через переменные окружения:
  * **SCALES_DRV_DEBUG_CONSOLE** - если определена лог будет посылаться в `stdout`
  * **SCALES_DRV_LOG_PATH** - путь к файлу лога
    по-умолчанию: 'scales_drv_ng.log' в текущей рабочей директории, если файл невозможно открыть на запись лог будет переведен в `stdout`
  * **SCALES_DRV_LOG_FILE_COUNT** - количество файлов в ротации лога
    по-умолчанию: 2
  * **SCALES_DRV_LOG_PART_SIZE** - размер каждой части в ротации в байтах
    по-умолчанию: 10485760


  ## Скачать 
  Cборка и тестирование осуществляется в CI проекта. Релизы выкладываются на [github](https://github.com/shtrih-m/scales_drv_ng/releases)  
  * **one_s_scales_drv_ng** - [сборка 1С](https://v8.1c.ru/tekhnologii/standartnye-biblioteki/1s-biblioteka-podklyuchaemogo-oborudovaniya/elektronnye-vesy/) для четырех платформ (Linux i486,Linux x86_64, Windows i386, Windows x86_64)
