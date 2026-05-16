# Política de Privacidad — InspectraEdificios

**Última actualización: 15 de mayo de 2026**

Esta política describe cómo InspectraEdificios (en adelante "la App"), desarrollada por **Allpa Servicios Integrales Limitada** (en adelante "Allpa", "nosotros"), recolecta, usa y protege la información de quienes la utilizan.

## 1. Responsable del tratamiento

- **Razón social**: Allpa Servicios Integrales Limitada
- **Contacto**: maldonado@allpa.cl
- **Jurisdicción**: República de Chile

## 2. Información que recolectamos

### 2.1. Datos de cuenta
Al registrarte con email/contraseña o con Google Sign-In recolectamos:
- Dirección de correo electrónico
- Nombre (si lo provees al registrarte o si proviene de tu cuenta de Google)
- Identificador único asignado por Firebase Authentication

No almacenamos contraseñas en texto plano: la autenticación es gestionada por Firebase Authentication (Google LLC).

### 2.2. Datos del levantamiento técnico
Cuando creas o editas un levantamiento, almacenamos:
- Datos generales del edificio (nombre del condominio, dirección, cantidad de torres, número de ascensores, presencia de piscinas, salas de bombas, generador, gas centralizado, aire acondicionado).
- Respuestas de las fichas técnicas (estados de mantención, observaciones, fechas de inspección).
- Fotografías que tú decidas adjuntar a las fichas.

Estos datos se asocian a tu cuenta y son visibles únicamente por ti.

### 2.3. Datos almacenados localmente
La App guarda una copia local de tus levantamientos (AsyncStorage) en tu dispositivo, para permitir el trabajo sin conexión. Esta copia no abandona tu dispositivo salvo cuando se sincroniza con nuestro backend.

### 2.4. Información que NO recolectamos
- No recolectamos ubicación GPS.
- No recolectamos contactos, agenda ni mensajes.
- No usamos identificadores publicitarios.
- No accedemos al micrófono.

## 3. Cómo usamos la información

Usamos los datos exclusivamente para:
- Permitir que accedas a tu cuenta y a tus levantamientos desde cualquier dispositivo.
- Generar los informes técnicos en formato PDF que tú solicites desde la App.
- Mantener una copia de respaldo en la nube de tu trabajo.
- Diagnosticar errores técnicos cuando reportas problemas.

**No vendemos, alquilamos ni compartimos tu información con terceros con fines comerciales.**

## 4. Proveedores de servicios

Para operar la App utilizamos servicios de terceros que pueden procesar datos:

- **Firebase (Google LLC)** — Autenticación, base de datos (Firestore) y almacenamiento de fotos (Cloud Storage). Sujeto a la política de privacidad de Google: https://policies.google.com/privacy
- **Expo (Expo, Inc.)** — Distribución y actualización de la App. Sujeto a https://expo.dev/privacy

Estos servicios aplican sus propias medidas de seguridad y políticas de retención. Allpa no comparte datos con otros terceros.

## 5. Almacenamiento y retención

Los datos se almacenan en servidores de Google Cloud Platform (regiones disponibles para Firebase). Conservamos tus datos mientras tu cuenta exista. Si solicitas la eliminación de tu cuenta, eliminamos los datos asociados dentro de un plazo razonable salvo obligación legal de retención.

## 6. Tus derechos

Bajo la Ley N° 19.628 sobre Protección de la Vida Privada (Chile) y el Reglamento General de Protección de Datos (cuando aplique), puedes:
- Solicitar acceso a tus datos.
- Solicitar la rectificación de datos incorrectos.
- Solicitar la eliminación de tus datos y de tu cuenta.
- Retirar el consentimiento en cualquier momento.

Para ejercer estos derechos, contáctanos a **maldonado@allpa.cl**.

## 7. Cómo solicitar la eliminación de tu cuenta y datos

Si quieres eliminar tu cuenta de InspectraEdificios y todos los datos asociados, puedes hacerlo de la siguiente manera:

**Procedimiento**:
1. Envía un correo a **maldonado@allpa.cl** con el asunto *"Solicitud de eliminación de cuenta - Inspectra"*.
2. Incluye en el cuerpo del correo el email con el que te registraste en la App.
3. Procesamos tu solicitud dentro de un plazo máximo de **30 días** y te confirmamos la eliminación por respuesta a ese mismo correo.

**Datos que se eliminan**:
- Tu perfil de usuario en Firebase Authentication (email, nombre, identificador único).
- Tus datos en Firestore: levantamientos creados, fichas técnicas, comentarios e incidencias generadas, tokens de notificaciones push.
- Las fotografías que subiste a Firebase Storage (de fichas e incidencias).

**Datos que pueden retenerse**:
Por motivos legales o de cumplimiento normativo aplicable a la administración de edificios podemos retener registros anonimizados (sin tu nombre, email ni identificador) durante el período que exija la ley vigente, sin posibilidad de re-asociarlos a tu identidad.

**Sobre eliminación parcial**: el historial de eventos del módulo Incidencias es inmutable por diseño (cada interacción genera un evento que no se modifica, similar a un libro de bitácora). Por eso, comentarios o eventos individuales no pueden eliminarse por separado; la única vía es la eliminación total de cuenta descrita arriba.

## 8. Seguridad

Las comunicaciones entre la App y nuestros servidores usan cifrado HTTPS/TLS. El acceso a la base de datos está limitado por reglas de Firebase Security Rules: cada usuario solo puede leer y escribir sus propios datos.

Aunque tomamos medidas razonables para proteger tu información, ningún sistema es 100% seguro. En caso de un incidente de seguridad que pueda afectarte, te notificaremos por correo electrónico.

## 9. Niños

La App no está dirigida a menores de 14 años y no recolectamos conscientemente información de menores. Si crees que un menor nos ha proporcionado información personal, contáctanos para eliminarla.

## 10. Cambios en esta política

Podemos actualizar esta política. La versión vigente y su fecha de última actualización siempre están disponibles en este mismo enlace. Cambios sustanciales se comunicarán por correo electrónico a los usuarios registrados.

## 11. Contacto

¿Preguntas sobre esta política o sobre el manejo de tus datos?

**maldonado@allpa.cl**
Allpa Servicios Integrales Limitada — Chile
