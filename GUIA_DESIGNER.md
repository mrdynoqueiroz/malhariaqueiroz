# 🎨 Guia Completo do Designer de Camisas

## 📖 Índice Rápido
1. [Começando](#começando)
2. [Cores da Camisa](#cores-da-camisa)
3. [Adicionar Imagem](#adicionar-imagem)
4. [Posicionar Elementos](#posicionar-elementos)
5. [Adicionar Texto](#adicionar-texto)
6. [Salvar e Compartilhar](#salvar-e-compartilhar)
7. [Dicas Profissionais](#dicas-profissionais)
8. [Troubleshooting](#troubleshooting)

---

## 🚀 Começando

### Acessar o Designer
1. Acesse: `http://localhost:8000/malharia-queiroz.html`
2. Scroll até a seção **"Crie seu Design de Camisa Agora"**
3. Você verá duas colunas:
   - **Esquerda**: Pré-visualização da camisa
   - **Direita**: Controles de customização

### Interface Básica
```
┌─────────────────────────────────┐
│  PREVIEW DA CAMISA              │  ← Veja seu design em tempo real
│  (Canvas branco com gola)       │
│                                 │
│  [📥] [📤] [🔄]                │  ← Botões de ação
└─────────────────────────────────┘

┌─────────────────────────────────┐
│  CONTROLES                      │
│  • Cor da Camisa                │
│  • Upload de Imagem             │
│  • Posição X/Y                  │
│  • Tamanho                      │
│  • Rotação                      │
│  • Texto                        │
│  • Cor do Texto                 │
│  • Tamanho do Texto             │
└─────────────────────────────────┘
```

---

## 🎨 Cores da Camisa

### Método 1: Usar Presets
Clique em um dos 8 botões de cor pré-definidas:
- ⚪ Branco (Default)
- ⚫ Preto
- 🔴 Vermelho
- 🔵 Azul
- 🟢 Verde
- 🟡 Amarelo
- 🟠 Laranja
- 🟣 Magenta

### Método 2: Cor Customizada
1. Clique no **color picker** (retângulo colorido)
2. A paleta nativa do navegador abrirá
3. Escolha a cor desejada
4. Clique OK ou selecione com o cursor

### Dica Profissional
- Branco: Melhor para estampas coloridas
- Preto: Clássico, contraste alto
- Cores pastel: Tendência moderna
- Cores vibrantes: Eventos e esportes

---

## 🖼️ Adicionar Imagem

### Requisitos
- **Formato**: PNG ou JPG
- **Tamanho máximo**: 5MB
- **Recomendação**: Fundo transparente (PNG)

### Como Fazer
1. Clique em "Enviar Imagem/Logo"
2. Selecione um arquivo do seu computador
3. A imagem aparecerá no preview em tempo real
4. Agora você pode posicionar e redimensionar

### Tipos de Imagem Recomendados
- 🏢 Logo da empresa (PNG transparente)
- 👥 Foto de perfil (quadrada)
- 🎨 Arte customizada (em PNG)
- 📱 Stickers (transparentes)
- 🏆 Badges ou medalhas

### Dica
Após fazer upload:
- Certifique-se de que a imagem está centrada
- Não deixe muito grande (máx 300px recomendado)
- Fundo transparente não aparecerá na camisa final

---

## 📍 Posicionar Elementos

### Posição Horizontal (X)
```
Eixo X:
0px ←──────────→ 400px
Esq            Dir
```

**Como usar:**
- Mova o slider para alterar a posição horizontal
- 0px = extrema esquerda
- 200px = centro aproximado
- 400px = extrema direita

**Valores Comuns:**
- Esquerda: 50-100px
- Centro: 150-200px
- Direita: 300-350px

### Posição Vertical (Y)
```
Eixo Y:
0px (Topo)
   ↓
500px (Fundo)
```

**Como usar:**
- Mova o slider para alterar a posição vertical
- 0px = topo
- 250px = meio
- 500px = fundo

**Valores Comuns:**
- Topo (ombro): 50-100px
- Peito (centro): 200-250px
- Cintura: 350-400px

### Visualização em Tempo Real
A camisa atualiza **instantaneamente** conforme você move os sliders.

---

## 📏 Tamanho da Imagem

### Range
- **Mínimo**: 50px (muito pequeno)
- **Máximo**: 400px (muito grande)
- **Recomendado**: 150-250px

### Como Ajustar
1. Mova o slider de tamanho
2. Veja o resultado no preview
3. 200px é um bom ponto de partida

### Dicas
- Imagem muito pequena: difícil ver detalhes
- Imagem muito grande: domina a camisa
- Teste diferentes tamanhos para seu design

---

## 🔄 Rotação

### Range
- **Mínimo**: 0° (vertical)
- **Máximo**: 360° (volta completa)

### Ângulos Comuns
- 0° = Posição normal (vertical)
- 45° = Diagonal
- 90° = Horizontal deitada
- 180° = De cabeça para baixo
- 270° = Horizontal (outra direção)

### Uso Prático
1. Mantenha em 0° para a maioria dos casos
2. Use 45° para efeito diagonal criativo
3. Use 90° para logos horizontais transformarem em verticais

---

## ✍️ Adicionar Texto

### Campo de Texto
1. Clique em "Texto da Camisa"
2. Digite seu texto
3. Será convertido automaticamente para MAIÚSCULAS
4. Aparece na camisa em tempo real

### Exemplos
- "MALHARIA QUEIROZ"
- "SUA EMPRESA"
- "TIMES 2026"
- "UNIFORME PREMIUM"

### Tamanho do Texto
- **Pequeno**: 12-18px (delicado)
- **Médio**: 25-35px (padrão)
- **Grande**: 40-60px (destaque)

### Cor do Texto
1. Clique no color picker de texto
2. Escolha uma cor que contraste com a camisa
3. A cor atualiza imediatamente

### Contraste Recomendado
| Camisa | Texto Melhor |
|--------|-------------|
| Branca | Preto, azul, vermelho |
| Preta | Branco, ouro, amarelo |
| Vermelha | Branco, preto |
| Azul | Branco, amarelo |
| Verde | Branco, preto |

---

## 💾 Salvar e Compartilhar

### Opção 1: Baixar Design (📥)
```
Clique em "Baixar Design"
↓
Arquivo "design-camisa.png" será baixado
↓
Salve em seu computador
↓
Pode enviar para a Malharia Queiroz
```

**Arquivo**: PNG de alta qualidade
**Tamanho**: ~50-200KB (dependendo da imagem)

### Opção 2: Compartilhar no WhatsApp (📤)
```
Clique em "Compartilhar"
↓
WhatsApp Web abre
↓
Mensagem pré-preenchida com seu design
↓
Escolha o contato e envie
```

**Nota**: Seu navegador deve ter WhatsApp Web instalado

### Opção 3: Resetar Design (🔄)
```
Clique em "Resetar"
↓
Todos os valores voltam ao padrão
↓
Camisa branca, sem imagem, texto "SEU TEXTO"
```

---

## 💡 Dicas Profissionais

### Design de Alto Nível
1. **Simplicidade**: Menos é mais
   - Use 1-2 cores principais
   - Logo simples e legível
   
2. **Contraste**: Legibilidade é tudo
   - Texto escuro em fundo claro
   - Texto claro em fundo escuro
   
3. **Posicionamento**: Balanceamento visual
   - Logo no centro ou peito
   - Texto na base ou ombro
   - Deixe espaços em branco
   
4. **Tamanho**: Proporção adequada
   - Logo não pode ser muito grande
   - Texto deve ser legível de longe

### Exemplos de Bom Design
- ✅ Logo pequeno no peito + empresa em texto na base
- ✅ Camisa colorida + logo monocromático = contraste
- ✅ Estampa centralizada + texto subtil
- ✅ Design simétrico e balanceado

### Exemplos de Ruim Design
- ❌ Imagem muito grande domina toda camisa
- ❌ Logo e texto com cores similares = sem contraste
- ❌ Muitas imagens/textos concorrendo por espaço
- ❌ Cores muito vibrantes juntas = agressivo

---

## 🔧 Troubleshooting

### Problema: Canvas em branco
**Solução**:
1. Recarregue a página (F5)
2. Verificar se JavaScript está habilitado
3. Limpar cache do navegador

### Problema: Imagem não carrega
**Verificar**:
- Arquivo é PNG ou JPG?
- Tamanho menor que 5MB?
- Caminho correto?

**Solução**:
1. Tentar outro arquivo
2. Converter para PNG se for JPG
3. Reduzir tamanho da imagem

### Problema: Texto não aparece
**Verificar**:
- Digitou o texto?
- Cor do texto é similar à da camisa?

**Solução**:
1. Mudança cor do texto
2. Aumentar tamanho do texto
3. Escrever texto novamente

### Problema: Download não funciona
**Verificar**:
- Pop-ups bloqueadas?
- Navegador desatualizado?

**Solução**:
1. Permitir pop-ups para o site
2. Atualizar navegador
3. Tentar outro navegador

### Problema: Designer muito lento
**Verificar**:
- Imagem muito grande?
- Muitos elementos?

**Solução**:
1. Reduzir tamanho da imagem (upload)
2. Usar PNG ao invés de JPG
3. Fechar outras abas/programas

---

## 📞 Próximos Passos

### Após Criar Seu Design
1. **Baixe** o PNG do design
2. **Compartilhe** conosco via WhatsApp
3. **Escolha** a malha desejada (veja seção Malhas)
4. **Solicite** orçamento na Malharia Queiroz
5. **Acompanhe** a produção do seu uniforme

### Contato
- 📱 **WhatsApp**: (94) 99132-2940
- 📧 **Email**: malharia.queiroz03@gmail.com
- 📍 **Endereço**: Vila Taboca, São Félix do Xingu - PA

---

## 🎓 Video Tutorial (Se Disponível)

[Link para video tutorial em YouTube - em breve]

---

## ⭐ Feedback

Gostou do designer? Tem sugestões?
Envie um WhatsApp para a Malharia Queiroz!

---

**Versão**: 1.0
**Data**: 28 de março de 2026
**Status**: ✅ Pronto para usar
