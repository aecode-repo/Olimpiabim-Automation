# Guia Completa para Participantes

## BIM AUTOMATION + IA - OlimpiaBIM 2026

Esta guia te lleva paso a paso por el proceso de registro en GitHub y entrega de soluciones. **Todo se hace desde el navegador web, no necesitas instalar nada.**

---

## PASO 01: Crear tu Cuenta en GitHub

1. Abre tu navegador y ve a **[github.com/signup](https://github.com/signup)**
2. Ingresa tu **correo electronico** (debe ser el **mismo** con el que te inscribiste al concurso)
3. Crea una **contrasena segura**
4. Elige un **nombre de usuario** (recomendado: tu nombre, ej: `juan-perez-bim`)
5. Completa la verificacion y haz clic en **"Create account"**
6. Ve a tu correo y haz clic en el **enlace de verificacion** que GitHub te envio

> **Si ya tienes cuenta de GitHub con otro correo**, puedes agregar tu correo de inscripcion como correo secundario: Ve a Settings > Emails > Add email address

---

## PASO 02: Solicitar Acceso al Repositorio

### Enviar solicitud por correo

Envia un correo a **aes.bim@unsaac.edu.pe** con la siguiente informacion:

- **Asunto**: `Acceso GitHub - BIM AUTOMATION - [Tu Nombre] - Equipo ##`
- **Contenido del correo**:
  - Nombre completo de los integrantes del equipo
  - Nombre de usuario de GitHub de cada integrante
  - Numero de equipo asignado

**Ejemplo:**
```
Para: aes.bim@unsaac.edu.pe
Asunto: Acceso GitHub - BIM AUTOMATION - Juan Perez - Equipo 03

Estimados organizadores,
Solicito acceso al repositorio de GitHub para el concurso BIM AUTOMATION + IA.

Equipo 03:
- Juan Perez Garcia (usuario GitHub: juan-perez-bim)
- Maria Lopez Ramos (usuario GitHub: maria-lopez-r)

Saludos.
```

### Aceptar la invitacion

1. Recibiras un **correo de GitHub** con la invitacion (revisa tambien tu carpeta de spam)
2. Haz clic en **"View invitation"** o **"Accept invitation"**
3. Tambien puedes aceptarla desde [github.com/notifications](https://github.com/notifications)

---

## PASO 03: Conocer la Estructura de Carpetas

El repositorio tiene la siguiente estructura donde cada equipo sube sus archivos:

```
entregas/
  fase-1/
    ronda-1/
      ejercicio-1/     <-- Reto 1: todos los equipos suben aqui
      ejercicio-2/     <-- Reto 2: todos los equipos suben aqui
      ejercicio-3/     <-- Reto 3: todos los equipos suben aqui
    ronda-2/           <-- Caso grande: todos los equipos suben aqui
  fase-2/              <-- Entrega presencial
```

### Nomenclatura obligatoria de archivos

Tus archivos deben seguir este formato (reemplaza `TuEquipo##` por tu nombre de equipo y numero):

**Para Fase 1 (cada ejercicio):**
- `BIMAUTO_TuEquipo01_Codigo.zip` - Carpeta comprimida con tus scripts (.py, .cs, .dyn)
- `BIMAUTO_TuEquipo01_README.pdf` - Instrucciones de ejecucion
- `BIMAUTO_TuEquipo01_Outputs.zip` - Resultados y evidencias
- `BIMAUTO_TuEquipo01_Dependencias.txt` - Solo si usas librerias externas

**Para Fase 2:**
- `BIMAUTO_TuEquipo01_VersionFinal.zip` - Version ajustada con el cambio
- `BIMAUTO_TuEquipo01_Logs_Reportes.pdf` - Logs de ejecucion
- `BIMAUTO_TuEquipo01_PresentacionFinal.pdf` - Material de sustentacion

---

## PASO 04: Subir tus Entregables

**Todo se hace desde el navegador, no necesitas instalar nada.**

### 4.1 Ir al repositorio
Abre en tu navegador: **github.com/aecode-repo/Olimpiabim-Automation**

### 4.2 Navegar a la carpeta del ejercicio
Haz clic en las carpetas para llegar al ejercicio correspondiente:
- Clic en **`entregas`**
- Clic en **`fase-1`**
- Clic en **`ronda-1`**
- Clic en **`ejercicio-1`** (o el ejercicio que corresponda)

### 4.3 Subir archivos
1. Haz clic en el boton **"Add file"** (arriba a la derecha)
2. Selecciona **"Upload files"**
3. **Arrastra tus archivos** al area de carga, o haz clic en **"choose your files"** para seleccionarlos
4. En el campo **"Commit changes"** (abajo), escribe un mensaje descriptivo:
   - Ejemplo: `Entrega Ejercicio 1 - Equipo 03`
5. Asegurate de que este seleccionado **"Commit directly to the main branch"**
6. Haz clic en el boton verde **"Commit changes"**

### 4.4 Verificar tu entrega
1. Despues de subir, veras tus archivos en la carpeta del ejercicio
2. Haz clic en cada archivo para verificar que se subio correctamente
3. Si necesitas subir mas archivos o reemplazar alguno, repite el proceso

---

## PASO 05: Actualizar o Corregir una Entrega

### Para agregar mas archivos:
Repite el Paso 04 en la misma carpeta del ejercicio.

### Para reemplazar un archivo:
1. Navega a la carpeta del ejercicio
2. Haz clic en el archivo que quieres reemplazar
3. Haz clic en el icono de **papelera** (Delete) para eliminarlo
4. Confirma la eliminacion con **"Commit changes"**
5. Sube el archivo corregido siguiendo el Paso 04

---

## Resolucion de Problemas

### "No puedo ver el repositorio"
- Verifica que aceptaste la invitacion de colaborador
- Revisa tu correo (incluida la carpeta de spam) buscando la invitacion de GitHub
- Contacta a los organizadores para que reenvien la invitacion

### "No me aparece el boton Add file"
- Asegurate de haber aceptado la invitacion como colaborador
- Intenta cerrar sesion y volver a iniciar sesion en GitHub

### "Error al subir archivos"
- Verifica que ningun archivo supere los **100 MB**
- Comprime carpetas en `.zip` antes de subirlas
- No subas archivos `.rvt` (modelos Revit)

### "Subi un archivo equivocado"
- Navega al archivo, haz clic en el, y usa el icono de papelera para eliminarlo
- Luego sube el archivo correcto

---

## Recordatorios Importantes

- Usa el **correo de inscripcion** para tu cuenta de GitHub
- **No modifiques archivos de otros equipos** (descalificacion inmediata)
- **Respeta la nomenclatura** de archivos
- **Incluye la bitacora de IA** si usaste herramientas de IA generativa
- **Comprime tus carpetas** en .zip antes de subir (GitHub no permite subir carpetas sueltas desde la web)
- **Fecha limite Fase 1**: Sabado 28 de marzo, 8:00 pm

---

## Contacto y Soporte

Si tienes problemas con GitHub o la entrega:
- **Correo**: aes.bim@unsaac.edu.pe
- **Asunto**: "Soporte GitHub - BIM AUTOMATION - [Tu Nombre]"

---

*Guia preparada por el comite organizador de OlimpiaBIM 2026 - CEFIC / AECODE / UNSAAC*
