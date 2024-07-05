**Objetivo General:** Desarrollar un soft sensor mediante un método de ensamble heterogéneo que permita predecir con precisión la producción de penicilina en un bioreactor industrial utilizando el conjunto de datos IndPenSim para el Centro de Investigación de Agricultura y Alimentación (INRAe) de Toulouse – Francia. 

**Objetivos Específicos:**
1. Seleccionar y procesar las variables on-line del conjunto de datos IndPenSim.
2. Verificar el rendimiento de cinco modelos: Lasso, KNN, ANN, XGBoost y SVR, en la predicción de penicilina utilizando el conjunto de datos IndPenSim seleccionado y procesado.
3. Desarrollar un soft sensor a partir de un ensamble heterogéneo utilizando los modelos verificados anteriormente.
4. Evaluar el rendimiento del soft sensor en comparación con los modelos individuales y con lo reportado en la literatura.
5. El experimento como tal consta de 100 lotes, estos se controlan utilizando diferentes estrategias de control en diferentes lotes, así, representando un proceso de fabricación biofarmacéutica típica de la siguiente manera:

    Lotes 1-30: Controlado por un enfoque basado en recetas.
    Lotes 31-60: Controlados por operarios.
    Lotes 61-90: Controlados por una solución de control avanzado de procesos (APC) mediante espectroscopia Raman.
    Lotes 91-100: Contienen fallos que provocan desviaciones del proceso.
