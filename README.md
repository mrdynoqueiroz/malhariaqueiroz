# 🎨 Aplicativo Web de Design de Camisas e Uniformes - Malharia Queiroz

## ✨ Sobre o Projeto

Um aplicativo web **completo e profissional** para criar designs de camisas, uniformes e camisetas da Malharia Queiroz. Construído com HTML5, CSS3 e JavaScript vanilla, oferece uma experiência premium de designer gráfico interativo.

---

## 🎯 Funcionalidades Principais

### 1. **Designer Interativo de Camisas**
- Canvas em tempo real (500x600px)
- Visualização imediata de todas as alterações
- Pré-visualização profissional da camisa

### 2. **Customização Completa**
- **Cor da Camisa**: Paleta com 8 cores pré-definidas + cor customizada
- **Logo/Imagem**: Upload de PNG ou JPG com fundo transparente
- **Posicionamento**: Controle horizontal (X) e vertical (Y) da imagem
- **Tamanho**: Redimensionamento da imagem/logo (50-400px)
- **Rotação**: Girar imagem até 360 graus
- **Texto**: Adicionar texto customizável com:
  - Tamanho variável (12-60px)
  - Cor personalizável
  - Texto em MAIÚSCULAS automático

### 3. **Controles Avançados**
- **Sliders dinâmicos** com feedback visual em tempo real
- **Color pickers** profissionais
- **Upload de arquivo** com validação
- **Botões de ação**:
  - 📥 **Baixar Design** - Salva como PNG
  - 📤 **Compartilhar** - Envia para WhatsApp
  - 🔄 **Resetar** - Retorna aos valores padrão

### 4. **Design & UX**
- Interface responsiva (desktop, tablet, mobile)
- Tema luxuoso (cores: ouro, preto, creme)
- Tipografia premium (Playfair Display, Jost, Cormorant Garamond)
- Animações suaves e transições elegantes
- Layout em grid 2 colunas (preview + controles)

---

## 🌟 Seções do Site

1. **Navbar Fixa** - Navegação com efeito scroll
2. **Hero Section** - Apresentação impactante
3. **Sobre Nós** - Informações com estatísticas
4. **Malhas** - 6 tipos de tecidos disponíveis
5. **Serviços** - 6 serviços principais + Destaque DTF
6. **Diferenciais** - 4 pontos-chave da qualidade
7. **Designer de Camisas** - ⭐ NOVO! Editor interativo
8. **Contato** - Formulário e informações
9. **Footer** - Links e informações legais
10. **WhatsApp Float** - Botão flutuante com animação

---

## 🚀 Como Usar

### **Acessar o Aplicativo**
```bash
# Servidor já está rodando em:
http://localhost:8000/malharia-queiroz.html
```

### **Designer - Passo a Passo**
1. Escolha a cor da camisa clicando em um dos presets ou use o color picker
2. Upload um logo/imagem (PNG com fundo transparente recomendado)
3. Ajuste a posição (X, Y) usando os sliders
4. Redimensione a imagem conforme necessário
5. Rode a imagem se necessário
6. Adicione texto customizado
7. Escolha a cor do texto
8. Ajuste o tamanho do texto
9. **Baixe** o design como PNG ou **compartilhe** pelo WhatsApp
10. Converse com a Malharia Queiroz para providenciar a estampa DTF

---

## 💻 Tecnologias Utilizadas

### Frontend
- **HTML5** - Estrutura semântica
- **CSS3** - Design responsivo, Grid, Flexbox, Animações
- **JavaScript (Vanilla)** - Lógica interativa, Canvas API
- **HTML2Canvas** - Exportação de canvas para imagem

### Bibliotecas Externas
- **Google Fonts** - Tipografia premium
- **HTML2Canvas.js** - Captura de canvas

### Ferramentas
- **Python HTTP Server** - Servidor local
- **VS Code** - Editor de código

---

## 📊 Estrutura do Projeto

```
/Users/dynoqz/TRABALHO DINO/
├── malharia-queiroz.html    (Aplicativo completo)
├── README.md                  (Este arquivo)
└── [Servidor rodando em :8000]
```

---

## ⚙️ Configuração Técnica

### Canvas
- **Dimensões**: 500x600px
- **Renderização**: 2D Context
- **Elementos**: Fundo, Gola, Imagem, Texto com sombra

### Responsividade
- Breakpoint tablet: 900px
- Breakpoint mobile: 600px
- Grid adapta-se automaticamente

### Performance
- Renderização em tempo real sem lag
- Otimização de eventos (input, change)
- Lazy loading de imagens

---

## 🎨 Paleta de Cores

| Cor | Código | Uso |
|-----|--------|-----|
| Ouro | #C9A84C | Acentos, títulos |
| Ouro Claro | #E2C47A | Hover states |
| Preto | #080808 | Fundo principal |
| Cinza Claro | #1a1a1a | Fundos secundários |
| Creme | #F5F0E8 | Texto principal |

---

## 🔧 Funcionalidades Técnicas Avançadas

### Canvas API
```javascript
// Desenho dinâmico com rotação e transformação
ctx.save();
ctx.translate(x, y);
ctx.rotate(angle);
ctx.drawImage(img, ...);
ctx.restore();
```

### Event Listeners Inteligentes
- Color input com picker
- Range sliders com feedback
- File upload com validação
- Canvas refresh em tempo real

### Exportação
- PNG de alta qualidade
- Compartilhamento WhatsApp
- Reset automático de estados

---

## 📱 Recursos Mobile

- Layout responsivo em coluna única
- Touch-friendly controls
- Color picker otimizado
- Botões de ação em tamanho adequado

---

## ✅ Testes Realizados

- ✅ Página abre sem erros
- ✅ Canvas renderiza corretamente
- ✅ Sliders funcionam com feedback visual
- ✅ Upload de imagem funciona
- ✅ Color picker atualiza em tempo real
- ✅ Texto atualiza corretamente
- ✅ Buttons funcionam
- ✅ Responsividade funcionando
- ✅ Animações suaves
- ✅ Navegação funciona

---

## 🚨 Troubleshooting

### Canvas não aparece
- Verificar se JavaScript está habilitado
- Limpar cache do navegador (Ctrl+Shift+Delete)

### Imagem não carrega
- Usar PNG ou JPG
- Arquivo máximo 5MB
- Fundo transparente recomendado

### Designer não responde
- Recarregar página (F5)
- Verificar console (F12) para erros

---

## 📞 Contato para Pedidos

Após criar seu design perfeito:

📱 **WhatsApp**: (94) 99132-2940
📧 **Email**: malharia.queiroz03@gmail.com
📍 **Endereço**: Vila Taboca, São Félix do Xingu - PA

---

## 📜 Copyright

© 2025 Malharia Queiroz - Todos os direitos reservados.

Uniformes & Camisetas Premium - São Félix do Xingu, Pará, Brasil

---

## 🎓 Desenvolvido com ❤️ para a Malharia Queiroz

**Versão**: 1.0.0
**Data**: 28 de março de 2026
**Status**: ✅ Produção
