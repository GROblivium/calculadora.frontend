Para ingresar a la calculadora, hay dos opciones diferentes: 

1.-  Haciendo click direcamente en el archivo calculadora.html, el cual desplegará automáticamente el proyecto.

2.- Desde la página principal de Te lo Vendo (index.html) en la esquina superior derecha se encuentra el link  "Saca la cuenta" el que redirige automáticamente hasta nuestra calculadora.

Las funciones que podemos realizar con esta herramienta son:

- Operaciones básicas como sumas, restas, multiplicaciones y divisiones.
- Obtener la raíz cuadrada y la potencia 2 de los números ingresados.
- No se puede dividir por 0
- No se pueden ingresar letras.
- No recibirá más de un operador seguido, pero puede ayudarse de los paréntesis para ingresar números negativos
ej "9*(-5)= -45"




-----------------------

Para configurar el proyeto en el repositorio debemos asegurarnos primero de tener configurado nuestro repositorio local a través de la consola que más nos acomode.

1.  Situarse en la carpeta elegida como repositorio local. (Puede crearse directamente en la consola a través de mkdir 'nombre-de-carpeta')
2. Ingresar " git config --global user.mail "micorreo@correo.cl" para la configuración
3. Iniciar el repositorio con "git init"
4. Escribir "git add 'nombre'"para agregar los archivos por su nombre o reemplazar el nombre por un punto (.) para agregar todo.
5. Con " git commit -m "'un mensaje descriptivo de los cambios'" " se actualizan los archivos de nuestro repositorio local para guardar los cambios realizados.
6. Si deseamos subirlo a repositorio remoto (GitHub) como es el caso de esta calculadora, la plataforma nos entrega estas líneas que deben copiarse en la consola una vez creado el repositorio remoto.
git remote add origin https://github.com/Miusario/miproyecto.git
git branch -M main
git push -u origin maingit remote add origin https://github.com/Miusario/miproyecto.git
git branch -M main
git push -u origin main
Con esto podemos ver remotamente todos los proyectos en los que estamos trabajando.

7. Para actualizar el repositorio remoto con el local, repetir los pasos 4 Y 5. 
8. El comando "git push" actualiza los cambios hechos en local al repositorio remoto. 