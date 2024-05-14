## Arquitectura en NestJS

JavaScript es un lenguaje muy útil para desarrollar programación Front-End en servidores pero tiene serias deficiencias a la hora de gestionar datos en el Back-End, lo cual puede hacer difícil el desarrollo de aplicaciones usando este lenguaje sin ninguna otra herramienta. 

Node es un entorno de ejecución del código JS del lado del servidor lo que permite ampliar la capacidad de JS ya que maneja un modelo de entrada y salida sin bloqueo y dirigido a eventos, esto significa que puede gestionar múltiples solicitudes de forma concurrente sin bloquear el hilo principal de la ejecución. Node permite usar módulos predeterminados para dividir el código de manera eficiente y gestionar mejor la dependencias, Nde incluye un extenso paquete de dependencias que pueden ser instaladas dependiendo del tipo de proyecto que tengamos en mente.

Para la elaboración de aplicaciones un  framework recomendado es NestJS, que permite una arquitectura modular y escalables inspirada en los principios de angular pero centrados en el Back-End. NestJS está escrito en TypeScript y ofrece un soporte completo para este lenguaje, a su vez puede soportar trabajar con herramientas de gestión de bases de datos mediante la inyección de dependencias.

Para instalar nest usamos: npm install -g @nestjs/cli

Creamos un nuevo proyecto con: nest new my-nest-project

Ejecutamos nuestro código en modo desarrollador con: npm run start:dev

## Reflexión

Al estudiar la arquitectura de NestJS, se observa que su enfoque en la modularidad y la organización estructurada del código facilita el desarrollo ágil y eficiente de aplicaciones. La capacidad de utilizar TypeScript, un lenguaje de programación tipado estáticamente, también contribuye a la creación de aplicaciones más seguras y menos propensas a errores. Sin embargo, el aprendizaje inicial de NestJS puede ser desafiante para aquellos que no están familiarizados con los principios de programación orientada a objetos o programación reactiva.

## Analogía

La arquitectura de NestJS se asemeja a la construcción de un edificio bien diseñado y estructurado. Los controladores actúan como los cimientos del edificio, proporcionando una base sólida para la aplicación. Los servicios son como los distintos pisos del edificio, cada uno con su propia función y responsabilidad. Los módulos son como las diferentes secciones del edificio, cada una con su propio propósito y recursos. Al igual que en la construcción de un edificio, la arquitectura de NestJS requiere una planificación cuidadosa y una ejecución meticulosa para garantizar la estabilidad y la longevidad de la aplicación.

## Resumen

En resumen, NestJS proporciona una serie de características y herramientas que hacen que el desarrollo de aplicaciones web con Node.js sea más eficiente, estructurado y productivo. Si estás desarrollando una aplicación web con Node.js y TypeScript, NestJS puede ser una excelente opción para simplificar y acelerar el proceso de desarrollo.

## Referencias

NestJS. (s.f.). Documentación de NestJS. Recuperado de https://docs.nestjs.com/

OpenWebinars. (s.f.). ¿Qué es Node.js?. OpenWebinars. Recuperado de https://openwebinars.net/blog/que-es-nodejs/

Vallejo, J. (S.f.). Curso básico de Nestjs [Diapositivas de PowerPoint]. Instituto de tecnologías Sudamericano, Cuenca, Ecuador.
