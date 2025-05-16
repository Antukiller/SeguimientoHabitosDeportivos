🏃 Seguimiento de Hábitos Deportivos
Una aplicación de escritorio JavaFX para registrar, visualizar y gestionar entrenamientos físicos, con funcionalidades diferenciadas para usuarios normales y administradores. Implementa arquitectura MVVM, control de errores basado en Railway Oriented Programming (ROP), almacenamiento local en SQLite y soporte para importación/exportación en múltiples formatos.

🚀 Funcionalidades Principales
🔹 Usuario Normal
📝 Registro de entrenamientos
Añadir datos sobre actividades deportivas:

Tipo de actividad (carrera, ciclismo, natación, etc.)

Duración (en minutos)

Calorías quemadas

Distancia recorrida

📊 Visualización de estadísticas personales

Promedio de minutos entrenados

Promedio de calorías quemadas

Frecuencia de entrenamiento semanal/mensual

🔍 Filtrado y búsqueda de entrenamientos

Por fecha

Por tipo de actividad

Por duración

🖨️ Impresión de historial en HTML
Generación de un historial visualmente atractivo, listo para imprimir o guardar.

📥 Importación de datos

Desde archivos .csv y .json

🔹 Usuario Administrador
El modo administrador requiere inicio de sesión (login) para acceder a funciones avanzadas. Las credenciales están cifradas con bcrypt y almacenadas en la base de datos.

✏️ Modificación y eliminación de entrenamientos existentes

⚙️ Gestión de ejercicios disponibles

Crear, editar o eliminar tipos de actividad

🗂️ Configuración de categorías de entrenamiento personalizadas

📤 Exportación de datos

A formatos .json, .csv y .zip (para respaldos)

🔐 Acceso restringido por rol

Los botones, menús y acciones avanzadas solo se activan si el usuario es administrador

🔐 Control de Acceso y Sesión
📛 No hay creación de cuentas
Los usuarios están predefinidos en la base de datos (usuarios), con su rol y contraseña encriptada.

👤 Sistema de sesión con objeto Sesion
Almacena el usuario actual e informa al sistema si el rol es admin.

👁️‍🗨️ Visibilidad dinámica
El sistema activa o desactiva componentes de la interfaz en función del rol del usuario (normal o admin).

📦 Estructura Técnica
🏗️ Arquitectura: MVVM

💾 Almacenamiento local: SQLite

📚 Serialización: Gson

🧪 Control de errores: Railway Oriented Programming (ROP)

🧪 Tests unitarios completos (excepto controladores de vista)

🖼️ Requisitos Adicionales
📷 Cada usuario y tipo de ejercicio cuenta con una imagen asociada.

🔄 Splash Screen inicial incluido.

💻 App multiplataforma, diseño adaptable.

