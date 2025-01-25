# CashFlowApp
**Descripción del Proyecto:**
Backend (Node.js y MongoDB):
Node.js: Plataforma de JavaScript del lado del servidor que permite ejecutar código JavaScript en el servidor, ideal para crear aplicaciones escalables y rápidas.
Express.js: Framework web para Node.js que facilita la creación de APIs, manejando las rutas y peticiones HTTP de manera sencilla.
MongoDB: Base de datos NoSQL que almacena datos en formato de documentos JSON, lo que la hace ideal para manejar datos semi-estructurados. Se utiliza para guardar las transacciones de ingresos y gastos.
Mongoose: ODM (Object Data Modeling) para MongoDB, que permite interactuar con la base de datos utilizando objetos JavaScript, haciendo más fácil la gestión de datos en MongoDB.
Dotenv: Biblioteca para gestionar variables de entorno en Node.js, útil para almacenar información sensible como las credenciales de la base de datos.
CORS: Middleware para permitir solicitudes entre diferentes orígenes (cross-origin requests), necesario para que la app frontend y el backend puedan comunicarse.
Frontend (React Native):
React Native: Framework para desarrollar aplicaciones móviles nativas utilizando JavaScript y React. Permite crear aplicaciones tanto para Android como para iOS con el mismo código base.
Axios: Biblioteca para hacer solicitudes HTTP desde el frontend. Se utiliza para enviar y recibir datos entre el frontend y el backend (por ejemplo, cargar las transacciones).
React: Biblioteca de JavaScript para construir interfaces de usuario. En este caso, se usa dentro de React Native para manejar el estado de la aplicación y las interacciones del usuario.
FlatList: Componente de React Native que se utiliza para mostrar listas de datos, como las transacciones cargadas en la aplicación.
Funcionalidades Clave del Proyecto:
Manejo de Transacciones: El backend gestiona los registros de ingresos y gastos, permitiendo su carga, consulta y actualización.
Aprobación de Transacciones: Las transacciones pueden ser aprobadas por un encargado o administración para reflejar su estado.
Control por Sucursal: Cada sucursal solo puede ver sus propias transacciones, mientras que los encargados generales pueden ver todas las sucursales.
Interfaz Móvil: La app permite a los usuarios cargar ingresos y gastos, ver un historial de transacciones y consultar el saldo por sucursal.
Este enfoque asegura que la aplicación sea escalable y fácil de mantener, tanto para el backend como para el frontend.
