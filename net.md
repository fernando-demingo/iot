---
marp:true
---

.NET (ASP, Entity Framework, WebAPI)
===

##### Luis Fernando de Mingo López 
##### 2019

---

# Configuración de idiomas `Locales`

 Cuando es interfaz gráfico está en *español* (los números con coma siguen el formato **X,XX**), pero sí el modelo de base de datos está en inglés (los números siguen el formato **X.XX**) toda la conversión de valores de los componentes en el *UI* puede ser que de errores en la validación automática que incluye el framework.

 En tal caso hay que modificar el fichero `webconfig` añadiendo lo que se denomina `cultures`, de la siguiente manera:

```xml
<system.web>
....
<globalization uiculture="es" culture="en" />
</system.web>
```

---

# Ajustar la cadena de conexión de un fichero que no está en el proyecto

A la hora de importar una solución y sí el fichero de base de datos no está incluido en el proyecto hay que modificar la cadena de conexión para especificar la ruta del fichero `.mdf`

```xml
<connection string="...">
```

---

# Versiones de drivers de SQL en Visual 2013 y 2017

`...\v11.0` por `...\MSSQLocalDB` en la cadena de conexión.

