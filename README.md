# Challenge2_DS_ONE_TelecomX
# 📄 Informe final

## Introducción

El objetivo de este análisis es con respecto al Challenge 2 de la ruta de Científici de Datos de ONE es identificar patrones y factores asociados con la evasión de clientes (churn) en para Telecom X, con el fin de proporcionar insights que ayuden a reducir la pérdida de clientes ( es decir retenerlos).

## Limpieza y Tratamiento de Datos

Se importaron y normalizaron datos provenientes de una API pública en formato JSON, el cuál contenía sub diccionarios que no ayudaban al tramiento de los datos y transformaciones.  
Por ello,se estandarizaron columnas y valores, se convirtieron variables categóricas a binarias y se crearon nuevas variables relevantes como la "facturación diaria".  
Se eliminaron registros con datos faltantes en variables clave para asegurar la calidad del análisis.

## Análisis Exploratorio de Datos

- La evasión presenta un porcentaje significativo del 26.5%, con diferencias claras en la facturación y duración del cliente.  
<img width="549" height="393" alt="image" src="https://github.com/user-attachments/assets/480e046a-81f6-4c8d-b21d-c25e9b06a105" />

<img width="491" height="504" alt="image" src="https://github.com/user-attachments/assets/4e4e98e8-01e5-4d58-9036-34c4ed773ce8" />

- Los clientes con contratos a corto plazo tienen una mayor tendencia a abandonar el servicio.

  <img width="790" height="390" alt="image" src="https://github.com/user-attachments/assets/293747e4-6489-4de0-b5e3-da8f51b654ce" />
  <img width="790" height="390" alt="image" src="https://github.com/user-attachments/assets/91497c54-70eb-49f4-89be-95a2fa8b5d87" />
  <img width="790" height="390" alt="image" src="https://github.com/user-attachments/assets/c92217ce-457f-43f7-9f97-632cf0e17dc0" />

- Las variables numéricas muestran que los clientes que evaden tienden a tener mayor facturación diaria y menor tiempo en la empresa.

### Interpretación del Análisis Descriptivo de Variables Numéricas según Evasión

- **Facturación mensual:**  
  Los clientes que evadieron tienen un gasto promedio mensual mayor (74.44) en comparación con los que permanecieron (61.31). Esto puede indicar que los clientes con facturas más altas podrían tener mayor propensión a cancelar el servicio, tal vez buscando opciones más económicas.


   <img width="704" height="394" alt="image" src="https://github.com/user-attachments/assets/7acef681-1430-45ca-a1cc-884eb55fac1b" />

- **Facturación diaria:**  
  Similarmente, la facturación diaria promedio es mayor en clientes que abandonaron (2.48) frente a los que se mantienen (2.04). Este dato refuerza la idea de que el costo diario del servicio puede ser un factor relevante en la decisión de evasión.

<img width="687" height="394" alt="image" src="https://github.com/user-attachments/assets/459ed712-7d6f-49fc-8f20-73c95b31e6e5" />

- **Meses como cliente:**  
  La antigüedad promedio de los clientes que evadieron es considerablemente menor (29 meses) que la de quienes permanecen (61 meses). Esto sugiere que la mayor parte de la evasión ocurre en clientes relativamente nuevos, enfatizando la importancia de estrategias de retención temprana.

<img width="687" height="394" alt="image" src="https://github.com/user-attachments/assets/41a2a816-97f2-48c3-a595-4ef0e5b61a79" />

<img width="691" height="394" alt="image" src="https://github.com/user-attachments/assets/21606340-0b06-46a4-9269-39ce840fdef4" />


## Conclusiones e Insights

- La duración del cliente y tipo de contrato son factores clave en la evasión.  
- La facturación diaria puede ser un indicador temprano de riesgo de evasión.  
- Variables demográficas mostraron menor impacto directo pero pueden ser exploradas más a fondo.

## Recomendaciones

- Implementar campañas específicas para clientes con contratos mes a mes.  
- Monitorear clientes con alta facturación diaria y poca antigüedad.  
- Mejorar el soporte y métodos de pago, alineándolos con perfiles de clientes en riesgo.  
- Desarrollar modelos predictivos para anticipar la evasión y tomar acciones preventivas.

---

Este análisis sienta una base sólida para continuar trabajando en la retención de clientes en Telecom X.
