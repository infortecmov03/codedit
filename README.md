# CodeMobile APK Builder 🚀

Editor de código mobile que gera APK automaticamente via GitHub Actions.

## 📱 Download do APK

Vá para [Releases](https://github.com/SEU_USUARIO/CodeMobile/releases) e baixe o APK mais recente.

## 🛠️ Build Automático

O APK é gerado automaticamente a cada push na branch `main`.

## ✨ Funcionalidades

- 8 Linguagens de programação
- Preview em tempo real  
- Sistema de arquivos
- Integração GitHub
- Snippets de código
- Tema claro/escuro

## 📦 Estrutura

- `index.html` - Aplicação completa (HTML + CSS + JS)
- `.github/workflows/build-apk.yml` - CI/CD para APK
- `manifest.json` - Configuração PWA

## 🔧 Build Local

```bash
# Instalar Capacitor
npm install -g @capacitor/cli

# Build APK
npx cap init
npx cap add android
npx cap open android