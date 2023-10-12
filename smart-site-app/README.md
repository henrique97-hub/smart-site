# SmartSite -

https://github.com/bioritmo/front-end-code-challenge-smartsite

## Configuração de fontes:

- assets/fonts/Gotham -> arquivos de fonte
- styles.scss -> configuração dessas fontes para serem utilizadas em toda a aplicação.
  @font-face -> declaração do nome da variavel que conterá a fonte e suas caracteristicas.
- As cores padrões que usaremos no projeto, serão declaradas em forma de variavel
  :root {
  --dark-grey: #333333;
  --light-grey: #808080;
  --yellow: #FFB612;
  --red: #dc0a17;
  --green: #2FC022;
  }
  -> para utiliza-las, basta:
  .classe {
  color: var(--green);
  }
