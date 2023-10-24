# Перенос данных из Amazon RDS for PostgreSQL в Managed Service for PostgreSQL

С помощью этого сценария вы сможете мигрировать данные из базы Amazon RDS for PostgreSQL в базу Managed Service for PostgreSQL, используя сервис Yandex Data Transfer.

Перенос данных работает для версий PostgreSQL, начиная с 9.4. Версия PostgreSQL в Managed Service for PostgreSQL должна быть не старше, чем версия PostgreSQL в Amazon RDS.

Сценарий может быть выполнен в [Консоли Управления Yandex Cloud](https://console.cloud.yandex.ru) или с помощью Terraform. Для выполнения сценария с помощью Terraform скачайте конфигурационный файл, [rds-pg-mpg.tf](rds-pg-mpg.tf). 

При выполнении сценария вы подготовите тестовые данные, подготовите и активируете трансфер, проверите работоспособность трансфера, а затем, удалите данные и ресурсы, которые вам больше не потребуются. Подробное описание см. в [практическом руководстве](https://cloud.yandex.ru/docs/data-transfer/tutorials/rds-to-mpg).

Дополнительные материалы о Yandex Data Transfer:
* [Доступные трансферы](https://cloud.yandex.ru/docs/data-transfer/transfer-matrix)
* [Практические руководства](https://cloud.yandex.ru/docs/data-transfer/tutorials/)
