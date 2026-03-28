# 🆘 FAQ & Troubleshooting

## ❓ Perguntas Frequentes

### 1. O aplicativo não carrega?
**Solução:**
```bash
# Certifique-se que o servidor está rodando
cd "/Users/dynoqz/TRABALHO DINO"
python3 -m http.server 8000

# Abra: http://localhost:8000/malharia-queiroz.html
# (não esqueça .html no final da URL)
```

### 2. Canvas está em branco?
**Verificar:**
- JavaScript está habilitado no navegador?
- Console tem erros? (F12 → Console)
- Recarregue a página (F5)

**Solução:**
```javascript
// No console, digitar:
window.designador
// Deve retornar um objeto com propriedades
```

### 3. Imagem não carrega após upload?
**Verificar:**
- Arquivo é PNG ou JPG?
- Tamanho < 5MB?
- Caminho correto no explorador?

**Solução:**
1. Tentar outro arquivo
2. Converter para PNG se for JPG
3. Comprimir imagem se for muito grande

### 4. Texto não aparece?
**Verificar:**
- Digitou o texto no campo?
- Cor do texto é diferente da camisa?

**Solução:**
1. Mudar cor do texto
2. Aumentar tamanho do texto
3. Movimentar posição (pode estar fora da visualização)

### 5. Botão de download não funciona?
**Verificar:**
- Pop-ups estão bloqueadas?
- Navegador desatualizado?

**Solução:**
1. Desbloquear pop-ups (clique no ícone de bloqueio na barra)
2. Atualizar navegador
3. Tentar outro navegador (Chrome, Firefox)

### 6. Compartilhar WhatsApp não abre?
**Verificar:**
- WhatsApp Web está aberto?
- Navegador tem permissão?

**Solução:**
1. Abrir WhatsApp Web em outro aba
2. Recarregar página
3. Tentar novamente

### 7. Design demora para atualizar?
**Verificar:**
- Imagem é muito grande?
- Navegador está lento?

**Solução:**
1. Reduzir tamanho da imagem (upload)
2. Fechar outras abas
3. Reiniciar navegador

---

## 🔧 Troubleshooting Avançado

### Designer não responde a cliques
```javascript
// No console, verificar:
document.getElementById('corCamisa') // deve existir
document.getElementById('designCanvas') // deve existir

// Verificar se evento está registrado:
// F12 → Elements → selecione #corCamisa → Event Listeners
```

### Canvas não renderiza imagem
```javascript
// No console:
window.designador.imagemUpload
// Se for null, nenhuma imagem foi carregada
```

### Performance lenta
```javascript
// Verificar tamanho da imagem:
window.designador.tamanhoImagem
// Reduzir para < 250px

// Verificar FPS:
// F12 → Performance → Record
```

---

## 🌐 Compatibilidade de Navegadores

| Navegador | Funciona | Versão Min |
|-----------|----------|-----------|
| Chrome | ✅ | 60+ |
| Firefox | ✅ | 55+ |
| Safari | ✅ | 11+ |
| Edge | ✅ | 79+ |
| Opera | ✅ | 47+ |
| IE 11 | ❌ | Não |

**Recomendado**: Chrome ou Firefox (melhor performance)

---

## 📱 Problemas Mobile

### Sliders muito sensíveis?
**Solução**: Use valores redondos (0, 50, 100, etc)

### Color picker não abre?
**Solução**: Alguns navegadores não suportam color picker mobile
- Use outro navegador
- Use desktop

### Canvas muito pequeno?
**Solução**: Zoom do navegador
- Pinch (dois dedos) para zoom out
- Ou use Ctrl + "-" no desktop

---

## 🖥️ Problemas de Servidor

### Porta 8000 já está em uso?
```bash
# Usar outra porta:
python3 -m http.server 9000

# Abrir: http://localhost:9000/malharia-queiroz.html
```

### Erro: "Address already in use"?
```bash
# Encontrar processo usando porta 8000:
lsof -i :8000

# Matar o processo:
kill -9 <PID>

# Depois reiniciar servidor
```

### Servidor não inicia?
```bash
# Verificar se Python está instalado:
python3 --version

# Deve mostrar Python 3.x.x
```

---

## 💾 Backup e Recuperação

### Fiz alterações e quero reverter?
```bash
# Git (se disponível):
git checkout malharia-queiroz.html

# Ou simplesmente redownload o arquivo original
```

### Posso fazer cópia de segurança?
```bash
# Copiar arquivo:
cp malharia-queiroz.html malharia-queiroz-backup.html

# Restaurar de backup:
cp malharia-queiroz-backup.html malharia-queiroz.html
```

---

## 🔍 Verificar Funcionalidade

### Teste Rápido
1. Abrir página
2. Mudar cor da camisa (clique em um preset)
   - ✅ Preview deve mudar
3. Upload uma imagem
   - ✅ Deve aparecer no canvas
4. Mover slider de posição
   - ✅ Imagem deve se mover
5. Digitar um texto
   - ✅ Texto deve aparecer na camisa

Se tudo acima funcionar, o site está 100% OK! ✅

---

## 📊 Debug Console Útil

```javascript
// Ver estado completo do designer:
console.table(window.designador)

// Testar renderização:
window.designador.desenharCamisa()

// Resetar:
window.designador.resetar()

// Ver canvas:
console.log(document.getElementById('designCanvas'))

// Exportar dados (para compartilhamento):
const dados = {
  cor: window.designador.corCamisa,
  texto: window.designador.texto,
  tamanho: window.designador.tamanhoImagem,
  posX: window.designador.posX,
  posY: window.designador.posY
}
console.table(dados)
```

---

## 🚀 Performance Tips

### Para melhorar velocidade:
1. Usar navegador moderno (Chrome, Firefox)
2. Fechar abas desnecessárias
3. Desabilitar extensões (ad blocker, etc)
4. Usar internet com boa velocidade
5. Imagens < 1MB

### Para melhorar capacidade de resposta:
1. Não enviar imagens muito grandes
2. Usar sliders ao invés de digitar valores
3. Resetar design se ficar lento
4. Atualizar navegador

---

## 💬 Como Relatar Problemas

Se encontrar um bug:

1. **Descreva o problema**
   - O que você estava fazendo?
   - O que aconteceu?

2. **Forneça detalhes**
   - Navegador: Chrome, Firefox, etc
   - Sistema: Windows, Mac, Linux
   - Versão: Qual versão do navegador?

3. **Screenshots**
   - F12 → Console → copiar erros

4. **Enviar para**
   - WhatsApp: (94) 99132-2940
   - Email: malharia.queiroz03@gmail.com

---

## ✅ Checklist de Funcionamento

- [ ] Página carrega sem erros
- [ ] Canvas renderiza
- [ ] Cor da camisa muda
- [ ] Imagem pode ser feita upload
- [ ] Posição X/Y funciona
- [ ] Tamanho da imagem funciona
- [ ] Rotação funciona
- [ ] Texto aparece na camisa
- [ ] Cor do texto muda
- [ ] Tamanho do texto muda
- [ ] Botão "Baixar" funciona
- [ ] Botão "Compartilhar" abre WhatsApp
- [ ] Botão "Resetar" volta ao padrão
- [ ] Página é responsiva no mobile
- [ ] Links de navegação funcionam

Se TODOS os itens estão ✅, tudo funciona perfeitamente!

---

## 📞 Suporte

**Ainda com dúvidas?**

Contate a Malharia Queiroz:
- 📱 WhatsApp: (94) 99132-2940
- 📧 Email: malharia.queiroz03@gmail.com
- 📍 Presencial: Vila Taboca, São Félix do Xingu - PA

Responderemos em até 1 hora nos dias úteis! ⚡

---

**Última atualização**: 28 de março de 2026
**Versão**: 1.0.0
**Status**: ✅ Pronto para usar
