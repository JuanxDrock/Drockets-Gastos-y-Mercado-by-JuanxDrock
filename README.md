# Drockets-Gastos-y-Mercado-by-JuanxDrock
App de finanzas personales: Drockets 💰 Nació de una necesidad propia: llevar mis gastos diarios y saber cuánto voy a pagar en caja cuando voy al mercado, sin hacer cuentas a ojo.

Drockets es una aplicación móvil para Android que ayuda a llevar el control de los gastos del día a día y a planear el presupuesto del mercado. Registras lo que gastas, vas anotando lo que echas al carrito mientras compras, ves el total que vas a pagar en caja y te das cuenta de qué productos subieron o bajaron de precio.

Estado del proyecto: uso privado. Este repositorio solo describe la aplicación; el código fuente no está publicado y la app no está disponible para descarga.

¿Para quién es?
Personas y familias que quieren saber en qué se va su dinero cada mes.
Quienes hacen el mercado y quieren saber cuánto van a pagar antes de llegar a la caja.
Quienes notan que "todo está más caro" y quieren ver, con datos propios, cuánto subió cada producto.
Cualquiera que prefiera una herramienta simple, sin hojas de cálculo ni formularios largos.
Funcionalidades
Cuentas
Registro e inicio de sesión con correo electrónico y contraseña.
Recuperación de contraseña por correo.
Cada cuenta guarda sus propios registros, separados de los de otras personas.
Los datos se guardan en la nube, así que se conservan al cambiar de celular o reinstalar la app.
Se puede seguir registrando sin conexión a internet; la información se sincroniza cuando vuelve la conexión.
Gastos diarios
Registro de gastos con monto, categoría, nota opcional y fecha.
Categorías: Transporte, Comida, Servicios, Salud, Ocio, Ropa, Imprevisto y Otros.
Lista agrupada por día, con el total de cada jornada y el total del mes.
Navegación entre meses.
Edición y eliminación de cualquier gasto.
Lista de mercado
Inicio de una compra al llegar al supermercado o a la plaza.
Cada producto se agrega con su precio unitario y cantidad (admite decimales, por ejemplo 0,5 kg).
Total en caja actualizado en tiempo real, para saber cuánto se va a pagar antes de llegar a pagar.
Sugerencias de productos ya comprados, con el último precio registrado.
Edición y eliminación de productos mientras se compra.
Al finalizar, la compra queda guardada en un historial con su total.
Seguimiento de precios
Indicador junto a cada producto que muestra si el precio subió (▲) o bajó (▼) frente a la compra anterior, con el porcentaje de variación.
Sección Precios con todos los productos comprados:
búsqueda por nombre,
filtros "Subieron" y "Bajaron",
historial de precios de cada producto.
Resumen mensual
Total del mes, separando gastos diarios y mercado.
Desglose por categoría con barras comparativas.
Presupuesto estimado de mercado, calculado con el promedio de los meses anteriores, y una versión ajustada según la variación reciente de los precios.
Diseño
Interfaz moderna basada en Material Design 3.
Compatible con modo claro y modo oscuro.
Logo e ícono propios.
Tecnologías y herramientas
Área	Herramienta
Lenguaje	Kotlin
Interfaz de usuario	Jetpack Compose
Diseño	Material Design 3
Navegación	Navigation Compose
Arquitectura	ViewModel con Kotlin Coroutines y Flow
Autenticación	Firebase Authentication (correo y contraseña)
Base de datos	Cloud Firestore, con soporte sin conexión
Entorno de desarrollo	Android Studio
Compilación	Gradle (Kotlin DSL)
Plataforma	Android 8.0 (API 26) o superior
Autor

Desarrollado por JuanxDrock Instagram, TikTok, YouTube, Facebook y X: @juanxdrocktech

© 2026 JuanxDrock. Todos los derechos reservados. Este proyecto no es de código abierto; el código, el diseño y el nombre no pueden copiarse, distribuirse ni usarse sin autorización del autor.
