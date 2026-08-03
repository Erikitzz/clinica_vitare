# Clínica Vitare — Landing Page Estática

Landing page estática (HTML + CSS puro, sem frameworks e sem backend) desenvolvida
para apresentar uma clínica de saúde fictícia e seus principais serviços.

Projeto acadêmico — trabalho de **Desenvolvimento de Soluções para Clínica de Saúde**,
Projeto 01 (Landing Page Estática).

## ✅ Requisitos atendidos

| Requisito | Onde está |
|---|---|
| Título da aba | `<title>Clínica Vitare — Cuidado que acompanha você</title>` |
| Mínimo de 2 imagens de serviços | 4 ilustrações SVG na seção `#servicos` |
| Descrição dos serviços | Seção `#servicos`, um card por serviço |
| Equipe fictícia (mín. 3, com foto e cargo) | Seção `#equipe`, 4 integrantes com foto e cargo |
| Pelo menos 2 níveis de cabeçalho | `<h1>` no hero, `<h2>` nas seções, `<h3>` nos cards |
| Formulário estático (Nome, E-mail, Cidade, Estado) | Seção `#contato` — `action="#"`, sem processamento |

## 🗂️ Estrutura do projeto

```
clinica-vitare/
├── index.html      # Estrutura da página
├── style.css        # Estilos (paleta, tipografia, layout responsivo)
└── README.md         # Este arquivo
```

## ▶️ Como executar localmente

Não é necessário instalar nada — é uma página 100% estática.

**Opção 1 — abrir direto:**
Dê duplo clique em `index.html` (ou clique com o botão direito → *Abrir com* → navegador).

**Opção 2 — servidor local (recomendado, evita bloqueios de CORS/fontes):**
```bash
# dentro da pasta do projeto
python3 -m http.server 8080
# depois acesse http://localhost:8080 no navegador
```
ou, com Node.js instalado:
```bash
npx serve .
```

## ☁️ Publicação (GitHub Pages)

1. Crie um repositório no GitHub e envie os arquivos deste projeto:
   ```bash
   git init
   git add .
   git commit -m "Landing page - Clínica Vitare"
   git branch -M main
   git remote add origin https://github.com/<seu-usuario>/<seu-repo>.git
   git push -u origin main
   ```
2. No repositório, vá em **Settings → Pages**.
3. Em **Source**, selecione a branch `main` e a pasta `/root`.
4. Salve. Em alguns minutos o link ficará disponível em:
   `https://<seu-usuario>.github.io/<seu-repo>/`

## 🛠️ Tecnologias

- HTML5 semântico
- CSS3 (Grid, Flexbox, variáveis CSS, responsivo)
- Google Fonts (Fraunces, Inter, IBM Plex Mono)
- Sem dependências externas de build — nenhuma instalação necessária

## ⚠️ Observação

Os nomes da equipe, fotos (geradas via [pravatar.cc](https://pravatar.cc)) e dados da
clínica são fictícios, criados exclusivamente para fins acadêmicos. O formulário de
contato é estático (`action="#"`) e não envia nem armazena nenhum dado, conforme
exigido pelo enunciado.
