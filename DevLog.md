# Desenvolvimento-Web-Atividade-1
Repositório destinado ao armazenamento da primeira atividade referente a cadeira de desenvolvimento web, com objetivo de praticar os conceitos básicos de HTML na disciplina de Desenvolvimento Web.
**Aluno**: Ednilson da Silva Silvério
**Professor:** Silas Santiago
**Título do Projeto:** Top 10 Forças Especiais Brasileiras

## Descrição do Projeto

Site desenvolvido com HTML5, CSS3 e será implementado Vite (Vanilla JS), apresentando um ranking com as 10 principais forças especiais brasileiras. Para cada unidade, o site traz uma imagem, descrição, curiosidades e um mapa de localização da sede via iframe do Google Maps.

O projeto conta com três páginas:

- **index.html** — Página inicial, com introdução, vídeo de destaque e o ranking das 10 forças especiais.
- **about.html** — Página "Sobre", com informações do projeto e do desenvolvedor.
- **contact.html** — Página de contato, com formulário para envio de dúvidas, sugestões e opiniões sobre o site.

## Como rodar o projeto localmente quando o VITE for implementado

Pré-requisito: ter o Node.js instalado.

execute os comandos
# 1. Clone o repositório
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git

# 2. Entre na pasta do projeto
cd Desenvolvimento-Web-Atividade-1

# 3. Instale as dependências
npm install

# 4. Rode o servidor de desenvolvimento
npm run dev

O terminal vai mostrar um endereço local, exemplo: `http://localhost:5173` — abra no navegador para visualizar o site.

## Checklist dos Recursos HTML Implementados

| # | Recurso | Implementado em | Status |
|---|---|---|---|
| 1 | Estrutura semântica (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`) | `index.html`, `about.html`, `contact.html` | ✅ |
| 2 | Meta tags (`viewport`, `description`, `icon`) | Todas as páginas | ✅ |
| 3 | Tags de mídia: `picture`, `source`, `img`, `iframe` | `index.html` (banner, cards, mapas) | ✅ |
| 4 | Tag `video` | `index.html` (seção do vídeo) | ✅ |
| 4 | `details` e `summary` | `index.html` (cards do ranking) | ✅ |
| 5 | Favicon alterado | Todas as páginas (`imagens/*.ico`) | ✅ |
| 6 | `strong` | Todas as páginas | ✅ |
| 6 | `b`, `i`, `em`, `mark`, `small`, `del`, `ins`, `sub`, `sup` | `index.html` | ✅ |
| 7 | Uso de `details` para organizar conteúdo | `index.html` | ✅ |
| 8 | Imagens responsivas (`picture` + `source`) | `index.html` (banner) | ✅ |
| 9 | `meta name="viewport"` | Todas as páginas | ✅ |
| 10 | `img` (com `width`/`height`), `a`, `h1`–`h6`, `p`, `br`, `ul`/`li` | Todas as páginas | ✅ |
| 11 | Inputs: `email`, `tel` com pattern, `date`, `number`, `range`, `radio`, `checkbox` | `contact.html` | ✅ |
| 12 | `video` para exibir conteúdo em vídeo | `index.html` | ✅ |
| 13 | `alt`, `loading` | Todas as páginas | ✅ |

# Diário de Desenvolvimento:

# Dia 1:
1 - Commit do HTML com sua estrutura Básica para início do projeto.
2 - Estruturação do projeto de acordo com o documento de requisitor enviado no ClassRoom.
3 - Adição de um Fivicon de acordo com o tema.
4 - Adição de um Banner gerado por IA com as forças especiais das quais pretendo abordar.
5 - Adição de uma section de introdução.
6 - Criação do primeiro Card do BOPE que será usado como modelo para os demais.

# Dia 2:
1 - Criação do segundo Card do COMANF com base no Card base
2 - Criação do tercerio Card do COpEsp com base no Card base
3 - Criação do quarto Card do GRUMEC com base no Card base

# Dia 3:
1 - Criação do quinto Card do COT com base no Card base
2 - Criação do sexto Card do CORE com base no Card base
3 - Criação do sétimo Card do GATE com base no Card base
4 - Criação do oitavo Card do CIOPAER com base no Card base
5 - Criação do nono Card do BPCHOQUE com base no Card base
6 - Criação do décimo Card do COE com base no Card base
7 - Criação de um .CSS básico para melhorar a visibilidade do site
8 - Implementação do about.html utilizando a estrutura básica do index e aproveitando o css sem adicionar novas propriedades
9 - Implementação do contatct.html utilizando a estrutura de header e footer do index
10 - Criação dos campos dos formulários utilizando diferentes estratégias de preenchimento e adicionando botões.
11 - Complementação do css para tornar o contact.html mais bonito visualmente utilizando propriedades nos campos e botões
12 - Adição de um vídeo ao index.html
13 - Estilização do vídeo
14 - Ajuste na imagem do desenvolvedor no about.html
15 - Fim