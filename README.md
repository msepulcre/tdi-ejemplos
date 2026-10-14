# TDI · Ejemplos de teoría

Material de **Tratamiento Digital de la Información** para leer ejemplos y experimentar con sus parámetros.
La colección contiene cinco ejemplos del **tema 3: codificación de canal** y cuatro del **tema 4: fundamentos del procesado estadístico**.

**[Abrir la web de ejemplos](https://msepulcre.github.io/tdi-ejemplos/)**

Cada ejemplo dispone de un **HTML estático**, con explicaciones, código y resultados guardados,
y un **cuaderno Jupyter**, que se abre directamente en Google Colab mediante el botón «Abrir en Colab».
Para experimentar en Colab no hace falta descargar archivos ni instalar Jupyter; se necesita una cuenta de Google para ejecutar.
Los cambios realizados en una sesión de Colab no modifican los cuadernos originales de este repositorio.

## Ejemplos disponibles

| Apartado | Ejemplo | Experimentar |
|---|---|---|
| 3.1 | [Capacidad del canal: ancho de banda, potencia y ruido](vista_previa/tema_3_01_capacidad_del_canal.html) | [Abrir en Colab](https://colab.research.google.com/github/msepulcre/tdi-ejemplos/blob/main/tema_3/01_capacidad_del_canal.ipynb) |
| 3.1–3.2 | [Distancia de Hamming: detectar no es lo mismo que corregir](vista_previa/tema_3_02_distancia_y_errores.html) | [Abrir en Colab](https://colab.research.google.com/github/msepulcre/tdi-ejemplos/blob/main/tema_3/02_distancia_y_errores.ipynb) |
| 3.2 | [Reed–Solomon: del mensaje a una palabra de símbolos de varios bits](vista_previa/tema_3_03_reed_solomon_simbolos.html) | [Abrir en Colab](https://colab.research.google.com/github/msepulcre/tdi-ejemplos/blob/main/tema_3/03_reed_solomon_simbolos.ipynb) |
| 3.4 | [Entrelazado: repartir una ráfaga sin eliminar errores](vista_previa/tema_3_04_rafagas_y_entrelazado.html) | [Abrir en Colab](https://colab.research.google.com/github/msepulcre/tdi-ejemplos/blob/main/tema_3/04_rafagas_y_entrelazado.ipynb) |
| 3.5 | [LDPC: ver la misma estructura en una matriz y en un grafo](vista_previa/tema_3_05_matriz_y_grafo_ldpc.html) | [Abrir en Colab](https://colab.research.google.com/github/msepulcre/tdi-ejemplos/blob/main/tema_3/05_matriz_y_grafo_ldpc.ipynb) |
| 4.1–4.3 | [Del símbolo a la muestra: canal, ruido y constelación](vista_previa/tema_4_01_modelos_del_canal_y_ruido.html) | [Abrir en Colab](https://colab.research.google.com/github/msepulcre/tdi-ejemplos/blob/main/tema_4/01_modelos_del_canal_y_ruido.ipynb) |
| 4.2–4.3 | [Un signo recibido no identifica siempre el símbolo: probabilidad y Bayes](vista_previa/tema_4_02_probabilidad_condicionada_y_bayes.html) | [Abrir en Colab](https://colab.research.google.com/github/msepulcre/tdi-ejemplos/blob/main/tema_4/02_probabilidad_condicionada_y_bayes.ipynb) |
| 4.4–4.5 | [Muestras que comparten ruido: covarianza, promedio y filtrado](vista_previa/tema_4_03_covarianza_y_ruido_filtrado.html) | [Abrir en Colab](https://colab.research.google.com/github/msepulcre/tdi-ejemplos/blob/main/tema_4/03_covarianza_y_ruido_filtrado.ipynb) |
| 4.3 y 4.5 | [Cuántos bits hacen falta: BER, variabilidad y cero errores](vista_previa/tema_4_04_ber_y_precision_del_experimento.html) | [Abrir en Colab](https://colab.research.google.com/github/msepulcre/tdi-ejemplos/blob/main/tema_4/04_ber_y_precision_del_experimento.ipynb) |

Las instrucciones de ejecución están dentro de cada cuaderno. Las figuras HTML se incluyen en cada archivo;
las fórmulas utilizan MathJax y pueden requerir conexión. Los cuadernos usan únicamente NumPy y Matplotlib
para los cálculos y no descargan datos ni instalan paquetes automáticamente.

## Uso de los cuadernos

En la web, pulsa **Abrir en Colab** para experimentar en el navegador. Las instrucciones están dentro del cuaderno.
También puedes descargar el archivo .ipynb y abrirlo en Jupyter local con NumPy y Matplotlib.

Los ejemplos de los temas 3 y 4 están aprobados. Cada tarjeta ofrece lectura HTML, apertura en Colab y descarga del cuaderno .ipynb.
