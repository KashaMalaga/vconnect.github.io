Política de Privacidad de VConnect
Fecha de entrada en vigor: 9 de agosto de 2025
Esta Política de Privacidad describe cómo VConnect ("la Aplicación", "nosotros", "nuestro") maneja su información en relación con el uso de nuestra aplicación para Wear OS. Su privacidad es de suma importancia para nosotros.
Nuestra filosofía es la mínima recopilación de datos. La Aplicación está diseñada para actuar como un cliente seguro entre su dispositivo y los servidores oficiales del fabricante de su vehículo, sin almacenar ni transmitir sus datos personales a nuestros servidores.
1. Información que la Aplicación Maneja
Para funcionar, la Aplicación necesita manejar los siguientes tipos de información:
Credenciales de Autenticación del Vehículo: Cuando usted inicia sesión a través de la Aplicación, se generan tokens de acceso (Access Token y Refresh Token) proporcionados por el fabricante del vehículo. Estos tokens son necesarios para autenticar y autorizar las solicitudes que la Aplicación realiza en su nombre (por ejemplo, para bloquear las puertas o consultar el nivel de batería).
Identificador del Vehículo (VIN): La Aplicación almacena el Número de Identificación de su Vehículo (VIN) seleccionado para dirigir los comandos al coche correcto.
Datos del Vehículo: La Aplicación solicita y muestra en tiempo real datos proporcionados por la API del fabricante de su vehículo. Esto incluye, entre otros:
Estado de las puertas y ventanillas.
Nivel de combustible y/o carga de la batería y autonomía.
Ubicación del vehículo (latitud y longitud).
Estado del motor y de la climatización.
Datos de diagnóstico (por ejemplo, presión de los neumáticos, necesidad de servicio).
Datos de Compra (Premium): Si adquiere la versión Premium, la Aplicación maneja un token de compra proporcionado por Google Play. Este token se utiliza únicamente para verificar la validez de su compra con nuestro servidor seguro.
Datos de Diagnóstico y Cierre Inesperado: La Aplicación utiliza servicios como Google Firebase Crashlytics para recopilar datos anónimos sobre cierres inesperados (crashes). Esta información no contiene datos personales identificables y se utiliza exclusivamente para mejorar la estabilidad y la calidad de la Aplicación.
2. Cómo se Almacenan sus Datos
La seguridad de sus datos es nuestra máxima prioridad.
Almacenamiento Local y Cifrado: Sus credenciales de autenticación (tokens) y el VIN de su vehículo se almacenan única y exclusivamente en el almacenamiento seguro y cifrado de su dispositivo Wear OS. Utilizamos la biblioteca EncryptedSharedPreferences de Android Jetpack, el estándar de la industria, para proteger esta información. Estas credenciales nunca abandonan su dispositivo para ser enviadas a nuestros servidores.
Sin Almacenamiento en la Nube: No tenemos servidores que almacenen sus credenciales, datos de su vehículo, ubicación o cualquier otra información personal. VConnect actúa como un intermediario seguro, no como un servicio de almacenamiento de datos.
3. Cómo se Utilizan sus Datos
Su información se utiliza estricta y exclusivamente para los siguientes propósitos:
Para Comunicarse con los Servidores del Vehículo: Los tokens de acceso se utilizan para autenticar las solicitudes a la API oficial del fabricante de su vehículo para ejecutar los comandos que usted solicita (bloquear, desbloquear, etc.) y para obtener el estado actual de su coche.
Para Verificar Compras Premium: El token de compra de Google Play se envía a nuestro servidor junto con un token de integridad de Google Play para una única verificación. No almacenamos este token de compra.
Para Mejorar la Aplicación: Los informes de cierre anónimos nos ayudan a identificar y corregir errores de software.
4. Intercambio de Información con Terceros
No vendemos, alquilamos ni compartimos su información personal con terceros. El único intercambio de datos que ocurre es el estrictamente necesario para el funcionamiento de la aplicación:
Con el Fabricante del Vehículo: Todas las solicitudes relacionadas con su coche (estado, comandos, ubicación) se envían directamente a los servidores seguros del fabricante del vehículo, utilizando los tokens de autenticación que usted proporcionó al iniciar sesión. Le recomendamos consultar la política de privacidad del fabricante de su vehículo para entender cómo manejan ellos sus datos.
Con Google Play: El proceso de compra es manejado íntegramente por los servicios de facturación de Google Play.
Con Nuestro Verificador de Licencias: Para activar la funcionalidad Premium, se envía un token de compra de un solo uso a nuestro servidor para su validación. Este proceso está protegido y no incluye información personal.
5. Seguridad
Hemos implementado medidas de seguridad estándar de la industria, como el uso de EncryptedSharedPreferences y la comunicación a través de HTTPS, para proteger la información manejada por la Aplicación en su dispositivo.
6. Cambios en esta Política de Privacidad
Podemos actualizar nuestra Política de Privacidad de vez en cuando. Le notificaremos de cualquier cambio publicando la nueva Política de Privacidad en esta página. Se le recomienda revisar esta Política de Privacidad periódicamente para cualquier cambio.
7. Contacto
Si tiene alguna pregunta sobre esta Política de Privacidad, puede contactarnos a través de nuestra ficha en la Google Play Store.
Próximos Pasos
Crea la Página: Copia y pega este texto en una página web pública.
Obtén el Enlace: Consigue la URL pública de esa página (por ejemplo, https://your-github-username.github.io/vconnect-privacy.html).
Actualiza la Play Console: Ve a la ficha de tu app en la Google Play Console, busca la sección "Política de Privacidad" (generalmente bajo "Contenido de la app") y pega el nuevo enlace.
Guarda y Reenvía: Guarda los cambios. Si tu app fue rechazada por este motivo, es posible que necesites reenviarla a revisión.
Con esta política, estás siendo transparente, honesto y cumples con los requisitos de Google. Debería ser aprobada sin problemas.
