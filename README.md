# Portal de Entretenimento Digital

## Nome do Aluno(a)
Georgia Salma Hayatt da Silva Santos

## Descrição do Portfólio
Portal web desenvolvido para a atividade acadêmica do curso técnico, estruturado para apresentar conteúdos de entretenimento divididos em três áreas principais: Filmes e Séries, Música e Podcasts, e Games e Tecnologia.

## Tecnologias Utilizadas
- **HTML5**: Estruturação semântica com tags como `<div>`, `<h1>`, `<h2>`, `<p>` e `<img>`.
- **CSS3**: Aplicação combinada de estilos Inline, Interno e Externo, além de classes, IDs e Flexbox.
- **CSS Reset**: Baseado no modelo de Eric Meyer para normalização de margens e preenchimentos entre navegadores.
- **GitHub Pages**: Hospedagem e publicação do site.

## Link do Site Publicado
[https://georgiasalmahayatt-max.github.io/portal-entretenimento/](https://georgiasalmahayatt-max.github.io/portal-entretenimento/)

## Explicação do Funcionamento do Projeto
O portal foi estruturado utilizando HTML semântico e organizado visualmente com o modelo **Flexbox**. O container principal emprega `display: flex` e `flex-direction: row` para alinhar as três seções lado a lado de forma fluida. Cada seção conta com títulos padronizados, textos explicativos e imagens ilustrativas acompanhadas de suas respectivas legendas de fonte.

## Descrição do Recurso Novo Adicionado
Implementação de um sistema estruturado de **CSS modular e Redirecionamento de Páginas**, combinando a exigência de nomenclatura acadêmica (`portal.html`) com a compatibilidade automática do ambiente de hospedagem web (`index.html`).

## Explicação de Como Esse Recurso Foi Implementado
- **CSS Reset e Externo:** O arquivo `reset.css` é carregado prioritariamente no `<head>` do documento, seguido pela folha de estilo principal `estilo.css`, garantindo consistência visual.
- **Redirecionamento para GitHub Pages:** Como a regra da atividade exige o arquivo principal nomeado como `portal.html`, foi inserido um arquivo `index.html` na raiz contendo a meta tag de redirecionamento (`<meta http-equiv="refresh" content="0; url=portal.html">`), permitindo que o site abra automaticamente no link público sem alterar a estrutura exigida pelo professor.