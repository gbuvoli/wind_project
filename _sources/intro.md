# Wind Speed ML Project

## 1. Descripción del problema

<!--El problema inicia con una contextualización en donde se proporciona un contexto amplio sobre el área o el sector al que pertenece el problema. Esto puede incluir antecedentes históricos, tendencias actuales y cualquier información relevante sobre el ámbito específico en el que se encuentra el problema. 

Posteriormente se identifica el problema específico, es decir, se debe describir de manera clara y precisa el problema específico que se abordará en el proyecto. Esto implica definir claramente las limitaciones, deficiencias o desafíos existentes en el área de estudio, en relación con el análisis de datos. Algo muy importante es medir o tener claro métricas para cuantificar el problema en su estado actual. -->


La predicción precisa de la velocidad del viento es crucial en diversas industrias, como la generación de energía eólica, la aviación, la navegación y la gestión de desastres naturales ***Agregar cifras y referencias aqui***. En la generación de energía eólica, por ejemplo, la capacidad de prever la velocidad del viento con precisión permite una mejor planificación de la producción de energía y la gestión eficiente de recursos ***agregar cifras y referencias aquí**.
Dependiendo del propósito de la predicción, se puede considerar ventanas muy pequeñas de un par de horas, pero también interesa predecir periodos de tiempo más amplios, como varios días.
En la última décana, la masificación de los modelos de Machine Learning han permitido a científicos de todo el mundo obtener resultados prometedores en cuanto a la precisión de las predicciones de velocidad del viento en diferentes ventanas de tiempo y para condiciones particulares, logrando  ***Agregar aquí algunos resultados obtenidos de la bibliografía***

Para el propósito particular de esta propuesta, contamos con mediciones realizadas cada hora, durante un periodo de 10 años de factores como `Humedad Minima`, ``Humedad Maxima``, `Presión Atmosferica`, `Precipitación total`, `dirección del viento`, `velocidad del viento`.
Con esto datos, el reto está en encontrar la ventana o periodos de tiempo en los que podamos obtener las mejores predicciones en términos de `Accuracy` y `RMSE`.

Sabemos que no existe un modelo, fórmula o metodología definida que funcione de manera general para todos los casos, por lo que el desafío consiste en generar un modelo de Machine Learning adecuado para este caso particular.

A partir de la revisión de bibliografía, podemos identificar algunos procesos que aportaron una mejora significativa de resultados, como por ejemplo, en ****** 


** AQUI VA INFORMACION RESPECTO AL AREA DE ESTUDIO **







Modelos de Machine Learning para Predicciones de Velocidad del Viento:

Redes Neuronales Recurrentes (RNN):

Las RNN son efectivas para modelar secuencias temporales, como los datos de velocidad del viento a lo largo del tiempo. Autores como Zhang et al. (2019) han explorado el uso de RNN en la predicción de la velocidad del viento.
Máquinas de Vectores de Soporte (SVM):

Las SVM son utilizadas para problemas de regresión, incluyendo la predicción de velocidad del viento. Chen et al. (2010) proporcionan un ejemplo de aplicación de SVM en la predicción de velocidad del viento.
Random Forest y Gradient Boosting:

Algoritmos de ensamblaje como Random Forest y Gradient Boosting también se han aplicado con éxito en la predicción de velocidad del viento. Wang et al. (2011) presentan un enfoque utilizando Random Forest para mejorar la precisión de la predicción.
Modelos Híbridos:

Algunos estudios han propuesto enfoques híbridos que combinan diferentes modelos de machine learning para mejorar la precisión de las predicciones. Wang et al. (2015) proponen un modelo híbrido que combina Wavelet Transform y Support Vector Machine.
Evaluación y Desafíos:
La evaluación de modelos de predicción de velocidad del viento generalmente se realiza utilizando métricas como el Error Absoluto Medio (MAE) o el Error Cuadrático Medio (MSE). Sin embargo, la complejidad de los patrones del viento y la variabilidad temporal presenta desafíos significativos en este campo.






the uncertainty of wind speed becomes a challenging task
Wind speed has the characteristics of uncertainty and high
volatility [3].

Despite
the current rate of the growth, it will still fall short of meeting the goal of
achieving zero global emissions by 2050. It is necessary to continue the
technological innovation of wind power industry and accelerate the
adjustment measures of the energy market. The accuracy of wind speed
prediction should be achieved first. Accurate wind speed prediction is
essential to ensure the safe and stable operation of the power system. It
can also promote the further development of the wind power industry
[2]. According to the different time intervals of wind speed data, Wind
speed prediction is divided into ultra-short-term wind speed prediction,
short-term wind speed, medium-term wind speed and long-term wind
speed.

In recent years, wind speed prediction has received widespread
attention. Wind speed has the characteristics of uncertainty and high
volatility [3]. At the same time, the formation of wind speed is also
affected by many factors. Wind speed prediction can be roughly divided
into three categories: physical models [4], traditional statistical models
[5] and machine learning models [6]. Physical models are inseparable
from geographical and meteorological factors [7]. Physical models have
strong predictability and stable prediction accuracy for long-term forecasts.
In the early stage of the research, traditional statistical models
including AR(Auto Regression) [8], ARCH (Auto Regressive Conditionally
Heteroscedasticity) [9], ARIMA (Autoregressive Integrated Moving
Average) [10], ARIMAX(ARIMA with exogenous variables) [11] were
proposed to forecast the given time series. However, the adaptability of
these models is relatively poor and the prediction accuracy is not enough
for time series with large fluctuations. What’s more, the statistical
models usually require the time series to be stable, or stable after differentiation.
According to the advantages and disadvantages of the
above two models, this paper considers the use of machine learning
models for wind speed prediction, which are more suitable for processing
large amounts of data with high volatility [12].


The randomness of wind speed and the performance of prediction models are the two issues that have the greatest impact
on wind speed prediction.  He wanga


lead time of four days, which is meaningful for the wind
power industry.  

Decomposition of the serie




## 2. Revisión de la literatura inicial 

<!--Consultar al menos cinco referencias en inglés en donde se resuelva un problema similar o equivalente al planteado en el proyecto, es clave que se analice cuál de los modelos o metodologías descritas puede ser aplicada para el desarrollo del proyecto. -->



## 3. Objetivo General 

 <!-- Una idea general de como se piensa resolver el problema planteado. En la estructura del objetivo se recomienda que en su formulación se incluya lo que se va a hacer, la(s) herramienta(s) a utilizar, y el propósito que se busca.-->

"**Mejorar las predicciones** de velocidad del viento **mediante** la implementación de un modelo de Machine Learning innovador, **para** optimizar la precisión y el RMSE obtenidos mediante los modelos tradicionales."


-----------------------------------------------------
:::{note}
Here is a note!
:::

And here is a code block:

```
e = mc^2
```

Check out the content pages bundled with this sample book to see more.
