# Миграция данных из OpenSearch в Yandex Managed Service for OpenSearch

C помощью сервиса Data Transfer в Yandex Cloud вы можете перенести данные из индексов стороннего кластера-источника OpenSearch в индексы Managed Service for OpenSearch. Для этого:

1. Настройте кластер-источник.
2. Подготовьте тестовые данные.
3. Настройте кластер-приемник.
4. Подготовьте и активируйте трансфер.
5. Проверьте работу трансфера.

Подробное описание см. в [практическом руководстве](https://cloud.yandex.ru/docs/data-transfer/tutorials/os-to-mos).
Сценарий может быть выполнен в [Консоли Управления Yandex Cloud](https://console.cloud.yandex.ru) или с помощью Terraform. Для выполнения сценария с помощью Terraform скачайте конфигурационный файл, [data-transfer-os-mos.tf](data-transfer-os-mos.tf). 

Дополнительные материалы о Yandex Data Transfer:
* [Доступные трансферы](https://cloud.yandex.ru/docs/data-transfer/transfer-matrix)
* [Практические руководства](https://cloud.yandex.ru/docs/data-transfer/tutorials/)
