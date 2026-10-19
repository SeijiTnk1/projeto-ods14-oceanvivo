# 🌊 OceanVivo — ODS 14: Vida na Água

Projeto 1 (HTML e CSS) da disciplina **Programação Web Front-End (2026_02)**, da **UTFPR — Cornélio Procópio**.

🔗 **Página publicada:** (https://github.com/SeijiTnk1/projeto-ods14-oceanvivo.git)
🎥 **Vídeo de apresentação:** COLE-AQUI-O-LINK-DO-VIDEO

---

## 📖 Descrição do projeto

O **OceanVivo** é um website de conscientização ambiental alinhado ao **Objetivo de Desenvolvimento Sustentável 14 da ONU — Vida na Água**, que busca conservar e usar de forma sustentável os oceanos, mares e recursos marinhos.

O site apresenta informações sobre o ODS 14, as principais ameaças aos oceanos (poluição por plástico, aquecimento global, sobrepesca e acidificação), uma galeria de imagens dos ecossistemas marinhos e links de organizações e materiais oficiais. Também possui páginas de login e cadastro para quem deseja participar da iniciativa.

**Objetivo do serviço:** informar e engajar as pessoas na proteção dos oceanos.

**Público-alvo:** estudantes, jovens e a comunidade em geral interessados em causas ambientais.

**ODS atendido:** ODS 14 — Vida na Água.

---

## 🗂️ Estrutura do projeto

```
/
├── index.html          # Página principal (sobre, ameaças, galeria, recursos e equipe)
├── login.html          # Página de login (e-mail e senha) → leva à página principal
├── cadastro.html       # Página de cadastro (6 campos) → leva ao login
├── style.css           # Estilos compartilhados por todas as páginas
├── img/                # Imagens do site
│   ├── img-01.webp ... img-06.webp
│   └── un-logo.svg
├── curriculos/         # Currículos dos integrantes (um por pasta)
│   └── cv_tnk/
│       ├── index.html
│       ├── estilo.css
│       └── imagens/
├── prints/             # Prints da validação do W3C (HTML e CSS)
└── README.md           # Documentação do projeto
```

### Fluxo de navegação

`login.html` → (Entrar) → `index.html`
`login.html` → (Cadastre-se) → `cadastro.html` → (Criar conta) → `login.html`

O link para os currículos de cada integrante está no rodapé das páginas.

---

## 🧩 O que a página principal contém

- Cabeçalho, menu de navegação e rodapé
- Ícones (Material Icons Outlined)
- Caixas de texto (`p`, `span`, `li`) e cards informativos
- Galeria com imagens locais da pasta `img/`
- Links externos (ONU, ONU Brasil e Oceana)
- Fontes: **Roboto** (fonte externa, Google Fonts) e **Arial**
- Paleta de cores em tons de azul
- Tags semânticas: `header`, `nav`, `main`, `section` e `footer`
- Link para o currículo de cada integrante no rodapé

---

## ✅ Validação do código

O código foi validado nos validadores do W3C. Os prints estão na pasta [`prints/`](prints/).

- HTML: https://validator.w3.org/
- CSS: https://jigsaw.w3.org/css-validator/

---

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- Google Fonts (Roboto)
- Google Material Icons
- GitHub Pages (publicação)

Nenhum framework foi utilizado.

---

## 👥 Integrantes da equipe

| Nome | Currículo |
|------|-----------|
| Gustavo Seiji Tanaka | [Currículo](curriculos/cv_tnk/index.html) |
| Gabriel Sasaki Roncaglia | [Currículo](curriculos/cv_GabrielSasaki/index.html) |
| Rafael Romanelo | [Currículo](curriculos/cv_RafaelRomanelo/index.html) |

---

## 🚀 Como executar

1. Clone o repositório:
   ```
   git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
   ```
2. Abra o arquivo `login.html` ou `index.html` em qualquer navegador.

---

## 📌 Próximas etapas

No **Projeto 2** serão implementadas funcionalidades em **JavaScript**, como validação dos formulários e login e cadastro funcionais.
