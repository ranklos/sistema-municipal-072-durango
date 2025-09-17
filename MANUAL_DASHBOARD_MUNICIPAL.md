# 📋 Manual de Usuario - Dashboard Municipal 072
## Municipio de Durango - Sistema de Reportes Ciudadanos

---

## 🚀 **Nuevas Funcionalidades Implementadas**

### ✅ **EDICIÓN INLINE DE ASSIGNEE Y NOTES**
### ✅ **DESCARGA DE FOTOS DE REPORTES**
### ✅ **SINCRONIZACIÓN AUTOMÁTICA CON GOOGLE SHEETS**

---

## 🔐 **Acceso al Sistema**

### **Credenciales Disponibles:**
- **Administrador:** `admin@durango.gob.mx` / `Durango2024!`
- **Operador:** `operador@durango.gob.mx` / `Operador072`  
- **Supervisor:** `supervisor@durango.gob.mx` / `Super072`

### **URL del Dashboard:**
- **Local:** Abrir `index.html` en navegador
- **Producción:** [URL de Netlify cuando se despliegue]

---

## 📝 **Cómo Editar Assignee (Responsable)**

### **Paso a Paso:**
1. **Localizar el reporte** en la tabla principal
2. **Hacer clic** en la celda de "Assignee" (columna 12)
3. **Seleccionar** del dropdown el responsable:
   - Sin asignar
   - Admin Municipal
   - Obras Públicas
   - Servicios Urbanos
   - Mantenimiento
   - Supervisor 072
   - Operador Turno A
   - Operador Turno B

4. **Hacer clic en ✓** para guardar
5. **Hacer clic en ✗** para cancelar

### **Confirmación Visual:**
- La celda se **marcará en verde** por 2 segundos
- Se mostrará **"Guardando..."** durante el proceso
- **Google Sheets se actualiza automáticamente**

---

## 📝 **Cómo Editar Notes (Notas)**

### **Paso a Paso:**
1. **Localizar el reporte** en la tabla principal
2. **Hacer clic** en la celda de "Notes" (columna 13)
3. **Escribir o editar** las notas en el área de texto
4. **Hacer clic en ✓** para guardar
5. **Hacer clic en ✗** para cancelar

### **Ejemplos de Notas Útiles:**
- "Contactado al ciudadano - programado para mañana"
- "Requiere materiales especiales"
- "En proceso - cuadrilla enviada"
- "Completado - verificar con supervisor"
- "Pendiente de presupuesto"

---

## 📸 **Cómo Descargar Fotos**

### **Paso a Paso:**
1. **Localizar el reporte** con foto disponible
2. **Hacer clic** en "📸 Descargar" en la columna Foto
3. **Confirmar** la descarga en el popup
4. **El archivo se descarga** como `Foto_DGO-072-XXXXXX.jpg`

### **Notas Importantes:**
- ✅ Las fotos se almacenan en **Google Drive**
- ✅ Se descargan en **formato JPG**
- ✅ Nombre del archivo incluye el **folio del reporte**

---

## 🔄 **Sincronización con Google Sheets**

### **¿Qué se Sincroniza Automáticamente?**
- ✅ **Assignee** → Columna L del Google Sheet
- ✅ **Notes** → Columna M del Google Sheet  
- ✅ **Timestamp** de actualización
- ✅ **Usuario** que realizó el cambio

### **Tiempo de Sincronización:**
- **Inmediato** (menos de 5 segundos)
- **Respaldo automático** cada hora
- **Verificación** de integridad diaria

---

## 🎯 **Mejores Prácticas**

### **Para Assignee:**
- ✅ **Asignar inmediatamente** los reportes nuevos
- ✅ **Cambiar a "Supervisor 072"** para escalación
- ✅ **Usar "Sin asignar"** solo temporalmente

### **Para Notes:**
- ✅ **Ser específico** en las actualizaciones
- ✅ **Incluir fechas** de seguimiento
- ✅ **Mencionar recursos** necesarios
- ✅ **Documentar comunicaciones** con ciudadanos

### **Para Fotos:**
- ✅ **Descargar antes** de salir a campo
- ✅ **Revisar calidad** de la imagen
- ✅ **Usar para verificación** post-reparación

---

## 📊 **Estructura Completa de la Tabla**

| # | Campo | Descripción | ¿Editable? |
|---|-------|-------------|------------|
| 1 | **Folio** | DGO-072-XXXXXX | ❌ No |
| 2 | **Fecha** | Timestamp del reporte | ❌ No |
| 3 | **Ciudadano** | Nombre del reportante | ❌ No |
| 4 | **Teléfono** | Contacto ciudadano | ❌ No |
| 5 | **Tipo** | Categoría del reporte | ❌ No |
| 6 | **Código 072** | Clasificación municipal | ❌ No |
| 7 | **Dirección** | Ubicación del problema | ❌ No |
| 8 | **Descripción** | Detalle del reporte | ❌ No |
| 9 | **Estado** | Pendiente/En proceso/Completado | ❌ No |
| 10 | **Prioridad** | Alta/Media/Baja | ❌ No |
| 11 | **Foto** | Descarga disponible | 📸 Descarga |
| 12 | **Assignee** | Responsable asignado | ✅ Editable |
| 13 | **Notes** | Notas de seguimiento | ✅ Editable |

---

## 🚨 **Solución de Problemas**

### **Si no puedo editar:**
- ✅ Verificar que esté **logueado correctamente**
- ✅ **Refrescar la página** (Ctrl + F5)
- ✅ **Intentar en otro navegador**

### **Si no se guarda:**
- ✅ Verificar **conexión a internet**
- ✅ **No dejar campos vacíos**
- ✅ **Esperar mensaje de confirmación**

### **Si no descarga foto:**
- ✅ **Permitir descargas** en el navegador
- ✅ Verificar que la **foto existe** en el reporte
- ✅ **Intentar clic derecho** → Guardar como

---

## 📞 **Contacto de Soporte**

### **Soporte Técnico:**
- **Horario:** 24/7 durante primer mes
- **Email:** soporte@municipio-durango.gob.mx
- **Teléfono:** 618-XXX-XXXX ext. 072

### **Actualizaciones del Sistema:**
- **Revisiones:** Semanales
- **Mejoras:** Según feedback del personal
- **Capacitación:** Disponible bajo demanda

---

## 🏆 **Beneficios del Sistema**

### **Para el Personal:**
- ✅ **Gestión visual** de todos los reportes
- ✅ **Asignación rápida** de responsabilidades
- ✅ **Seguimiento detallado** con notas
- ✅ **Acceso a fotos** para verificación

### **Para el Municipio:**
- ✅ **Transparencia** en el proceso
- ✅ **Reducción de tiempos** de respuesta
- ✅ **Mejor comunicación** ciudadana
- ✅ **Reportes automáticos** de gestión

---

**🏛️ Sistema Municipal 072 - Mejorando la atención ciudadana de Durango**

**Versión:** 2.3.0 - Dashboard con Edición Inline  
**Fecha:** Septiembre 2024  
**Personal capacitado:** [Llenar después del entrenamiento]