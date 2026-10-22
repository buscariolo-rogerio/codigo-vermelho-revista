# Código Vermelho

Revista digital sobre inteligência artificial, trabalho e direitos no Brasil. A 1ª edição, **“Trabalho descartável: até quando vamos fingir que isso é progresso?”**, é apresentada em 15 páginas com leitura por rolagem vertical.

## Nesta edição

- **Editorial:** apresenta o tema e a posição da revista.
- **Contextualização:** discute trabalho cristalizado, trabalho fantasma e o impacto da automação sobre profissionais qualificados.
- **Reportagem:** acompanha o efeito da vigilância e dos cortes por IA em uma equipe de tecnologia.
- **Direito em Xeque:** aborda a proteção constitucional, a LGPD e os direitos trabalhistas diante de decisões automatizadas.
- **O Labirinto do Subemprego:** examina a informalidade e o trabalho por plataformas.
- **Proposta de Intervenção:** reúne medidas de proteção, fiscalização e requalificação.
- **Expediente e Integrantes** e **Referências Bibliográficas** encerram a edição.

## Como abrir

Acesse o [site da revista](https://buscariolo-rogerio.github.io/codigo-vermelho-revista/) ou abra `index.html` no navegador. O projeto é estático e não precisa de instalação ou etapa de compilação.

Os oito gráficos são elementos HTML interativos: passe o mouse ou use Tab para consultar os valores; nos gráficos circulares, selecione uma categoria para destacá-la. Dados e fontes aparecem na própria página.

## Estrutura

```text
index.html        Página inicial e conteúdo da revista
dist/styles.css   Estilos e diagramação
dist/charts.js    Dados e interação dos gráficos
dist/assets/     Fotografias e logotipos usados nas páginas
```

Para publicar pelo GitHub Pages, mantenha essa estrutura no repositório e selecione **Deploy from a branch**, branch `main`, pasta **/(root)** em *Settings → Pages*. [Instruções do GitHub](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

Os títulos usam Stardos Stencil. O texto usa Lufga quando disponível e Outfit como alternativa. Os créditos da equipe estão na página 14 da revista.
