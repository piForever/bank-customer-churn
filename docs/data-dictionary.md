# Data Dictionary

This document describes the variables used in the Bank Customer Churn Prediction project. The bilingual Excel version is available as [a downloadable file](Classification_Model_Data_Dictionary_Bilingual.xlsx).

| Feature | Unit of Measure | Description |
| --- | --- | --- |
| numero_de_cliente | id | Unique identifier assigned to each customer. |
| cliente_vip | N/A | Indicates whether the customer is classified as a VIP customer. |
| internet | N/A | Indicates whether the customer uses online banking services or has the mobile app installed. |
| cliente_edad | years | Customer age in years. |
| cliente_antiguedad | months | Customer tenure in months. |
| mrentabilidad | Argentine pesos | Total profit earned by the bank from the customer during the month. |
| mrentabilidad_anual | Argentine pesos | Total profit earned by the bank from the customer during the last year of the customer relationship, or since onboarding for recent customers. |
| mcomisiones | Argentine pesos | Total fees earned by the bank from the customer. |
| mactivos_margen | Argentine pesos | Total interest income earned by the bank from loans or other customer assets. |
| mpasivos_margen | Argentine pesos | Total income earned by the bank from the customer's deposits or investments. |
| cant_total_prod | N/A | Number of product families the customer holds with the bank. |
| tpaquete1 | N/A | Indicates whether the customer has package 1, the bank's premium package. |
| tpaquete2 | N/A | Indicates whether the customer has package 2. |
| tpaquete3 | N/A | Indicates whether the customer has package 3. |
| tpaquete4 | N/A | Indicates whether the customer has package 4. |
| tpaquete5 | N/A | Indicates whether the customer has package 5. |
| tpaquete6 | N/A | Indicates whether the customer has package 6. |
| tpaquete7 | N/A | Indicates whether the customer has package 7. |
| tpaquete8 | N/A | Indicates whether the customer has package 8. |
| tpaquete9 | N/A | Indicates whether the customer has package 9. |
| tcuentas | N/A | Number of accounts held by the customer: 0 for none, 1 for savings or checking accounts only, and 2 for at least one of each type. |
| mdescubierto_preacordado | Argentine pesos | Total agreed overdraft amount on checking accounts. |
| mcuentas_saldo | Argentine pesos | Total balance across all customer accounts, including savings and checking accounts in local and foreign currency. |
| ctarjeta_debito_transacciones | N/A | Number of debit card transactions made by the customer during the month. |
| mautoservicio | Argentine pesos | Total amount of debit card transactions made by the customer during the month. |
| ctarjeta_visa | N/A | Number of Visa credit card accounts held by the customer. |
| ctarjeta_visa_transacciones | N/A | Number of Visa credit card transactions made during the month. |
| mtarjeta_visa_consumo | Argentine pesos | Total amount spent with the Visa credit card during the month. |
| ctarjeta_master | N/A | Number of Mastercard credit card accounts held by the customer. |
| ctarjeta_master_transacciones | N/A | Number of Mastercard credit card transactions made during the month. |
| mtarjeta_master_consumo | Argentine pesos | Total amount spent with the Mastercard credit card during the month. |
| cprestamos_personales | N/A | Number of active personal loans held by the customer. |
| mprestamos_personales | Argentine pesos | Total outstanding balance across all customer personal loans. |
| cplazo_fijo | N/A | Number of active fixed-term deposits held by the customer in local and foreign currency. |
| mplazo_fijo_dolares | Argentine pesos | Total value of active foreign-currency fixed-term deposits, converted to Argentine pesos at the month-end exchange rate. |
| mplazo_fijo_pesos | Argentine pesos | Total value of active local-currency fixed-term deposits. |
| cfondos_comunes_inversion | N/A | Number of active mutual fund investments held by the customer. |
| mfondos_comunes_inversion_pesos | Argentine pesos | Total value of active local-currency mutual fund investments. |
| mfondos_comunes_inversion_dolares | Argentine pesos | Total value of active foreign-currency mutual fund investments. |
| Ctitulos | N/A | Number of active securities investments held by the customer. |
| mtitulos | Argentine pesos | Total value of securities investments, expressed in Argentine pesos. |
| cseguro_auto | N/A | Number of active motor insurance policies held by the customer. |
| cseguro_vivienda | N/A | Number of home insurance policies held by the customer. |
| cseguro_accidentes_personales | N/A | Number of personal accident insurance policies held by the customer. |
| ccaja_seguridad | N/A | Indicates whether the customer has at least one safe deposit box. Possible values are 0 and 1. |
| mbonos_corporativos | Argentine pesos | Total value of the customer's government bond investments, expressed in Argentine pesos at month-end. |
| mmonedas_extranjeras | Argentine pesos | Total foreign currency held by the customer, valued in Argentine pesos at month-end. |
| minversiones_otras | Argentine pesos | Total value of other investments, expressed in Argentine pesos at month-end. |
| cplan_sueldo | N/A | Number of payroll accounts or salary plans. |
| mplan_sueldo | Argentine pesos | Total amount credited by registered employers to the customer during the month. |
| mplan_sueldo_manual | Argentine pesos | Total amount manually credited by registered employers to the customer during the month. |
| cplan_sueldo_transaccion | N/A | Number of manual salary credit transactions made by registered employers during the month. |
| ccuenta_debitos_automaticos | N/A | Number of automatic debits charged to bank accounts during the month, excluding credit cards. |
| mcuenta_debitos_automaticos | Argentine pesos | Total amount of automatic debits charged to bank accounts during the month, excluding credit cards, converted to Argentine pesos at month-end. |
| ctarjeta_visa_debitos_automaticos | N/A | Number of automatic debits charged to Visa credit cards during the month. |
| mttarjeta_visa_debitos_automaticos | Argentine pesos | Total amount of automatic debits charged to Visa credit cards during the month, converted to Argentine pesos at month-end. |
| cpagodeservicios | N/A | Number of utility or service payments made during the month. |
| mpagodeservicios | Argentine pesos | Total amount of utility or service payments made during the month. |
| cpagomiscuentas | N/A | Number of payments made through the PagoMisCuentas channel during the month. |
| mpagomiscuentas | Argentine pesos | Total amount in Argentine pesos of payments made through the PagoMisCuentas channel during the month. |
| mcomisiones_mantenimiento | Argentine pesos | Total product maintenance fees charged by the bank during the month. |
| ccomisiones_otras | N/A | Number of other fees charged to the customer during the month. |
| mcomisiones_otras | Argentine pesos | Total amount in Argentine pesos of other fees charged to the customer during the month. |
| ccambio_monedas | N/A | Number of foreign currency exchange transactions made by the customer during the month. |
| ccambio_monedas_compra | N/A | Number of foreign currency purchase transactions made by the customer during the month. |
| mcambio_monedas_compra | Argentine pesos | Total amount in Argentine pesos of foreign currency purchase transactions made by the customer during the month. |
| ccambio_monedas_venta | N/A | Number of foreign currency sale transactions made by the customer during the month. |
| mcambio_monedas_venta | Argentine pesos | Total amount in Argentine pesos of foreign currency sale transactions made by the customer during the month. |
| ctransferencias_recibidas | N/A | Number of transfers received across all accounts during the month, from the customer or third parties. |
| mtransferencias_recibidas | Argentine pesos | Total amount of transfers received across all accounts during the month, from the customer or third parties. |
| ctransferencias_emitidas | N/A | Number of transfers sent from all accounts during the month, by the customer or third parties. |
| mtransferencias_emitidas | Argentine pesos | Total amount of transfers sent from all accounts during the month, by the customer or third parties. |
| cextraccion_autoservicio | N/A | Number of ATM cash withdrawals during the month. |
| mextraccion_autoservicio | Argentine pesos | Total amount of ATM cash withdrawals during the month. |
| ccheques_depositados | N/A | Number of checks deposited into the customer's accounts during the month. |
| mcheques_depositados | Argentine pesos | Total amount of deposited and successfully collected checks during the month. |
| ccheques_emitidos | N/A | Number of customer checks collected during the month, by the customer or third parties. |
| mcheques_emitidos | Argentine pesos | Total amount of customer checks collected during the month, by the customer or third parties. |
| ccheques_depositados_rechazados | N/A | Number of checks deposited into the customer's accounts and rejected during the month. |
| mcheques_depositados_rechazados | Argentine pesos | Total amount of checks deposited into the customer's accounts and rejected during the month. |
| ccheques_emitidos_rechazados | N/A | Number of customer-issued checks rejected during the month. |
| mcheques_emitidos_rechazados | Argentine pesos | Total amount of customer-issued checks rejected during the month. |
| thomebanking | N/A | Indicates whether the customer is enrolled in online banking. Possible values are 0 and 1. |
| chomebanking_transacciones | N/A | Number of online banking transactions made by the customer during the month. |
| cautoservicio | N/A | Number of self-service terminal transactions made during the month, including cash and check deposits. |
| cautoservicio_transacciones | N/A | Total amount of self-service terminal transactions made during the month, including cash and check deposits. |
| tmovimientos_ultimos90dias | N/A | Number of voluntary bank-account transactions, excluding credit card transactions, made during the last 90 days. |
| Visa_marca_atraso | N/A | Indicates whether the customer failed to make the minimum payment and is delinquent. Possible values are 0 and 1. |
| Visa_cuenta_estado | N/A | Visa credit card account status: 10 normal, 11 and 12 with issues, and 19 closed account. |
| Visa_mfinanciacion_limite | Argentine pesos | Credit card financing limit, expressed in Argentine pesos. |
| Visa_msaldototal | Argentine pesos | Total credit card balance for the month. |
| Visa_msaldopesos | Argentine pesos | Total local-currency credit card balance for the month. |
| Visa_msaldodolares | Argentine pesos | Total foreign-currency credit card balance for the month. |
| Visa_mconsumospesos | Argentine pesos | Total local-currency credit card spending by the customer during the month. |
| Visa_mconsumosdolares | Argentine pesos | Total foreign-currency credit card spending by the customer during the month. |
| Visa_mlimitecompra | Argentine pesos | Credit card purchase limit. |
| Visa_mpagado | Argentine pesos | Total amount of all payments made by the customer. |
| Visa_mpagospesos | Argentine pesos | Total amount of local-currency payments made by the customer. |
| Visa_mpagosdolares | Argentine pesos | Total amount of foreign-currency payments made by the customer. |
| Visa_fechaalta | date | Credit card account opening date. |
| Visa_mconsumototal | Argentine pesos | Total amount in Argentine pesos of all local- and foreign-currency spending made by the customer during the month. |
| Visa_cconsumos | N/A | Number of credit card purchases made by the customer during the month. |
| Visa_mpagominimo | Argentine pesos | Minimum payment required to avoid credit card delinquency. |
| clase_binaria | N/A | Target variable indicating whether the customer churns during the following two months. Possible values are BAJA and CONTINUA. |
