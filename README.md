# 🧪 Pruebas No Funcionales - Beneficios

En este repositorio vamos a buscar explicar de forma clara y concisa qué son las **pruebas no funcionales** en el desarrollo de software. Está especialmente pensado para que personas sin mucha idea del tema puedan comprender cómo se evalúa la calidad de una aplicación más allá de su funcionalidad.

---

## 📌 ¿Qué son las pruebas no funcionales?

Las pruebas no funcionales son un tipo de prueba de software que **evalúan el rendimiento, la usabilidad, la seguridad y otros aspectos técnicos** que no siempre están directamente relacionados con las funciones específicas de la aplicación.

Mientras que las **pruebas funcionales** verifican que es lo que *va a hacer un sistema* (por ejemplo, si un botón guarda correctamente los datos de un form), las **pruebas no funcionales** analizan *cómo lo hace* (por ejemplo, que tan rápido responde el sistema, lo seguro que es, o si puede usarse desde un celular).

---

## ✅ Beneficios clave de las pruebas no funcionales

A continuación vamos a detallar los tipos más comunes de pruebas no funcionales, junto con una explicación clara y sus beneficios más importantes.

---

### 🔐 Seguridad

Las pruebas de seguridad evalúan y determinan si una aplicación puede ser **resistente a ataques maliciosos** y si protege de manera correcta y adecuada los datos sensibles de los usuarios.

**¿Por qué es importante?**
- Evita que atacantes roben información personal, como contraseñas o tarjetas de crédito.
- Detecta vulnerabilidades como inyecciones SQL o scripts maliciosos.
- Permite definir qué usuarios pueden acceder a X partes del sistema.

**Beneficios:**
- Mayor confianza del usuario.
- Cumplimiento de normativas legales.
- Protección frente a daños ya sean económicos o reputacionales.

📷 *Ejemplo Visual*:
![Tipos de ataques maliciosos](https://www.fortinet.com/content/dam/fortinet/images/cyberglossary/types-of-cyberattacks.png)
> Ejemplos de los tipos de ataques maliciosos que se pueden encontrar
---

### 📦 Portabilidad

La portabilidad verifica si una aplicación **funciona correctamente en diferentes entornos/dispositivos**. Esto llega a incluir distintos sistemas operativos, navegadores web y tamaños de pantalla.

**¿Por qué es importante?**
- No todos los usuarios van a tener el mismo dispositivo o sistema.
- La app debe funcionar igual en una notebook, un celular o una tablet.
- Facilita actualizaciones futuras o migraciones a otros entornos (por ejemplo, un cambio de servidor físico a la nube).

**Beneficios:**
- Un mayor alcance de usuarios.
- Ahorro de tiempo en soporte técnico.
- Menor riesgo de errores al hacer cambios de plataforma.

📷 *Ejemplo visual*:
![Compatibilidad multiplataforma](https://cdn-www.stelorder.com/wp-content/uploads/2024/02/app-para-organizar-tareas-any.do_.png)
> Visualización de la misma app en múltiples plataformas

---

### 📈 Escalabilidad

La escalabilidad analiza si el sistema puede **manejar un aumento en la carga de trabajo** sin destruirse en el proceso. Por ejemplo, ¿qué pasa si en lugar de 10 usuarios tenemos 10.000?

**¿Por qué es importante?**
- Una aplicación puede empezar con pocos usuarios y crecer con el tiempo.
- Eventos especiales pueden generar picos de tráfico (ej, un Black Friday).
- El mal rendimiento debido al alto puede afectar ventas, reputación y la experiencia del usuario en sí.

**Beneficios:**
- Permite crecer sin rehacer el sistema.
- Mejora la preparación y organización frente a imprevistos.
- Optimiza el uso de recursos (CPU, memoria, red, etc).

📷 *Ejemplo visual*:
![Ejemplo escalabilidad](https://www.loadview-testing.com/wp-content/uploads/load-testing-loadview.png)
> Simulación de usuarios simultáneos con JMeter

---

### 🌐 Accesibilidad

La accesibilidad hace referencia a qué tan fácil es para todas las personas —incluyendo aquellas con alguna discapacidad— **utilizar el sistema**. Esto incluye la navegación por teclado, los lectores de pantalla, fuentes y colores adecuados, entre otros.

**¿Por qué es importante?**
- Existen millones de personas con discapacidades visuales, auditivas o motoras.
- La accesibilidad en sí es un derecho y también una ventaja competitiva.
- Las leyes en muchos países exigen que los sitios públicos sean accesibles.

**Beneficios:**
- Aplicación inclusiva y ética.
- Mejora la experiencia para todos los usuarios (no solo los que tienen discapacidades).

📷 *Ejemplo visual*:
![Accesibilidad web](https://lh3.googleusercontent.com/tSHcpuokmtjQFdWaKFYGCrQ-WNCi746CrfBRKV0eiqJxKSp9zdkBz55g_QZIrr2w_cPnqUtAcJRuql1npR0mzEYQEIE=s1280-w1280-h800)
> Chequeo automático de accesibilidad con axe DevTools, una extensión de Google Chrome

---

## 🎯 ¿Por qué son importantes las pruebas no funcionales?

Porque al final de dia, te aseguran que la aplicación no solo **funcione**, sino que funcione **bien**, incluso cuando las cosas se ponen al límite de verdad.

Muchas veces, una app puede parecer perfecta durante las pruebas básicas, pero cuando la empieza a usar mucha gente o cuando se hacen conexiones desde distintos dispositivos... ahí es donde empiezan los problemas.

Sin estas pruebas, una aplicación podría:
- Funcionar bien en *teoría*, pero llegar en realidad a ser lenta o poco confiable.
- Caerse cuando muchas personas la usan al mismo tiempo.
- No ser segura y quedar expuesta a ataques.
- No poder ser utilizada por personas con diversas discapacidades.

Realizar pruebas no funcionales **antes de lanzar** o **durante el desarrollo** es una inversión que ahorra dinero y problemas de cabeza a largo plazo.

---

## 🧪 Comparativa general

| Tipo de prueba       | ¿Qué evalúa?                          | Ejemplo práctico                            |
|----------------------|----------------------------------------|---------------------------------------------|
| Funcional            | ¿El sistema hace lo se supone?         | El botón "registrarse" guarda los datos     |
| No funcional - Seguridad | ¿Protege los datos y acceso?        | El sistema bloquea intentos de hacking      |
| No funcional - Portabilidad | ¿Funciona en distintos entornos? | El sitio se ve bien en Chrome, Firefox y móvil |
| No funcional - Escalabilidad | ¿Soporta el crecimiento?         | 5.000 personas usan la app sin caídas       |
| No funcional - Accesibilidad | ¿Todos la pueden usar?             | Usuarios ciegos pueden navegar sin problema |

---

## 🛠️ Herramientas recomendadas

>En base a investigaciones, encontramos algunas herramientas que ayudan en el proceso de las *pruebas no funcionales*

| Tipo de prueba | Herramientas comunes                         |
|----------------|-----------------------------------------------|
| Seguridad      | OWASP ZAP                       |
| Portabilidad   | BrowserStack                   |
| Escalabilidad  | Apache JMeter                    |
| Accesibilidad  | axe-core, Google Lighthouse, WAVE       |

---

> 🧠 *Una app completa no solo hace su tarea, sino que hace la misma bajo presión, sin errores (en un mundo perfecto), y pensando en **todos** los usuarios. Las pruebas no funcionales nos ayudan a garantizar eso 🫶🫂*

