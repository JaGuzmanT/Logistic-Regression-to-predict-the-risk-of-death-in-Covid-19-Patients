Estimation of the main conditions in (SARS-CoV-2) Covid-19 patients that cause their death using Machine learning, the case of Mexico
Description of the repository
This repository contains 1 folder named Model with 1 notebook, Feature selection and model.

Features type: Multiclass(Categorical and Ordinal)
Features: 
ID_REGISTRO           object
ORIGEN                object
SECTOR                object
ENTIDAD_UM             int64
SEXO                  object
ENTIDAD_NAC            int64
ENTIDAD_RES            int64
MUNICIPIO_RES          int64
TIPO_PACIENTE         object
FECHA_INGRESO         object
FECHA_SINTOMAS        object
FECHA_DEF             object
INTUBADO              object
NEUMONIA              object
EDAD                   int64
NACIONALIDAD          object
EMBARAZO              object
HABLA_LENGUA_INDIG    object
DIABETES              object
EPOC                  object
ASMA                  object
INMUSUPR              object
HIPERTENSION          object
OTRA_COM              object
CARDIOVASCULAR        object
OBESIDAD              object
RENAL_CRONICA         object
TABAQUISMO            object
OTRO_CASO             object
MIGRANTE               int64
PAIS_NACIONALIDAD     object
PAIS_ORIGEN           object
UCI                   object
RESULTADO             object
MORTALIDAD             int64

Target: MORTALIDAD (Categorical feature)

Type of problem: Supervised and Regression problem

Regressor: Logistic Regression.

##Note: The dataset is contained in the file.rar, If you want to try with other datset you just need to change the name of the file.csv in the first notebook according to the name of your file.
