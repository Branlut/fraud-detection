# Contexto
El dataset contiene los registros de transacciones financieras para la detección de fraudes (6,3 millones de registros).

INGRESO EN EFECTIVO: es el proceso de aumentar el saldo de la cuenta mediante un pago en efectivo a un comercio.

RETIRO EN EFECTIVO: es el proceso opuesto al INGRESO EN EFECTIVO; consiste en retirar efectivo de un comercio, lo que disminuye el saldo de la cuenta.

DÉBITO: es un proceso similar al RETIRO EN EFECTIVO e implica enviar el dinero del servicio de dinero móvil a una cuenta bancaria.

PAGO: es el proceso de pagar bienes o servicios a comercios, lo que disminuye el saldo de la cuenta y aumenta el del receptor.

TRANSFERENCIA: es el proceso de enviar dinero a otro usuario del servicio a través de la plataforma de dinero móvil.

# Tecnologias
- Pyspark
- seaborn
- matplotlib
- Pyspark.ml

# Hallazgos
- El data set no conto con inconsistencias ya sea por datos faltantes o duplicados



# Modelo ML
El modelo usado es un Random forest para clasificar si una transacción es un fraude
- El modelo conto con AUC = 0.9757 implica que el modelo tiene una capacidad muy alta de discriminar entre transacciones fraudulentas y legítimas.
- En términos simples: si tomas una transacción fraudulenta y una legítima al azar, hay un 97.57% de probabilidad de que el modelo le asigne una puntuación más alta (de riesgo) a la fraudulenta.
