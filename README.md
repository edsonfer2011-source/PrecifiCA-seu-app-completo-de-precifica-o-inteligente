[README.md](https://github.com/user-attachments/files/27104765/README.md)
# PrecifiCA — Precificador Inteligente com IA

> Descubra o preço certo para o seu produto ou serviço — com dados reais do mercado, análise por inteligência artificial e exportação em PDF e Excel.

---

## 🎯 Sobre o Projeto

O **PrecifiCA** é uma ferramenta web criada para empreendedores, autônomos e pequenos negócios que precisam precificar seus produtos ou serviços com segurança — mesmo sem ter conhecimento técnico em finanças.

A ferramenta guia o usuário em 4 passos simples, pesquisa preços reais praticados no mercado brasileiro em tempo real e entrega uma análise completa com o preço viável, composição de custos e dicas práticas personalizadas.

**🔒 Privacidade total:** nenhuma informação inserida é enviada ou salva em servidores. Tudo permanece no navegador do usuário.

---

## ✨ Funcionalidades

- **Guia passo a passo** acessível para qualquer pessoa, sem jargão técnico
- **Pesquisa de mercado ao vivo** — a IA busca preços reais na internet (iFood, Mercado Livre, OLX, Instagram e outros)
- **Comparativo visual com concorrentes** — barras comparativas com posicionamento de mercado
- **3 faixas de preço:** mínimo (sem prejuízo), recomendado (com margem) e premium (teto do mercado)
- **Composição do preço detalhada** — custos diretos, mão de obra, fixos, taxas e lucro
- **Análise completa em linguagem simples** escrita diretamente para o empreendedor
- **Exportação em PDF** — relatório profissional formatado, pronto para compartilhar
- **Exportação em Excel** — planilha com 4 abas: Resumo, Composição, Comparativo e Dados
- **Suporte a 4 categorias:** produto físico, serviço, produto digital e alimentação/gastronomia

---

## 🖥️ Demonstração

🔗 **[Acessar o PrecifiCA ao vivo](https://seu-usuario.github.io/precifica)**

> Substitua o link acima pelo seu link do GitHub Pages após publicar.

---

## 🚀 Como Usar

1. Acesse o link do projeto
2. Insira sua chave de API da Anthropic *(gratuita em [console.anthropic.com](https://console.anthropic.com/settings/keys))*
3. Preencha os 4 passos com as informações do seu produto ou serviço
4. Clique em **"Calcular meu preço ideal"**
5. Aguarde a pesquisa de mercado e análise (aproximadamente 15–20 segundos)
6. Baixe o resultado em **PDF** ou **Excel**

---

## 🗂️ Estrutura dos Resultados

Após a análise, o relatório inclui:

| Seção | Descrição |
|---|---|
| Veredicto | Viável ✅ / Atenção ⚠️ / Revisar ❌ |
| Comparativo de mercado | Concorrentes reais pesquisados na internet |
| Faixa de preço | Mínimo, Recomendado e Premium |
| Composição do preço | Breakdown de todos os custos |
| Análise completa | Explicação em linguagem simples |
| Dicas práticas | 4 sugestões personalizadas para o negócio |

---

## 🔑 Requisitos

- Navegador moderno (Chrome, Firefox, Edge, Safari)
- Chave de API da Anthropic (plano gratuito disponível)
- Conexão com a internet (para pesquisa de mercado em tempo real)

> A chave de API é salva apenas no seu navegador local (`localStorage`). Ela nunca trafega por servidores de terceiros.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Função |
|---|---|
| HTML5 + CSS3 | Interface e layout responsivo |
| JavaScript (Vanilla) | Lógica do aplicativo |
| [Claude API (Anthropic)](https://www.anthropic.com) | Pesquisa de mercado e cálculo de precificação |
| [SheetJS (xlsx)](https://sheetjs.com) | Geração de planilhas Excel no navegador |
| [jsPDF](https://parall.ax/products/jspdf) + [AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) | Geração de PDF no navegador |
| Google Fonts | Tipografia (Playfair Display + Jost) |

---

## 📁 Estrutura do Projeto

```
precifica/
└── index.html     # Aplicativo completo em arquivo único
```

O projeto foi intencionalmente construído como um **arquivo HTML único**, sem dependências locais, sem build tools e sem backend — basta hospedar o `index.html` e está funcionando.

---

## 📦 Como Publicar no GitHub Pages

1. Crie um repositório público chamado `precifica`
2. Faça o upload do arquivo `index.html` (renomeie o arquivo para `index.html` antes)
3. Vá em **Settings → Pages**
4. Em **Source**, selecione `Deploy from a branch` → branch `main` → pasta `/ (root)`
5. Clique em **Save**
6. Aguarde 1–2 minutos e acesse: `https://seu-usuario.github.io/precifica`

---

## 💡 Categorias Suportadas

- 🛍️ **Produto físico** — artesanato, roupas, cosméticos, eletrônicos, etc.
- ✂️ **Serviço** — corte de cabelo, aulas, consultoria, manutenção, etc.
- 💻 **Produto digital** — cursos online, e-books, templates, software, etc.
- 🍰 **Alimentação / Gastronomia** — marmitas, bolos, doces, lanches, etc.

---

## 🤝 Contribuições

Este projeto foi criado com auxílio de Inteligência Artificial como parte de um portfólio pessoal. Sugestões, melhorias e feedbacks são bem-vindos — abra uma **Issue** ou envie um **Pull Request**.

---

## 📄 Licença

Este projeto está sob a licença [MIT](https://opensource.org/licenses/MIT). Sinta-se livre para usar, modificar e distribuir.

---

## 👤 Autor

Desenvolvido com IA por **[Edson Ferreira da Silva - edsonfer2011-source]**

[![GitHub](https://github.com/edsonfer2011-source/PrecifiCA-seu-app-completo-de-precifica-o-inteligente/new/main?filename=README.md)

---

<p align="center">
  Feito com 🤖 <a href="https://claude.ai">Claude AI</a> · Anthropic
</p>
