# 🎱 Bingo — Sorteador Digital

Plataforma de sorteio de bingo 100% estática, sem servidor, sem banco de dados, sem custo.  
Funciona direto no navegador com persistência via `localStorage`.

---

## 🚀 Deploy no GitHub Pages (5 minutos)

### Opção 1 — Upload direto pelo site (mais fácil)

1. Acesse [github.com](https://github.com) e faça login
2. Clique em **New repository**
3. Nomeie como `bingo` (ou qualquer nome)
4. Marque **Public** e clique em **Create repository**
5. Clique em **uploading an existing file**
6. Arraste o arquivo `index.html` para a área de upload
7. Clique em **Commit changes**
8. Vá em **Settings → Pages**
9. Em "Source", selecione **Deploy from a branch → main → / (root)**
10. Clique em **Save**

Aguarde 1-2 minutos. Seu sorteador estará em:  
`https://SEU_USUARIO.github.io/bingo/`

---

### Opção 2 — Via Git (linha de comando)

```bash
# Clone ou entre na pasta do projeto
git init
git add index.html
git commit -m "feat: sorteador de bingo"

# Crie o repositório no GitHub e conecte
git remote add origin https://github.com/SEU_USUARIO/bingo.git
git push -u origin main

# Ative o GitHub Pages nas configurações do repositório
# Settings → Pages → Deploy from branch → main / root
```

---

## 🎮 Como usar

1. Acesse a URL do seu GitHub Pages
2. Configure o **número mínimo** e **número máximo** (padrão: 1 a 75)
3. Clique em **Sortear número** — ou pressione `Espaço`
4. O número sorteado aparece em destaque; a grade vai marcando os já chamados
5. O jogo é salvo automaticamente — se fechar o navegador, ao voltar tudo estará lá
6. Clique em **Novo Jogo** para reiniciar (com confirmação)

---

## ✨ Recursos

- Sorteio aleatório sem repetição
- Configuração de faixa de números (1 a 9999)
- Grade visual de todos os números com status de cada um
- Número atual em destaque com animação
- Persistência automática no localStorage (sobrevive ao fechar/reabrir)
- Restauração do jogo ao voltar ao site
- Interface totalmente responsiva (celular, tablet, desktop)
- Tecla de atalho: `Espaço` para sortear
- Animações suaves e feedback visual em cada ação

---

## 🛠 Tecnologias

- HTML5 + CSS3 + JavaScript (Vanilla)
- Zero dependências externas (exceto Google Fonts)
- Zero servidor necessário
- Zero custo

---

## 📋 Requisitos mínimos do navegador

Qualquer navegador moderno: Chrome, Firefox, Safari, Edge (versões dos últimos 3 anos).
