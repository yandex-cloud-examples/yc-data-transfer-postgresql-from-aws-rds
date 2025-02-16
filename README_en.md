# Transferring data from Amazon RDS for PostgreSQL to Managed Service for PostgreSQL

Follow this scenario to migrate data from an Amazon RDS for PostgreSQL database to a Managed Service for PostgreSQL one through Yandex Data Transfer.

Data transfers are supported for PostgreSQL versions starting with 9.4. Make sure the PostgreSQL version in your Managed Service for PostgreSQL is not older than the one in Amazon RDS.

To run this scenario, use the [ Yandex Cloud management console](https://console.yandex.cloud) or Terraform. If you prefer using Terraform, download this configuration file: [rds-pg-mpg.tf](rds-pg-mpg.tf). 

The scenario includes preparing your test data, creating and activating a data transfer, checking that the transfer runs as intended, and deleting temporary data and resources engaged in the deployment. For more information, see [this tutorial](https://yandex.cloud/docs/data-transfer/tutorials/rds-to-mpg).

Additional materials on Yandex Data Transfer:
* [Available transfers](https://yandex.cloud/docs/data-transfer/transfer-matrix)
* [Tutorials](https://yandex.cloud/docs/data-transfer/tutorials/)
