🚀 Seguimiento de Hábitos Deportivos
Un sistema para registrar, visualizar y gestionar entrenamientos deportivos, con funciones avanzadas para administradores.

📌 Funcionalidades
🔹 Usuario Normal
Registrar entrenamientos (tipo de actividad, duración, calorías quemadas, distancia recorrida).

Visualizar estadísticas personales: promedio de minutos entrenados, calorías quemadas y frecuencia de entrenamiento.

Filtrar entrenamientos por fecha, tipo de actividad o duración.

Imprimir historial en HTML.

Importar datos en CSV y JSON.

🔹 Usuario Administrador
Modificar registros de entrenamiento.

Gestionar la base de datos de ejercicios disponibles.

Configurar categorías de entrenamiento.

Exportar datos en múltiples formatos, incluyendo ZIP para respaldos.

🔐 Control de Acceso
Sin creación de cuentas. Solo login para admin cuando sea necesario.

Los usuarios ya están registrados en una tabla usuarios, con contraseña cifrada en bcrypt.

La visibilidad de elementos se controla según el rol del usuario.

🔄 Gestión de Sesión
Objeto Sesion para almacenar el usuario actual.

Activación/desactivación de funciones según el rol.

🖼️ Requisitos Adicionales
Imágenes de cada usuario y ejercicios disponibles.

Tests completos (excepto los controladores).
