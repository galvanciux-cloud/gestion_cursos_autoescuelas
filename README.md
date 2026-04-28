# Autoescuela Hub - Plataforma de Gestión React  www.autoescuela-react.netlify.app
> **Sistema Todo-en-Uno:** Sitio público + Panel administrativo para gestionar autoescuelas de forma autónoma.

## 🚀 Funcionalidades Principales
Desde el **Panel de Control**, puedes crear y personalizar cada curso con total libertad:

![Panel de Control](gestion_cursos.png)

| Configuración | Ejemplo | ¿Qué permite? |
|--------------|---------|----------------|
| **🎓 Tipo de curso** | Recuperación Parcial (6 pts) / Recuperación Total / Sensibilización | Elegir la modalidad formativa |
| **💰 Precio** | 350€ / 450€ / 212,50€ | Poner el importe que quieras |
| **👥 Plazas** | 15 / 20 / 30 alumnos | Limitar el aforo máximo |
| **📅 Días y horarios** | Viernes 15:00-21:15, Sábado 08:00-14:15 | Definir fechas exactas 

### 1. Gestión Dinámica de Cursos

<img width="993" height="805" alt="gestion_cursos" src="https://github.com/user-attachments/assets/85ee93b2-140b-4018-8709-97d0bdf94e15" />

<img width="717" height="797" alt="auto" src="https://github.com/user-attachments/assets/9733b8c0-c364-40de-90a6-6b0342b0ba26" />


- **CRUD completo** desde el panel administrativo
- Crear/editar/eliminar ediciones de cursos (Recuperación Parcial/Total)
- Configurar: fechas, horarios, plazas, precios
- **Publicación inmediata** en la web pública (`auto.png`)

### 2. Generación Automática de Certificados

- Botón "Generar Diploma" en lista de alumnos
- Inserción dinámica de datos (nombre, DNI, curso, fechas)
- Exportación a PDF con librerías React (`@react-pdf/renderer`)
- Almacenamiento automático en historial del alumno

<img width="733" height="672" alt="cert" src="https://github.com/user-attachments/assets/89093122-9153-45f9-ad8c-0d3f94670037<img width="713" height="635" alt="mail" src="https://github.com/user-attachments/assets/8bf0de71-1750-483d-b21e-d1c0b84f5f14" />





### 3. Personalización de Marca

<img width="1036" height="813" alt="marc" src="https://github.com/user-attachments/assets/7cde6b82-4838-443b-a4cc-8d1b531b4c35" />


- Cambiar **nombre de la autoescuela** desde "Configuración"
- **Subir/actualizar logo** (input file React)
- Cambios **globales instantáneos** (panel + web pública + PDFs + correos)

### 4. Sistema de Correos Automatizado

- Configuración SMTP (Gmail, Outlook, etc.)
- Editor de **plantillas de email**
- Envío automático de certificados adjuntos al completar curso

<img width="713" height="635" alt="mail" src="https://github.com/user-attachments/assets/2761f984-615b-4b8d-a23a-46840aeb61a6" />


  

### 5. Pasarela de Pagos Stripe

<img width="571" height="661" alt="pago_doc" src="https://github.com/user-attachments/assets/713cb313-4be5-4b41-a121-3857aa8b157c" />


- Integración segura con **Stripe React Components**
- Creación de Payment Intents
- Confirmación de pago **antes de reservar plaza**
- Estado de pago visible en panel (`PAGADO/PENDIENTE`)

### 6. Gestión Documental Automática y Dashboard

<img width="930" height="811" alt="listado_docu" src="https://github.com/user-attachments/assets/4feca0bc-f50e-4827-8ae0-719dfebcd283" />


- Subida de **DNI frontal/reverso** durante inscripción
- Almacenamiento seguro en **Firebase Storage**
- Visualización en modal desde panel administrativo
- Extracción automática de número DNI

## 🗄️ Base de Datos: Firebase Firestore
