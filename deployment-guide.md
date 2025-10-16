# 🌐 NuSense AIgent Dashboard - Guía de Publicación

> **Instrucciones completas para hacer público el dashboard**

## 🚀 **Opciones de Publicación**

### 1️⃣ **GitHub Pages (Gratuito)**
```bash
# Crear repositorio
git init
git add grafica_pitch_nusense.html
git commit -m "Add NuSense Dashboard"
git remote add origin https://github.com/TU_USUARIO/nusense-dashboard
git push -u origin main

# Activar GitHub Pages
Settings → Pages → Source: Deploy from branch → main → Save
```

**📍 URL Pública:** `https://TU_USUARIO.github.io/nusense-dashboard/grafica_pitch_nusense.html`

### 2️⃣ **Netlify Drop (Instantáneo)**
1. **Ir a:** https://drop.netlify.com
2. **Arrastrar** el archivo `grafica_pitch_nusense.html`
3. **Obtener** URL automática: `https://RANDOM-NAME.netlify.app`

### 3️⃣ **Vercel (Profesional)**
```bash
# Instalar CLI
npm i -g vercel

# Deploy
vercel --prod
```

### 4️⃣ **Firebase Hosting**
```bash
# Instalar CLI
npm install -g firebase-tools

# Inicializar
firebase login
firebase init hosting
firebase deploy
```

## 📁 **Estructura de Archivos Necesaria**

```
proyecto/
├── index.html (renombrar grafica_pitch_nusense.html)
├── README.md
└── assets/ (opcional)
    ├── css/
    └── js/
```

## 🔧 **Preparación del Archivo**

### **1. Renombrar archivo**
```bash
mv grafica_pitch_nusense.html index.html
```

### **2. Verificar dependencias externas**
✅ Chart.js - CDN ✅
✅ Font Awesome - CDN ✅  
✅ Google Fonts - CDN ✅
✅ No dependencias locales

### **3. Optimización para producción**
```html
<!-- Agregar meta tags SEO -->
<meta property="og:title" content="NuSense AIgent Dashboard">
<meta property="og:description" content="Academia de Excelencia Semanal">
<meta property="og:image" content="URL_DE_PREVIEW_IMAGE">
<meta name="twitter:card" content="summary_large_image">
```

## 🌍 **URLs de Ejemplo**

### **GitHub Pages**
```
https://alejandra-pinzon.github.io/nusense-dashboard/
```

### **Netlify**
```
https://nusense-dashboard.netlify.app/
```

### **Vercel**  
```
https://nusense-dashboard.vercel.app/
```

## 📱 **Compartir el Dashboard**

### **Para Presentations**
- **Formato:** `https://tu-dominio.com/`
- **QR Code:** Generar en qr-code-generator.com
- **Short URL:** Usar bit.ly o tinyurl.com

### **Para Embebido**
```html
<iframe 
  src="https://tu-dashboard-url.com/" 
  width="100%" 
  height="800px" 
  frameborder="0">
</iframe>
```

### **Para Social Media**
- **LinkedIn:** Previsualización automática con meta tags
- **Teams/Slack:** Link directo funcional
- **Email:** Compatible con todos los clientes

## ⚡ **Instrucciones Rápidas - Netlify Drop**

1. **Abrir:** https://drop.netlify.com
2. **Arrastrar:** `grafica_pitch_nusense.html`
3. **Copiar:** URL generada automáticamente
4. **Listo:** Dashboard público en 30 segundos

## 🔒 **Consideraciones de Seguridad**

- ✅ **Solo HTML/CSS/JS** - Sin datos sensibles
- ✅ **CDNs externos** - Confiables y seguros
- ✅ **No backend** - Sin riesgo de ataques
- ✅ **HTTPS automático** - En todas las plataformas

## 📊 **Monitoreo**

### **Google Analytics (Opcional)**
```html
<!-- Agregar antes de </head> -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

---

## 🎯 **Recomendación: Netlify Drop**
**La opción más rápida y sencilla para compartir inmediatamente**

1. **Drag & Drop** del archivo HTML
2. **URL pública instantánea**  
3. **HTTPS automático**
4. **Sin configuración**

**⏱️ Tiempo total: 30 segundos**

---

**📞 ¿Necesitas ayuda?** El dashboard está listo para publicar con cualquiera de estas opciones.
