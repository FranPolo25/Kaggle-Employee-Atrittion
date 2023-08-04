# Kaggle-Employee-Atrittion
Power Bi Proyect designed for Kaggle Employee Atrittion database

Online Visualization on: https://app.powerbi.com/reportEmbed?reportId=f2805570-c02b-4b66-ae62-eea80e8f4d22&autoAuth=true&ctid=92e84ceb-fbfd-47ab-be52-080c6b87953f 
El nivel de satisfacción y/o desercción de los empleados es una de las problemáticas actuales que más duelen a las empresas. El costo de capacitación y rotación de personal llega a generar costos muy altos
Importación y uso de librerías como Scikit Learn, Numpy, Matplotlib, Pandas, Google Colab
Lenguaje utilizado: Python
Plataformas utilizadas: Google Drive, Google Colab, Power BI
Base de datos utilizada: Kaggle-Employee-Attrition.csv
Temas o herramientas utilizadas:
Lectura y preprocesamiento del conjunto de datos, resumen conciso de la información 
Limpieza de datos, eliminación de variables no útiles para nuestro objetivo 
One Hot Encoding, Variables Dummy
Normalización de los datos utilizando librerías de sklearn.preprocessing import MinMaxScaler, StandardScaler, RobustScaler
Creación de conjuntos de entrenamiento y prueba utilizando la librería de sklearn.model_selection import train_test_split
Creación de modelos de aprendizaje: 
•	Bosque aleatorio 
	Librería utilizada: from sklearn.model_selection import cross_validate
	Librería utilizada: from sklearn.ensemble import RandomForestClassifier
o	Busqueda de mejores hiperparámetros 
	Librería utilizada: sklearn.model_selection import GridSearchCV
o	Matriz de confusión y métricas de evaluación del conjunto de prueba
	Librería utilizada: from sklearn.metrics import ConfusionMatrixDisplay
	Librería utilizada: from sklearn.metrics import classification_report
•	Regresión Logística
	Librería utilizada: from sklearn.linear_model import LogisticRegression
o	Busqueda de mejores hiperparámetros 
	Librería utilizada: from sklearn.model_selection import RandomizedSearchCV
o	Matriz de confusión y métricas de evaluación del conjunto de prueba
•	Bayes Ingenuo Gaussiano
	Librería utilizada: from sklearn.naive_bayes import GaussianNB
o	Matriz de confusión y métricas de evaluación del conjunto de prueba
•	Máquina de Vectores de soporte
	Librería utilizada: from sklearn.svm import SVC
o	Busqueda de mejores hiperparámetros 
o	Matriz de confusión y métricas de evaluación del conjunto de prueba
Análisis de determinación del mejor modelo de aprendizaje meduante Curva ROC y métrica AUC 
o	Librería utilizada: from sklearn.metrics import RocCurveDisplay
Conclusiones obtenidas
