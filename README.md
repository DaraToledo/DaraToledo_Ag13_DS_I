# 🎬 Meu Portal de Entretenimento Digital
### Agenda 13 – CSS: Cascading Style Sheets
**Curso Técnico em Desenvolvimento de Sistemas | ETEC**

---

## 📋 Sobre o Projeto

Página web temática desenvolvida como atividade da **Agenda 13** do Curso Técnico em Desenvolvimento de Sistemas (modalidade EaD – Centro Paula Souza).

O projeto consiste em um portal de entretenimento digital dividido em três seções principais, aplicando os conceitos de **HTML5** e **CSS** estudados na agenda.

---

## 🗂️ Estrutura de Arquivos

```
DaraToledo_Ag13_DS_I/
├── img/
│   ├── filme.png
│   ├── hysteria.png
│   ├── cds.png
│   ├── podcast.png
│   ├── gamer.png
│   └── tech.png
├── portal.html
├── estilo.css
└── reset.css
```

---

## 📑 Seções do Portal

| Seção | Conteúdo |
|---|---|
| 🎬 Filmes e Séries | Destaques de filmes e séries como Hysteria |
| 🎵 Música e Podcasts | Álbuns, playlists e podcasts em destaque |
| 🎮 Games e Tecnologia | Jogos, gadgets e novidades tecnológicas |

---

## ✅ Requisitos Técnicos Aplicados

### Três formas de CSS
- **Inline** → aplicado diretamente na `<div id="musica">` via atributo `style`
- **Interno** → bloco `<style>` no `<head>` estilizando o `#cabecalho`
- **Externo** → arquivo `estilo.css` linkado ao HTML

### Seletores e Organização
- **Classes** → `.secao`, `.titulo-secao`, `.legenda`, `.descricao`
- **IDs** → `#cabecalho`, `#filmes`, `#musica`, `#games`, `#rodape`
- **Agrupamento de seletores** → `#filmes, #musica, #games { ... }`
- **Comentários no CSS** → blocos explicativos ao longo do `estilo.css`

### Layout
- **Flexbox** → `.container` com `display: flex` e `flex-grow: 1` nas seções, organizando as três colunas lado a lado de forma responsiva

### Reset CSS
- Arquivo `reset.css` baseado no modelo de **Eric Meyer** ([meyerweb.com](https://meyerweb.com/eric/tools/css/reset/)), linkado antes da folha de estilo principal para remover formatações padrão do navegador

---

## 🛠️ Tecnologias Utilizadas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

---

## 💡 Competências Desenvolvidas

- Implementar páginas para a Internet utilizando recursos de estilização em CSS
- Desenvolver páginas web utilizando linguagem de marcação de texto (HTML)
- Construir folhas de estilo aplicando sintaxe, seletores e propriedades CSS

---

## 👩‍💻 Autora

**Dara Toledo**
Curso Técnico em Desenvolvimento de Sistemas – ETEC
Atividade: `DaraToledo_Ag13_DS_I`
