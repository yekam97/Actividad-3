# 🐄 Del Campo al Plato - La Ruta Invisible de la Carne

## Descripción

Una aplicación web interactiva educativa y gamificada que simula el recorrido completo de un producto cárnico desde la granja hasta el consumidor final. Los jugadores deben tomar decisiones inteligentes bajo presión, con retroalimentación inmediata en cada fase.

## ✨ Características Principales

### 🎮 Mecánicas de Juego
- **Sistema de puntuación dinámico** que comienza en 100% Trazabilidad
- **Temporizadores en cada fase** que aumentan la presión
- **Drag & Drop intuitivo** para interacciones
- **Feedback detallado** al completar cada fase
- **Penalizaciones acumulativas** por errores

### 📊 Fases de la Experiencia

#### 🚜 Fase 1: La Granja (60 segundos)
- Registra vacas con información completa
- Tiempo límite: 60 segundos
- Penalización por vacas sin registrar
- Feedback detallado al completar

#### 🚚 Fase 2: Transporte (2 sub-fases)
- **Observación**: 7 segundos para memorizar rutas y camiones
- **Decisión**: Asigna camiones a rutas considerando:
  - Capacidad
  - Refrigeración
  - Clima
  - Sensores

#### 🏭 Fase 3: Procesamiento
- Clasifica productos en lotes
- Banda transportadora animada
- Penalización por productos perdidos

#### 📦 Fase 4: Distribución (2 sub-fases)
- **Observación**: 6 segundos para ver demanda
- **Decisión**: Distribuye productos a ciudades

#### 🛒 Fase 5: Punto de Venta
- Coloca productos en estantería
- Activa QR de trazabilidad
- Verificación final

#### 📊 Fase 6: Resultado Final
- Puntuación porcentual
- Timeline completo del producto
- Análisis de errores
- Opción para compartir y reintentar

## 🎯 Sistema de Penalizaciones

| Error | Penalización |
|-------|-------------|
| Vaca sin registrar | -10% |
| Registro incompleto | -6% |
| Código duplicado | -12% |
| Ruta lluviosa sin refrigeración | -10% |
| Sobrecarga de camión | -6% |
| Producto perdido | -7% |
| Mal lote | -10% |
| Producto mal ubicado | -5% |
| QR sin activar | -8% |
| Cliente sin trazabilidad | -12% |

## 🚀 Cómo Ejecutar

### Opción 1: Servidor Local (Recomendado)
```powershell
cd "c:\Users\Yeison Gamba\Desktop\Prueba"
python -m http.server 8000
```
Luego abre en tu navegador: `http://localhost:8000`

### Opción 2: Abrir Directamente
- Haz doble clic en `index.html` en el explorador de archivos

### Opción 3: Desplegar en Vercel
```bash
git init
git add .
git commit -m "Initial commit"
git push origin main
```
Conecta con Vercel en https://vercel.com

## 📱 Compatibilidad

- ✅ Desktop (Chrome, Firefox, Safari, Edge)
- ✅ Tablets (iPad, Android tablets)
- ✅ Responsive design
- ✅ Sin dependencias externas

## 🎓 Objetivo Educativo

Esta aplicación enseña:
- **Importancia de la trazabilidad** en alimentos
- **Decisiones bajo presión** en logística
- **Consecuencias de errores** operacionales
- **Gestión eficiente** de recursos
- **Importancia de la calidad** en cada etapa

## 🛠️ Tecnología

- HTML5
- CSS3 (con animaciones y gradientes)
- JavaScript vanilla (sin frameworks)
- Drag & Drop API
- LocalStorage para progreso

## 📈 Feedback Dinámico

Cada fase proporciona:
- ✅ Análisis de decisiones
- 📊 Impacto en la puntuación
- 💡 Sugerencias de mejora
- 📍 Resumen de acciones

## 🎨 Diseño Visual

- Flat design moderno
- Gradientes suaves
- Animaciones fluidas
- Transiciones elegantes
- Microinteracciones

## 📝 Cómo Jugar

1. Clickea "Iniciar Experiencia"
2. Registra todas las vacas dentro del tiempo
3. Memoriza información en fases de observación
4. Toma decisiones inteligentes en fases de decisión
5. Obtén feedback detallado de cada fase
6. Completa todas las fases
7. Revisa tu puntuación final

## 🏆 Metas

- **90-100%**: Excelente - Trazabilidad perfecta
- **80-89%**: Buen desempeño - Errores mínimos
- **60-79%**: Desempeño regular - Mejora necesaria
- **Menos 60%**: Desempeño bajo - Revisar estrategia

## 👥 Autor

Creado como herramienta educativa interactiva para enseñar sobre trazabilidad alimentaria y gestión logística.

## 📄 Licencia

Uso educativo libre.

---

**¡Disfruta la experiencia y aprende sobre la ruta invisible de la carne!** 🐄 → 🍖
