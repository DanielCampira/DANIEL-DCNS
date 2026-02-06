# 📸 COMO ADICIONAR IMAGENS - PASSO A PASSO

## 🎯 TÊS OPÇÕES FÁCEIS:

---

## ✅ OPÇÃO 1: EXPLORADOR DE FICHEIROS (Mais Fácil!)

### Passo 1: Abrir a Pasta de Imagens
```
1. Abre o Windows Explorer
2. Navega para: 
   C:\Users\CAMPIRA\Documents\GitHub\meusite\assets\images

3. Deverás ver a pasta com estes ficheiros:
   ✅ logo.svg (já existe)
   ✅ README.md
   - (os outros devem estar vazios)
```

### Passo 2: Preparar as Imagens
```
Tens as imagens em lugar nenhum?

OPÇÃO A - Se as imagens estão numa pasta:
  1. Coloca as imagens numa pasta no teu computador
     (ex: C:\MinhasImagens\DCNewSolutions\)
  
OPÇÃO B - Se as imagens estão espalhadas:
  1. Cria uma pasta chamada "DC_Imagens" 
  2. Coloca TODAS as imagens lá
```

### Passo 3: Renomear as Imagens CORRECTAMENTE

**MUITO IMPORTANTE**: Os nomes devem ser EXACTOS!

```
Renomeia assim:

LOGO:
├── logo.png (ou guarda como logo.svg que já existe)

SERVIÇOS (4 imagens):
├── servico-1.jpg
├── servico-2.jpg
├── servico-3.jpg
└── servico-4.jpg

PRODUTOS (4 imagens):
├── produto-1.jpg
├── produto-2.jpg
├── produto-3.jpg
└── produto-4.jpg

AUTOCOLANTES (4 imagens):
├── adesivo-1.jpg
├── cartao-1.jpg
├── banner-1.jpg
└── flyer-1.jpg
```

**COMO RENOMEAR um ficheiro:**
```
1. Clica com botão direito no ficheiro
2. Escolhe "Renomear"
3. Digita o nome EXACTO (ex: servico-1.jpg)
4. Carrega em Enter
```

### Passo 4: COPIAR as Imagens

```
1. Open a pasta com as tuas imagens
   (ex: C:\MinhasImagens\DCNewSolutions\)

2. Selecciona TODAS as imagens:
   - Clica em Ctrl+A
   - Ou selecciona 1 a 1 com Ctrl+Click

3. COPIA: Ctrl+C

4. NAVEGA para:
   C:\Users\CAMPIRA\Documents\GitHub\meusite\assets\images

5. COLA: Ctrl+V

6. Deverás ver algo assim:
   assets/images/
   ├── logo.svg ✅
   ├── README.md
   ├── servico-1.jpg ✅
   ├── servico-2.jpg ✅
   ├── servico-3.jpg ✅
   ├── servico-4.jpg ✅
   ├── produto-1.jpg ✅
   ├── produto-2.jpg ✅
   ├── produto-3.jpg ✅
   ├── produto-4.jpg ✅
   ├── adesivo-1.jpg ✅
   ├── cartao-1.jpg ✅
   ├── banner-1.jpg ✅
   └── flyer-1.jpg ✅
```

### Passo 5: Verificar no Site

```
1. Abre o site:
   - Duplo-clique em C:\Users\CAMPIRA\Documents\GitHub\meusite\index.html
   - Ou abre no navegador

2. Verifica se as imagens aparecem:
   📄 Página Inicial (index.html)
      → Logo no topo centrado
   
   🔧 Serviços (services.html) 
      → 4 imagens de serviços
   
   📦 Produtos (produtos.html)
      → 4 imagens de produtos
      → 4 imagens de autocolantes
```

---

## ✅ OPÇÃO 2: VS CODE (Se Preferir)

```
1. Abrir VS Code
2. Abrir a pasta do projeto:
   File → Open Folder
   Selecciona: C:\Users\CAMPIRA\Documents\GitHub\meusite

3. No painel esquerdo, expande:
   📁 assets
      📁 images

4. Clica com botão direito em "images"
5. Escolhe "Open in File Explorer"

6. Cole as imagens lá (como descrito acima)

7. VS Code recarrega automático
```

---

## ✅ OPÇÃO 3: TERMINAL (Para Quem Prefere)

```powershell
# Abrir PowerShell como Administrador e rodar:

cd C:\Users\CAMPIRA\Documents\GitHub\meusite\assets\images
dir  # Ver o que já existe

# Depois, copia os ficheiros para lá manualmente
# ou usa comando:
# copy "C:\Teu_Local\*.*" .
```

---

## 🎨 FORMATOS SUPORTADOS

Usa **estes formatos**:
- ✅ **JPG** (melhor para fotos) - nome: `servico-1.jpg`
- ✅ **PNG** (para gráficos) - nome: `servico-1.png`
- ✅ **WebP** (muito pequeno) - nome: `servico-1.webp`

---

## 📏 TAMANHOS RECOMENDADOS

Para ficarem bonitas:

```
LARGURA mínima: 400px
ALTURA mínima: 240px

IDEAL: 800x480 ou 1200x675

PESO máximo: 500KB por imagem

Exemplo:
- Uma foto de 5MB é demasiado pesada
- Comprime para ~200KB antes de adicionar
```

---

## 🔧 COMO COMPRIMIR IMAGENS (Grátis)

Se as tuas imagens são muito grandes:

### Online (Sem instalar nada):
```
1. Vai para: https://tinypng.com
2. Arrasta a imagem
3. Descarrega comprimida
4. Renomeia (ex: servico-1.jpg)
5. Cola na pasta assets/images/
```

### No Windows (Usando Paint):
```
1. Clica direito na imagem → Abrir com → Paint
2. Ficheiro → Guardar como
3. Escolhe tipo JPEG ou PNG
4. Muda para 800x480px (se quiser)
5. Guarda na pasta certa com nome certo
```

---

## 🚨 SE AS IMAGENS NÃO APARECEM

### Verificação 1: Nome Correcto?
```
❌ ERRADO:
   - Servico1.jpg (maiúscula S)
   - servico 1.jpg (espaço)
   - servico_1.jpg (underscore)
   - servico-1 (sem extensão)

✅ CERTO:
   - servico-1.jpg (tudo minúsculo)
   - produto-2.png (extensão correcta)
```

### Verificação 2: Local Correcto?
```
❌ ERRADO:
   C:\Users\CAMPIRA\documents\GitHub\...
   (qualquer outro lugar)

✅ CERTO:
   C:\Users\CAMPIRA\Documents\GitHub\meusite\assets\images\
   (EXACTAMENTE aqui!)
```

### Verificação 3: Recarregar Página
```
1. Abre o site no navegador
2. Carrega em Ctrl+F5 (força recarregar, limpa cache)
3. Se ainda não aparecer, verifica passos acima
```

---

## ✨ RESULTADO ESPERADO

Depois de adicionar as imagens corretamente, verás:

### Página Inicial (index.html)
```
🏢 Logo da empresa no topo (centrado)
```

### Página Serviços (services.html)
```
"GALERIA DE SERVIÇOS"
┌─────────────┬─────────────┐
│  Serviço 1  │  Serviço 2  │
├─────────────┼─────────────┤
│  Serviço 3  │  Serviço 4  │
└─────────────┴─────────────┘
(com efeito de hover - imagem cresce ao passar rato)
```

### Página Produtos (produtos.html)
```
"GALERIA DE PRODUTOS"
┌─────────────┬─────────────┐
│ Produto 1   │ Produto 2   │
├─────────────┼─────────────┤
│ Produto 3   │ Produto 4   │
└─────────────┴─────────────┘

"AUTOCOLANTES E CARTÕES"
┌─────────────┬─────────────┐
│ Adesivo 1   │ Cartão 1    │
├─────────────┼─────────────┤
│ Banner 1    │ Flyer 1     │
└─────────────┴─────────────┘
```

---

## 📞 RESUMO RÁPIDO

```
1. Tens imagens? → Renomeia conforme acima
2. Local? → C:\Users\CAMPIRA\Documents\GitHub\meusite\assets\images\
3. Copia? → Ctrl+C / Ctrl+V
4. Abre site? → Duplo-clique no HTML ou abre no navegador
5. Ctrl+F5? → Força recarregar sem cache
6. Pronto! ✅
```

---

**Dúvidas? Envia-me uma screenshot do Explorer mostrando:**
- A pasta onde estão tuas imagens agora
- Os nomes dos ficheiros que tens

Assim consigo ajudar melhor! 📸

