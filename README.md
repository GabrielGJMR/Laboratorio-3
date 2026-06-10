Laboratorio 3 - GmailDashboard

Aplicación web desarrollada con Spring Boot que permite a los usuarios iniciar sesión con su cuenta de Google (OAuth 2.0) y acceder a un dashboard personalizado donde se muestra su información de perfil (nombre, correo, foto y configuración regional).

Funcionalidad


Página de inicio (/) que muestra si el usuario ha iniciado sesión.
Inicio de sesión mediante Google OAuth 2.0 (/login).
Dashboard protegido (/dashboard) que muestra los datos del usuario autenticado: nombre, correo, foto de perfil, idioma/locale y la fecha y hora actual.
Cierre de sesión que invalida la sesión y redirige al inicio.


Tecnologías utilizadas


Java 21 + Spring Boot 4.0.6
Spring Security (OAuth 2.0 Login con Google)
Thymeleaf (con extras de Spring Security)
Maven
HTML / CSS


Video

https://drive.google.com/file/d/1o1bbxLVU27aK1Cjj9StfCZIAIc_Lsk47/view?usp=drive_link
