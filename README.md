Proyecto Telecom-X - Análisis de Evasión de Clientes

Descripción
Este proyecto corresponde al análisis de evasión de clientes en una compañía ficticia de telecomunicaciones, Telecom-X.
El trabajo sigue el enfoque ETL ("Extract, Transform, Load") complementado con análisis exploratorio de datos ("EDA") y generación de insights de negocio.

Objetivos
Extraer y preparar los datos de los clientes desde un archivo JSON.
Transformar y limpiar los datos para obtener un dataset estructurado.
Analizar patrones de evasión de clientes en variables numéricas y categóricas.
Generar un informe final con conclusiones y recomendaciones estratégicas.

Documentos
Dataset original en formato JSON
Telecom-X-Alura.ipynb 
Informe_Final.md
README.md

Tecnologías
Python 3.10+
Pandas
NumPy
Matplotlib
Seaborn
Google Colab


Resultados principales
Los clientes con contratos mes a mes tienen mayor tasa de cancelación.
Métodos de pago automáticos como tarjeta o transferencia bancaria muestran menor churn.
Los clientes con antigüedad baja < 12 meses cancelan más frecuentemente.
Los cargos mensuales altos se asocian a mayor evasión.

Reproducibilidad
Clonar el repositorio: git clone https://github.com/tuusuario/Telecom-X-Alura.git cd Telecom-X-Alura

Instalar dependencias: pip install -r requirements.txt
Abrir el notebook: jupyter notebook notebooks/Telecom-X-Alura.ipynb

Autor
Proyecto desarrollado por Santiago Mesa participante del programa Alura ONE - Data Science.
