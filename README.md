# Crackeo de contraseñas con JTR

## Resumen:

  Este proyecto tiene como objetivo realizar un análisis detallado sobre la fortaleza de contraseñas en un entorno Kali Linux, utilizando herramientas avanzadas de ciberseguridad.
A través de la generación de diferentes conjuntos de contraseñas y el uso de estrategias de ataque con John the Ripper, se mide el esfuerzo necesario para vulnerar dichas contraseñas.

## Características clave:

### Generación de Contraseñas:

  Se han creado 25 datasets de 100 contraseñas cada uno, variando en complejidad y longitud (entre 3 y 7 caracteres). Los conjuntos incluyen:
    - Letras minúsculas
    - Letras mayúsculas
    - Números
    - Combinaciones alfanuméricas y símbolos
    - Palabras tomadas de un diccionario

### Evaluación en Kali Linux:

  Todos los experimentos y estrategias de ataque se ejecutaron directamente desde la terminal de Kali Linux, aprovechando el entorno especializado en ciberseguridad. 
Se aplicaron 5 estrategias diferentes de rotura de contraseñas, registrando el porcentaje de contraseñas vulneradas y el tiempo promedio de ataque.
  
## Tecnologías:

  - **Kali Linux:** plataforma utilizada para ejecutar todos los experimentos y ataques de rotura de contraseñas.
  - **John the Ripper:** herramienta principal para realizar los ataques de fuerza bruta y analizar la fortaleza de las contraseñas.
  - **Comando de terminal en Linux:** empleados en la generación de los datasets y la automatización del análisis de resultados.

## Memoria:

  El informe adjunto detalla el proceso llevado a cabo en Kali Linux, explicando la metodología empleada para la creación de los datasets mediante comandos en la terminal, las configuraciones utilizadas en John the Ripper y los resultados obtenidos para cada estrategia. 
Además, se explican los scripts y comandos empleados para generar contraseñas y analizar los resultados, junto con las principales conclusiones derivadas de los experimentos.

[memoria.pdf](https://github.com/Ari-Potente/Password-Cracking-with-JTR/blob/main/Practica1_Ciberseguridad_Memoria.pdf)
