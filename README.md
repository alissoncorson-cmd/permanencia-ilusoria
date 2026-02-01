[README.md](https://github.com/user-attachments/files/24989129/README.md)
# 🌍 O Chão Derretendo

**Um site interativo sobre eventos climáticos extremos, analfabetismo funcional e a velocidade do colapso no Brasil**

---

## 📖 Sobre o Projeto

Este site apresenta uma análise profunda sobre a crise climática no Brasil, combinando:
- **Ciência climática** (AMOC, Amazônia, eventos extremos)
- **Educação** (29% de analfabetismo funcional)
- **Desinformação** (fake news 6x mais rápidas que a verdade)
- **Visualização interativa** (animação do planeta derretendo)

### 🎨 Design
- **Cor principal**: Verde Amazônia (#00a86b)
- **Estilo**: Minimalista, clean, profundo
- **Animação**: Planeta interativo que derrete conforme você move o mouse
- **Responsivo**: Funciona perfeitamente em mobile e desktop

---

## 🚀 Como Hospedar no GitHub Pages (GRÁTIS)

### **Opção 1: Interface Web do GitHub (Mais Fácil)**

1. **Crie uma conta no GitHub**
   - Acesse [github.com](https://github.com)
   - Clique em "Sign up"
   - Escolha um username (será seu link: `seuusuario.github.io`)

2. **Crie um novo repositório**
   - Clique no **+** (canto superior direito)
   - Selecione "New repository"
   - **Nome do repositório**: `o-chao-derretendo`
   - Marque: **Public**
   - Clique: "Create repository"

3. **Faça upload dos arquivos**
   - Clique em "uploading an existing file"
   - Arraste os 3 arquivos:
     - `index.html`
     - `artigo.html`
     - `fontes.html`
   - Clique "Commit changes"

4. **Ative o GitHub Pages**
   - Vá em **Settings** (topo do repositório)
   - Menu lateral → **Pages**
   - Em "Source" escolha: **main** branch
   - Clique "Save"
   - Aguarde 1-2 minutos

5. **Pronto! 🎉**
   - Seu site estará em: `seuusuario.github.io/o-chao-derretendo`

---

### **Opção 2: Via Git (Para Desenvolvedores)**

```bash
# 1. Clone ou crie o repositório
git init o-chao-derretendo
cd o-chao-derretendo

# 2. Adicione os arquivos
# (cole os 3 arquivos HTML na pasta)

# 3. Commit e push
git add .
git commit -m "Initial commit: O Chão Derretendo"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/o-chao-derretendo.git
git push -u origin main

# 4. Ative GitHub Pages nas configurações do repositório
```

---

## 📁 Estrutura do Projeto

```
o-chao-derretendo/
│
├── index.html          # Página inicial (animação + preview)
├── artigo.html         # Artigo completo formatado
├── fontes.html         # Todas as fontes científicas
└── README.md          # Este arquivo
```

### **index.html** - Página Inicial
- Animação interativa do planeta derretendo
- Estatísticas em destaque (29% analfabetismo, 1M afetados, etc.)
- Preview do artigo
- Call-to-action para leitura completa

### **artigo.html** - Artigo Completo
- Texto completo do artigo formatado
- Barra de progresso de leitura
- Citações em destaque
- Boxes de dados e avisos
- Botões de compartilhamento

### **fontes.html** - Fontes Científicas
- Todas as referências categorizadas
- Links para estudos originais
- Descrição de cada fonte
- Notas sobre metodologia

---

## 🎨 Personalização

### Mudar Cores
Edite as variáveis CSS no início de cada arquivo HTML:

```css
:root {
    --amazon-green: #00a86b;      /* Verde principal */
    --dark-green: #006b45;        /* Verde escuro */
    --light-green: #3dd68c;       /* Verde claro */
    --danger-red: #ff6b6b;        /* Vermelho de alerta */
    --warning-orange: #ffa502;    /* Laranja de aviso */
}
```

### Adicionar Google Analytics
Adicione antes do `</head>`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=SEU-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'SEU-ID');
</script>
```

---

## 🌐 Outras Opções de Hospedagem Gratuita

### **Netlify** (Ainda mais fácil)
1. Acesse [netlify.com/drop](https://app.netlify.com/drop)
2. Arraste os 3 arquivos HTML
3. **Pronto!** Link gerado instantaneamente

### **Vercel**
1. Acesse [vercel.com](https://vercel.com)
2. Faça login com GitHub
3. Importe o repositório
4. Deploy automático

---

## 📱 Compartilhamento

### URLs de Compartilhamento
Os botões já incluem links para:
- **Twitter/X**
- **Facebook**
- **WhatsApp**

Após publicar, atualize o `url` nos botões de compartilhamento em `artigo.html`:

```html
<a href="https://twitter.com/intent/tweet?text=O%20Chão%20Derretendo&url=SEU-LINK-AQUI">
```

### Gerar QR Code
Use [qr-code-generator.com](https://www.qr-code-generator.com/) com seu link publicado.

---

## 📊 Fontes Científicas Principais

- **INAF 2024**: Analfabetismo Funcional no Brasil
- **PISA 2022**: Avaliação Internacional de Estudantes
- **Cemaden 2025**: Eventos Climáticos Extremos no Brasil
- **OMM 2024-2025**: Relatórios Climáticos América Latina
- **Nature/Science**: Estudos sobre AMOC e Amazônia
- **Utrecht University 2024**: Modelo de Colapso da AMOC
- **NOAA/NASA**: Dados de temperatura global

Todas as fontes detalhadas estão em `fontes.html`.

---

## 🎯 Recursos do Site

### ✅ Features Incluídas
- [x] Animação interativa responsiva
- [x] Design minimalista profissional
- [x] 100% responsivo (mobile-first)
- [x] Barra de progresso de leitura
- [x] Navegação suave entre páginas
- [x] Botões de compartilhamento social
- [x] Estatísticas em tempo real (temperatura interativa)
- [x] Categorização de fontes científicas
- [x] SEO otimizado (meta tags completas)
- [x] Performance otimizada (CSS/JS inline)

### 🚀 Melhorias Futuras Possíveis
- [ ] Modo escuro/claro
- [ ] Múltiplos idiomas
- [ ] Newsletter
- [ ] Comentários
- [ ] Mapa interativo do Brasil
- [ ] Timeline de eventos 2024-2025
- [ ] Infográficos animados

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Variáveis CSS, Flexbox, Grid, Animations
- **JavaScript Vanilla**: Canvas API para animação
- **Google Fonts**: Inter & Merriweather

**Sem dependências externas!** Tudo funciona offline após carregar.

---

## 📝 Licença e Uso

Este projeto foi criado para conscientização sobre a crise climática e educacional no Brasil.

**Você pode:**
- ✅ Usar livremente para fins educacionais
- ✅ Adaptar o conteúdo
- ✅ Compartilhar amplamente
- ✅ Hospedar sua própria versão

**Pedimos apenas:**
- 📚 Manter as referências às fontes científicas
- 🌍 Usar para conscientização, não desinformação
- 💚 Compartilhar conhecimento

---

## 📧 Contato e Contribuições

Encontrou um erro? Tem uma sugestão? Quer adicionar mais fontes?

- Abra uma **Issue** no GitHub
- Faça um **Pull Request** com melhorias
- Compartilhe nas redes sociais

---

## 🌟 Créditos

**Conteúdo**: Baseado em fontes científicas de 2024-2025  
**Design**: Minimalista com verde Amazônia  
**Animação**: Canvas API com física interativa  
**Tipografia**: Inter (UI) & Merriweather (leitura)

---

## ⚠️ Disclaimer

Este site apresenta informações baseadas em fontes científicas confiáveis. No entanto:

- A ciência climática evolui constantemente
- Existem debates legítimos sobre timing e magnitude de eventos futuros
- Apresentamos múltiplas perspectivas quando há controvérsia
- Recomendamos sempre consultar as fontes originais

**O objetivo não é gerar pânico, mas conscientização informada.**

---

## 🎉 Agradecimentos

Agradecimentos especiais a todos os cientistas, pesquisadores e instituições que tornaram seus dados públicos e acessíveis, permitindo que projetos como este existam.

---

**🌍 O chão está derretendo. E nós nem conseguimos ler o termômetro.**

---

*Última atualização: Fevereiro 2025*
