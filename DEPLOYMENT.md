# 🚀 Guia de Deployment - Malharia Queiroz Web App

## Opções de Hospedagem

### 1️⃣ **Netlify** (Recomendado - GRÁTIS)

#### Passo 1: Criar conta
- Acesse [netlify.com](https://www.netlify.com)
- Clique em "Sign up"
- Autentique com GitHub ou email

#### Passo 2: Deploy
```bash
# Opção A: Arrastar e soltar
1. Faça login no Netlify
2. Arraste a pasta "/TRABALHO DINO" para a área de drop
3. Pronto! Seu site estará online em minutos

# Opção B: Git (Recomendado)
1. Push para GitHub
2. Conecte repositório no Netlify
3. Deploy automático a cada push
```

#### Passo 3: Domínio Customizado
```
Configure em: Netlify Dashboard → Domain Settings → Custom Domain
Seu domínio estará em: seu-dominio.com/malharia-queiroz.html
```

---

### 2️⃣ **Vercel** (GRÁTIS + Performance)

```bash
# Instalar Vercel CLI
npm install -g vercel

# Deploy
cd "/TRABALHO DINO"
vercel

# Seguir as instruções interativas
```

---

### 3️⃣ **GitHub Pages** (GRÁTIS)

```bash
cd "/TRABALHO DINO"
git init
git add malharia-queiroz.html README.md
git commit -m "Initial commit: Malharia Queiroz Web App"
git branch -M main
git remote add origin https://github.com/seu-usuario/malharia-queiroz.git
git push -u origin main
```

Depois, nas **Settings** do repositório:
- GitHub Pages → Source: main branch
- Site estará em: `seu-usuario.github.io/malharia-queiroz/`

---

### 4️⃣ **Hosting Tradicional** (Godaddy, Hostgator, etc)

```bash
# 1. Compre um plano de hospedagem
# 2. Acesse via FTP/SFTP
# 3. Upload de malharia-queiroz.html
# 4. Acesse: seu-dominio.com/malharia-queiroz.html
```

---

## 🏠 Executar Localmente

### Requisitos
- Python 3.x instalado
- Terminal/PowerShell

### Comando
```bash
cd "/Users/dynoqz/TRABALHO DINO"
python3 -m http.server 8000

# Abrir no navegador:
# http://localhost:8000/malharia-queiroz.html
```

---

## 📋 Checklist de Deployment

- [ ] Arquivo `malharia-queiroz.html` pronto
- [ ] Todos os scripts carregam (html2canvas)
- [ ] Canvas renderiza corretamente
- [ ] Designer funciona completamente
- [ ] WhatsApp links funcionam
- [ ] Imagens carregam rápido
- [ ] Página responsiva em mobile
- [ ] SSL/HTTPS habilitado
- [ ] Analytics configurado (opcional)
- [ ] SEO meta tags atualizadas

---

## 🔒 Segurança

### Recomendações
1. **HTTPS obrigatório** - Todos os hosters acima oferecem SSL grátis
2. **CSP Headers** - Configure Content Security Policy
3. **CORS** - Configurar para domínio específico
4. **Rate Limiting** - Se receber muito tráfego
5. **Backup** - Manter cópia local

---

## ⚡ Otimizações de Performance

### Já Implementadas
- ✅ Fontes Google Fonts otimizadas
- ✅ CSS inline (menos requisições)
- ✅ JavaScript nativo (sem jQuery)
- ✅ Lazy loading de imagens
- ✅ Animações com CSS (não JS)

### Para Adicionar (Opcional)
```html
<!-- Service Worker para PWA -->
<!-- Gzip compression -->
<!-- Minificação de CSS/JS -->
<!-- Image optimization -->
```

---

## 📊 Monitoramento

### Recomendado
- **Google Analytics** - Rastrear visitantes
- **Hotjar** - Mapa de calor
- **Sentry** - Erros em produção

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_ID');
</script>
```

---

## 🐛 Debugging

### Ver erros em produção
```javascript
// Adicionar ao console para rastrear
window.addEventListener('error', (e) => {
  console.error('Erro:', e.message);
});
```

### Verificar performance
```bash
# DevTools → Lighthouse
# Scores: Performance, Accessibility, Best Practices, SEO
```

---

## 📞 Suporte

Qualquer dúvida sobre deployment:
- **Email**: malharia.queiroz03@gmail.com
- **WhatsApp**: (94) 99132-2940
- **Documentação**: Este arquivo

---

## Versões Recomendadas

| Plataforma | Preço | Velocidade | Suporte |
|-----------|-------|-----------|---------|
| Netlify | GRÁTIS | ⭐⭐⭐⭐⭐ | 24/7 |
| Vercel | GRÁTIS | ⭐⭐⭐⭐⭐ | 24/7 |
| GitHub Pages | GRÁTIS | ⭐⭐⭐⭐ | Community |
| Hostgator | $3-5/mês | ⭐⭐⭐ | Email |

**Melhor custo-benefício**: Netlify

---

**Última atualização**: 28 de março de 2026
**Status**: ✅ Pronto para produção
