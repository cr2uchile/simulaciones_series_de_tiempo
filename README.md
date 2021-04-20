# simulaciones_series_de_tiempo
* ¿cómo descargarlas a través del ftp?
* ¿cómo extraer una serie de tiempo usando simulaciones globales? 


Lo puedes realizar utilizando un simple código en python para esto debes solicitar acceso al ftp del centro completando el formulario de acceso en:  http://www.cr2.cl/simulaciones-regionales-regcm4/ el cual contiene las simulaciones globales, regionales y locales presentes en la plataforma de simulaciones climáticas http://simulaciones.cr2.cl. Estas simulaciones se encuentran principalmente en formato NetCDF, un formato complejo grillado tipo ráster. Si deseas extraer información de una localidad específica (latitud, longitud) puedes utilizar estos programas o utilizar la plataforma de simulaciones. 
Puedes extraer esta información desde el ftp como se muestra a continuación, recuerda que también puedes utilizar un software menos complejo como Filezilla para navegar. El resultado es obtener un csv con la serie de tiempo obtenida a través de alguna simulacion en particular.

Estos son ejemplos básicos, para que puedas empezar a trabajar con estos datos en python, existen otros programas para inspeccionar estas simulaciones como ncdump, ncview, panoply, nco, cdo, entre otras.

# Ejemplos

* Uso para simulaciones globales cmip5
  * download_sim_cmip5_from_ftp.py  
  * sim_cmip5.py
  * tas_CMIP5_time_series_from_netcdf.csv   
* Uso simulaciones regionales para Chile RegCM4
  * download_sim_regcm_from_ftp.py
  * sim_regcm.py
  * tas_RegCM4_time_series_from_netcdf.csv   
