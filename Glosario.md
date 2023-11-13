# Glosario

En esta imagen se pueden leer el signficado de cada variable del data frame antes de realizarle modificaciones

![image](https://user-images.githubusercontent.com/118769777/220240501-8c21461d-2de5-495b-954e-10fb9bf38014.png)

### Hospitalizacion ETL

**dataframe** = dataframe que contiene los valores de la base de datos provista  
**duplicados** = Contiene los duplicados de nuestro dataframe  
**data** = dataframe sin duplicados y sin nulos  
**registros_Nan** = cantidad de registros con valores Nan(Nulos)  
**totalnan** = division de registros_Nan por el total de registros   
**porcentajenan** = es el resultado en porcentaje de totalnan  
**nombres** = diccionario que contiene todos los nuevos nombres de las columnas  

### Hospitalizacion EDA

**data** = dataframe limpio  
**conteo_infeccion** = contador de dias con infeccion con valor 0  
**len_infeccion** = longitud de la columna dias con infeccion    
**conteo_dias_mq** = contador de dias en medico qirurgico con valor 0  
**len_dias_mq** = longitud de la columna dias en medico qirurgico  
**conteo_dias_upc** = contador de dias upc con valor 0  
**len_dias_upc** = longitud de la columna dias upc  
**conteo_hosp_ult_mes** = contador de hospitalizacion en el ultimo mes con valor "NO"  
**len_hos_ult_mes** = longitud de la columna hospitaliz_ultimo_mes  
**conteo_cup** = contador de CUP con valor "NO"  
**len_cup** = longitud de la columna Cup  
**conteo_Epoc** = contador de CUP con valor "NO"  
**len_Epoc** = longitud de la columna Epoc  
**conteo_itu** = contador de ITU con valor "NO"  
**len_itu** = longitud de la columna Itu  
**conteo_cultivo** = contador de tipo de cultivo con valor "NO"  
**len_cultivo** = longitud de la columna Tipo_cultivo  
**conteo_agente** = contador de agente aislado con valor "NO"  
**len_agente** = longitud de la columna Agente_aislado  
**conteo_patron** = contador de patron de resistencia con valor "NO"  
**len_patron** = longitud de la columna Patron_resistencia  
**mapeo_resto** = mapeos segun los valores que tenia cada columna, los valores posibles son: SI = 1 y NO = 0  
**mapeo_antibiotico** = mapeo de valores para los tipos de antibioticos   
**mapeo_biopsia** = mapeo de valores para los tipos de biopsia  
**corr** = grafico de correlaciones entre las variables  

### Hospitalizacion Modelo

**data** = dataframe codificado para el modelo  
**X1** = dataframe sin la columna Hospitalizacion(variable objetivo)  
**Y** = dataframe de la variable objetivo  
**escalador** = objeto de clase minmaxscaler  
**X** = dataframe escalado para que todas las variables tengan la misma escala  
**X_train** = Subconjunto con datos de entrenamiento  
**X_test** = Subconjunto con datos de evaluacion  
**Y_train** = Subconjunto con etiquetas de entrenamiento  
**Y_test** = Subconjunto con etiquetas para evaluacion  
**modelo** = objeto de la clase LogisticRegression  
**y_test_pred** = contiene las etiquetas predichas con el subconjunto X_test  
**y_train_pred** = contiene las etiquetas predichas con el subconjunto X_train  
**acc_score** = metrica de evaluaion de modelo  
**precision** = metrica de evaluacion que combina precision y sensibilidad  
**cruzada_Score** = metrica de evaluaion de modelo  
**matrix** = matriz de confusion para evaluar el modelo  
**cm_display** = objeto de la clase ConfusionMatrixDisplay para visualizar la matriz de confusion  
**sensibilidad** = capacidad para identificar los casos positivos  
**especificidad** = capacidad para identificar los casos negativos  


