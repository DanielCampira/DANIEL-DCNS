# 📋 GUIA DE IMAGENS - DC NEW SOLUTIONS

## ✅ Estrutura Criada

Seu site agora tem **3 seções de galerias** prontas para receber imagens:

---

## 📍 LOGO (Obrigatório) ✅ PRONTO
**Local**: `assets/images/logo.svg`  
**Status**: Já criado e integrado em todas as 9 páginas  
**Recomendação**: Substituir pelo arquivo PNG/JPG que você enviou

**Para usar sua imagem de logo:**
1. Exporte sua imagem como `logo.png` ou `logo.jpg`
2. Coloque em: `assets/images/logo.png`
3. O site carregará automaticamente

---

## 📸 SERVIÇOS (services.html)
**Local**: `assets/images/`

Adicione estas 4 imagens:
```
servico-1.jpg  → Consultoria Informática
servico-2.jpg  → Manutenção de Computadores
servico-3.jpg  → Impressão e Reprografia
servico-4.jpg  → Limpeza e Conservação
```

✨ **Efeito**: Hover com zoom + sombra

---

## 📦 PRODUTOS (produtos.html)
**Local**: `assets/images/`

Adicione estas 4 imagens:
```
produto-1.jpg  → Equipamentos Informáticos
produto-2.jpg  → Mobiliário de Escritório
produto-3.jpg  → Material de Consumo
produto-4.jpg  → Artigos Promocionais
```

✨ **Efeito**: Hover com zoom + sombra

---

## 🎨 AUTOCOLANTES E CARTÕES (também em produtos.html)
**Local**: `assets/images/`

Adicione estas 4 imagens:
```
adesivo-1.jpg  → Autocolantes Personalizados
cartao-1.jpg   → Cartões de Visita
banner-1.jpg   → Banners e Placas
flyer-1.jpg    → Flyers e Brochuras
```

✨ **Efeito**: Mesmo efeito da galeria - hover com zoom + sombra

---

## 📊 RESUMO DE ARQUIVOS NECESSÁRIOS

```
assets/images/
├── logo.svg (ou logo.png) ✅ PRONTO
├── servico-1.jpg
├── servico-2.jpg
├── servico-3.jpg
├── servico-4.jpg
├── produto-1.jpg
├── produto-2.jpg
├── produto-3.jpg
├── produto-4.jpg
├── adesivo-1.jpg
├── cartao-1.jpg
├── banner-1.jpg
└── flyer-1.jpg

TOTAL: 13 imagens (1 logo + 12 para galerias)
```

---

## 🎯 RECOMENDAÇÕES TÉCNICAS

### Tamanho das Imagens
- **Largura mínima**: 400px
- **Altura mínima**: 240px  
- **Proporção ideal**: 16:9 (como 800x480, 1200x675)
- **Peso máximo**: 500KB por imagem

### Formatos Suportados
- ✅ JPG/JPEG (melhor para fotos)
- ✅ PNG (melhor para gráficos com transparência)
- ✅ WebP (muito bom para web, mas nem todos navegadores antigos)

### Otimização
```
Ferramentas recomendadas:
- TinyPNG.com (comprime PNG/JPG)
- ImageOptim (Mac) ou FileOptimizer (Windows)
- Squoosh.app (Google - online)
```

---

## 📥 COMO ADICIONAR AS IMAGENS

### Opção 1: Drag and Drop
1. Abra a pasta `assets/images/` no explorador de arquivos
2. Arraste as imagens PNG/JPG para lá
3. O site carregará automaticamente

### Opção 2: Via VS Code
1. No VS Code, expanda `assets` → `images`
2. Clique com botão direito → "Abrir na Pasta"
3. Copie/cole os arquivos de imagem

### Opção 3: Terminal
```powershell
cd c:\Users\CAMPIRA\Documents\GitHub\meusite\assets\images
# Copie seus arquivos para este diretório
```

---

## 🎨 SUBSTITUIR LOGO SVG PELA IMAGEM PNG

Se quiser usar a imagem de logo que enviou:

1. **Exporte como PNG** (com fundo transparente é ideal)
2. **Salve como**: `logo.png` na pasta `assets/images/`
3. **Edite** o arquivo `logo.svg` e substitua pelo seu PNG:

**Abra cada HTML e mude:**
```html
<!-- De: -->
<a href="index.html" class="logo"><img src="assets/images/logo.svg" ...></a>

<!-- Para: -->
<a href="index.html" class="logo"><img src="assets/images/logo.png" ...></a>
```

Ou envie o arquivo e fazemos a substituição para você.

---

## 🖼️ PREVIEW NO SITE

Após adicionar as imagens, elas aparecerão em:

- 🔗 **Página Inicial**: [seu-site]/index.html (logo no topo)
- 🔗 **Serviços**: [seu-site]/services.html (galeria com 4 imagens)
- 🔗 **Produtos**: [seu-site]/produtos.html
  - Galeria de produtos (4 imagens)
  - Galeria de autocolantes (4 imagens)

---

## ✨ EFEITOS INCLUSOS

- ✅ **Hover com Zoom**: Imagens crescem 5% ao passar o mouse
- ✅ **Sombra Dinâmica**: Carta eleva-se na tela
- ✅ **Transição Suave**: 0.3s de animação
- ✅ **Responsive**: Funciona em mobile, tablet e desktop
- ✅ **Lazy Loading**: Imagens carregam sob demanda (melhor performance)

---

## 🚨 TROUBLESHOOTING

### Imagem não aparece?
```
✓ Verifique se o nome do arquivo está EXATO
  (ex: servico-1.jpg, não servico_1.jpg)
✓ Coloque em: assets/images/
✓ Recarregue a página (Ctrl+F5 para cache)
```

### Imagem está muito grande/pequena?
A galeria usa `object-fit: cover` - a proporção 16:9 fica perfeita
Se usar outra proporção, a imagem será cortada para caber

### Site carrega mas imagem é cinza?
Placeholder automático aparece quando imagem não existe  
Significa que a pasta/arquivo está errado

---

## 📞 PRÓXIMOS PASSOS

1. **Recolha as imagens** (logotipo, fotos de serviços/produtos, autocolantes)
2. **Coloque na pasta** `assets/images/`
3. **Nomeie corretamente** conforme instruções acima
4. **Recarregue o site** e pronto! ✅

---

**Site criado em**: 6 de fevereiro de 2026  
**Última atualização**: 6 de fevereiro de 2026  
**Versão**: 2.0 (Com suporte a galerias de imagens)

