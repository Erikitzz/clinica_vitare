# Clínica Vitare

Landing page estática (HTML + CSS puro, sem frameworks e sem backend) desenvolvida
para apresentar uma clínica de saúde fictícia e seus principais serviços.

Projeto acadêmico de **Programação e Desenvolvimento Web**,
Projeto 01 (Landing Page Estática).

## ✅ Requisitos atendidos

| Requisito | Onde está |
|---|---|
| Título da aba | `<title>Clínica Vitare — Cuidado que acompanha você</title>` |
| Mínimo de 2 imagens de serviços | 4 ilustrações SVG na seção `#servicos` |
| Descrição dos serviços | Seção `#servicos`, um cartão por serviço |
| Equipe fictícia (mín. 3, com foto e cargo) | Seção `#equipe`, 4 integrantes com foto e cargo |
| Pelo menos 2 níveis de cabeçalho | `<h1>` no destaque, `<h2>` nas seções, `<h3>` nos cartões |
| Formulário estático (Nome, E-mail, Cidade, Estado) | Seção `#contato` e `action="#"` |

## ✨ Seções extras

- **Sobre nós** (`#sobre`) história fictícia da clínica e estatísticas de atuação
- **Depoimentos** (`#depoimentos`) 3 depoimentos de pacientes fictícios, com foto
- **Horários & Localização** (`#localizacao`) horário de funcionamento, endereço em Brasília/DF e mapa incorporado (Google Maps embed)
- **Dúvidas frequentes** (`#faq`) 5 perguntas em formato acordeão (`<details>/<summary>`, sem JavaScript)

## 🗂️ Estrutura do projeto

```
clinica-vitare/
├── index.html      # Estrutura da página
├── style.css        # Estilos (paleta, tipografia, layout responsivo)
└── README.md         # Este arquivo
```

## 🛠️ Tecnologias

- HTML5 semântico
- CSS3 (Grid, Flexbox, variáveis CSS, responsivo)
- Google Fonts (Fraunces, Inter, IBM Plex Mono)

## ⚠️ Observação

Os nomes da equipe, fotos (geradas via [pravatar.cc](https://pravatar.cc)) e dados da
clínica são fictícios, criados exclusivamente para fins acadêmicos. O formulário de
contato é estático e não envia nem armazena nenhum dado, conforme
exigido pelo enunciado.
