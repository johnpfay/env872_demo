---
Title: datos_abiertos_vigilancia_malaria.csv
Download Date: 2 April 2024
Download Site: https://www.datosabiertos.gob.pe/dataset/vigilancia-epidemiol%C3%B3gica-de-malaria/resource/a1ddd151-59aa-49f8-9c20-5e9a3eca9307
Downloaded by: john.fay@duke.edu
Description: https://www.datosabiertos.gob.pe/dataset/vigilancia-epidemiol%C3%B3gica-de-malaria
---

# `datos_abiertos_vigilancia_malaria.csv`

### Dataset reporting malaria to Peru's public health surveillance system

This dataset contains information on the reporting of **malaria** cases  to Peru's public health surveillance system, managed and administered by the **National Center for Disease Epidemiology, Prevention and Control (CDC PERU**). The data come from the **National Epidemiology Network (RENACE**), which consists **of 10 034 health establishments** of the Ministry of Health, EsSalud and others in the sector at the  different levels of Peru's Regional Health Directorates. Of these, **8 105 are Notificating Units**, recognized with Directorial Resolution of the respective  Diresas/Geresas de Salud of Peru. Dataset information is updated every  week or month, according to the trend section of the epidemiological  bulletin, and is provided weekly by RENACE. The data and analysis are  provisional and may be subject to modification. Dataset aims to provide  information on the epidemiological situation of dengue in Peru, as well  as to facilitate access to open data for research, education, prevention and control of this disease.

The dataset contemplates a historical series from 2000 to 2022, with  data disaggregated by department, province, district, disease, year,  week, diagnosis, type of diagnosis, health direction, ubigeo, age, type  of age and sex. Dataset includes the following variables:

| CAMPO        | TIPO     | DENOMINACIÓN                           | VALORES                                     |
| ------------ | -------- | -------------------------------------- | ------------------------------------------- |
| departamento | Caracter | Región geográfica                      |                                             |
| provincia    | Caracter | Provincia                              |                                             |
| distrito     | Caracter | Lugar probable de infección            |                                             |
| enfermedad   | Caracter | Diagnóstico vigilado                   |                                             |
| ano          | Integer  | Año                                    |                                             |
| semana       | Integer  | Semana de inicio de síntomas           |                                             |
| diagnostic   | Caracter | CIE 10                                 |                                             |
| tipo_dx      | Caracter | Tipo de diagnóstico                    | C= Confirmado, P = Probable, S = Sospechoso |
| diresa       | Caracter | Dirección de salud que notifica        |                                             |
| ubigeo       | Caracter | Código del lugar probable de infección |                                             |
| edad         | Caracter | Edad del paciente                      |                                             |
| tipo_edad    | Caracter | Tipo de edad del paciente              | A = Año, M = Mes, D = Días                  |
| sexo         | Caracter | Sexo                                   | M = Masculino, F = Femenino                 |