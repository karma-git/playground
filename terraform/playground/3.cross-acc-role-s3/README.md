# Обзор

Есть два амазон аккаунта **A** и **B**. 

В аккаунте A находится S3 бакет.

Мы хотим разрешить просматривать бакеты и вносить изменения в определенный путь в бакете для аккаунта B.

## Шаги

Выполняем терраформ код.

Выполняем скрипт assume_role.sh

В него нужно передать имя профайлов aws аккаунтов A, B, и имя роли A.

Скрипт эскпортирует переменные окружения aws с которыми можно будет получить доступ к s3 в аккаунте A.