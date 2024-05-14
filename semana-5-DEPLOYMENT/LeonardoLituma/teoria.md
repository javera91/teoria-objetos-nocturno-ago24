Leonardo Lituma // Jhonatan Cadme

# Introducción

El deployment de una aplicación NestJS es un proceso crucial para llevarla a producción y ponerla a disposición de los usuarios. Este proceso implica compilar la aplicación, empaquetarla y desplegarla en un entorno de hosting. Si bien existen diversas herramientas y plataformas para realizar el deployment, es importante comprender los principios subyacentes y las mejores prácticas para garantizar un despliegue exitoso.

# Teoría:

Los fundamentos del deployment en NestJS se basan en la comprensión del ciclo de vida de una aplicación y los conceptos de compilación, empaquetado y despliegue.

Ciclo de vida de una aplicación: El ciclo de vida de una aplicación comprende las etapas de desarrollo, pruebas, staging y producción. Cada etapa tiene sus propios objetivos y requisitos, y el deployment facilita la transición entre ellas.

Compilación: La compilación es el proceso de transformar el código fuente de la aplicación en código ejecutable. En NestJS, la compilación se realiza utilizando el comando nest build del CLI de NestJS.

Empaquetado: El empaquetado consiste en agrupar el código compilado, las dependencias y otros recursos necesarios para ejecutar la aplicación en un único paquete. En NestJS, el empaquetado se realiza utilizando herramientas como npm pack o yarn pack.

Despliegue: El despliegue es el proceso de transferir el paquete de la aplicación a un entorno de hosting y ejecutarlo. Existen diversas opciones de hosting para aplicaciones NestJS, como servidores en la nube, plataformas PaaS y servicios de hosting especializados.

# Reflexión:

El deployment de una aplicación NestJS no es solo un proceso técnico, sino que también implica una reflexión sobre la estrategia de desarrollo y las necesidades del proyecto.

Estrategia de desarrollo: La estrategia de desarrollo define cómo se construye, prueba y mantiene la aplicación. La elección de herramientas y prácticas de CI/CD puede influir significativamente en el proceso de deployment.

Necesidades del proyecto: Las necesidades del proyecto dictan el tipo de entorno de hosting y las configuraciones de despliegue requeridas. Aspectos como el escalado, la seguridad y el rendimiento deben considerarse al elegir una solución de deployment.

# Analogía:

Para ilustrar el concepto de deployment en NestJS, se puede utilizar la analogía de un libro.

Desarrollo: El desarrollo de una aplicación NestJS es similar a escribir un libro. El autor plasma sus ideas en el papel, organizando el contenido en capítulos y secciones.

Compilación: La compilación es como traducir el manuscrito a un idioma que pueda ser leído por una audiencia más amplia. El libro se convierte en un formato que puede ser entendido por diferentes lectores.

Empaquetado: El empaquetado es como preparar el libro para su distribución. Se crea una cubierta atractiva y se incluyen todos los elementos necesarios para que el libro llegue a los lectores.

Despliegue: El despliegue es como colocar el libro en una librería o tienda online. El libro se pone a disposición del público para que pueda ser adquirido y disfrutado.

# Bibliografia
NestJS Documentation - Deployment
Vercel - Deploying NestJS to Vercel
Heroku - Deploying NestJS to Heroku
Adaptable.io - Deploying a NestJS App
AWS - Deploying a NestJS Application to Amazon Elastic Beanstalk