# 🚀 Guía de Deployment en Vercel

Tu proyecto **"Del Campo al Plato"** ha sido configurado exitosamente para deployment en Vercel.

## Estado Actual

✅ Repositorio Git inicializado  
✅ Conectado a GitHub: `https://github.com/yekam97/Actividad-3.git`  
✅ Rama main con commit inicial  
✅ Archivos de configuración listos (vercel.json, package.json)  

## Pasos para Hacer Deploy en Vercel

### Paso 1: Ir a Vercel
Visita: **https://vercel.com**

### Paso 2: Conectar GitHub
1. Inicia sesión o crea una cuenta en Vercel
2. En la página principal, haz clic en **"Import Project"**
3. Selecciona **"Import Git Repository"**
4. Busca y selecciona: **yekam97/Actividad-3**

### Paso 3: Configurar el Proyecto
Vercel detectará automáticamente:
- ✅ Framework: Static Site
- ✅ Root Directory: ./
- ✅ Output Directory: ./
- ✅ Build Command: (vacío para sitios estáticos)
- ✅ Install Command: (vacío)

**¡Deja todo como está por defecto!**

### Paso 4: Desplegar
1. Haz clic en **"Deploy"**
2. Espera a que termine (normalmente 1-2 minutos)
3. Verás un mensaje: **"Congratulations! Your site is live"**

## Tu URL en Vivo Será:

```
https://actividad-3.vercel.app
```

(O un dominio personalizado si lo conectas después)

## Después del Deploy

### ✨ Actualizaciones Automáticas
- **Cualquier push** a la rama `main` en GitHub
- **Dispara automáticamente** un nuevo deployment en Vercel
- No necesitas hacer nada más

### 📊 Monitorear el Estado
1. En https://vercel.com/dashboard
2. Haz clic en **"Actividad-3"**
3. Verás el historial de deployments
4. Cada fila muestra: estado, hora, commit

### 🔧 Cambios Futuros
```bash
# Hacer cambios locales
git add .
git commit -m "descripción del cambio"
git push origin main

# ¡Vercel se actualiza automáticamente!
```

## Comandos Rápidos

```bash
# Ver estado del repositorio
git status

# Ver historial de commits
git log --oneline

# Hacer un nuevo commit
git add .
git commit -m "Descripción del cambio"
git push origin main
```

## Troubleshooting

### ❌ "Build Failed" en Vercel
- Verifica que no haya errores en `index.html`
- Asegúrate que todos los archivos estén en la raíz del proyecto
- Revisa los logs en el dashboard de Vercel

### ❌ "404 - Not Found"
- Verifica que `index.html` esté en la raíz
- Revisa que la URL sea correcta: `https://actividad-3.vercel.app`

### ❌ Cambios no aparecen
- Espera a que el deployment termine (verifica el dashboard)
- Limpia caché del navegador: `Ctrl+Shift+Delete`
- Force refresh: `Ctrl+F5`

## Variables de Entorno (Si las necesitas)

Si tu proyecto requiere variables de entorno en el futuro:

1. En Vercel Dashboard → Settings → Environment Variables
2. Agrega tus variables
3. Vuelve a hacer deploy

## Dominio Personalizado (Opcional)

1. En Vercel Dashboard → Settings → Domains
2. Conecta tu dominio personalizado
3. Sigue las instrucciones de DNS

## Estadísticas y Monitoreo

En el dashboard puedes ver:
- 📊 Número de deployments
- ⏱️ Tiempos de build
- 🌍 Ubicaciones de los servidores
- 📈 Analytics del sitio

## ¡Listo! 🎉

Tu aplicación "Del Campo al Plato" está ahora:
- ✅ En GitHub
- ✅ Desplegada en Vercel
- ✅ Accesible en: https://actividad-3.vercel.app
- ✅ Con actualizaciones automáticas

**Comparte el link con tus usuarios y ¡que disfruten la experiencia gamificada!** 🚜🍖

---

### Preguntas Frecuentes

**P: ¿Qué pasa si quiero cambiar el nombre?**  
R: Puedes renombrar el proyecto en Vercel Settings → General, pero el repo de GitHub mantiene su nombre.

**P: ¿Se cobra por usar Vercel?**  
R: Vercel ofrece un plan gratuito generoso. Solo se cobra si excedes los límites.

**P: ¿Cómo veo mi sitio en vivo?**  
R: Abre: https://actividad-3.vercel.app en tu navegador.

---

**Creado para: Yeison Gamba**  
**Proyecto: Del Campo al Plato - Experiencia Gamificada**  
**Última actualización: $(date)**
