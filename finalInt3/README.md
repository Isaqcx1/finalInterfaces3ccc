===========================================
   SISTEMA DE GESTIÓN DE CURSOS - ANGULAR
===========================================

Este proyecto es una aplicación web desarrollada con:
- Frontend: Angular
- Backend: Node.js + Express
- Autenticación: JWT
- Base de datos temporal en memoria

Permite gestionar:
- Usuarios
- Cursos
- Inscripciones
- Panel de administrador
- Reportes

===========================================
1. CLONAR EL PROYECTO DESDE GITHUB
===========================================

Primero debes clonar el proyecto desde GitHub con el siguiente comando:

git clone https://github.com/Isaqcx1/finalInterfaces3ccc

Luego entras a la carpeta del proyecto:

cd finalInt3



===========================================
2. INICIAR EL BACKEND (API)
===========================================

Desde la carpeta del proyecto, entra a la carpeta backend:

cd backend

Instala las dependencias (solo la primera vez):

npm install

Luego inicia el servidor:

node server.js

La API se ejecutará en:

http://localhost:3000

===========================================
3. INICIAR EL FRONTEND (ANGULAR)
===========================================

Abre otra terminal (sin cerrar el backend) y entra a la carpeta del frontend:

cd finalInt3

Instala las dependencias (solo la primera vez):

npm install

Luego ejecuta Angular:

npm install --legacy-peer-deps

La aplicación se abrirá en el navegador en:

http://localhost:4200

===========================================
4. USUARIOS PARA INICIAR SESIÓN
===========================================

USUARIO ADMINISTRADOR:
Usuario: admin
Contraseña: 123

Este usuario puede:
- Crear cursos
- Editar cursos
- Eliminar cursos
- Ver usuarios registrados
- Eliminar usuarios
- Ver reportes
- Ver monto total
- Ver inscripciones

USUARIOS NORMALES:
Se pueden crear desde el formulario de registro en la aplicación.

Los usuarios pueden:
- Ver cursos activos
- Inscribirse en cursos
- Ver sus cursos inscritos
- Eliminar cursos inscritos
- Editar su perfil

===========================================
5. FUNCIONALIDADES PRINCIPALES
===========================================

- Login con JWT
- Rutas protegidas con Guards
- Control de acceso por rol (admin y usuario)
- CRUD completo de cursos
- Gestión de usuarios
- Sistema de inscripciones
- Reportes generales:
  - Total de usuarios
  - Total de cursos
  - Total de inscripciones
  - Monto total recaudado

===========================================
6. NOTAS IMPORTANTES
===========================================

- El backend usa almacenamiento en memoria, por lo tanto:
  - Si se apaga el servidor, los cursos se borran.
- El frontend usa Angular Standalone Components.
- El sistema es solo con fines educativos.

===========================================
AUTOR: (Grupo:
SALVINIA PALOMINO OCHOA 
ISAAC GAVIDIA RIOJA 
GOSFREY ARMANDO LOPEZ FLORES 
DANIEL ALESSANDER GUILLÉN RIOS )

CURSO: (Desarrollo de interfaces 3)
FECHA: (9 de diciembre 2025)
===========================================