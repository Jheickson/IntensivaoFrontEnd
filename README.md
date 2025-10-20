# IntensivaoFrontEnd — JavaScript em Páginas HTML

Repositório para o código da apresentação do Intensivão da RioHacks sobre JavaScript em páginas HTML.

Este projeto é um material educativo interativo com exemplos práticos que mostram como JavaScript adiciona comportamento às páginas web. Ele foi desenvolvido para ser direto ao ponto e didático: todo o conteúdo principal está contido no arquivo `index.html`, que reúne estrutura (HTML), estilos (CSS) e scripts (JavaScript) usados na apresentação.

## Objetivo

- Servir como material de apoio para o Intensivão da RioHacks, workshops ou estudo individual.
- Mostrar conceitos essenciais de JavaScript aplicados diretamente em páginas HTML estáticas.
- Permitir que iniciantes editem o código e vejam resultados imediatos no navegador.

## Estrutura do repositório

- `index.html` — página única com todas as seções e exemplificações interativas.
- `README_FULL.md` — este arquivo com instruções e explicações (versão expandida).
- `README.md` — arquivo curto (preservado). Se quiser, posso sobrescrever `README.md` com o conteúdo desta versão.

> Observação: o projeto foi mantido em um único arquivo para reduzir atrito durante a apresentação. Para projetos reais, recomenda-se separar JS/CSS/HTML em arquivos distintos.

## Como executar localmente

1. Clone o repositório ou baixe os arquivos:

```bash
git clone https://github.com/Jheickson/IntensivaoFrontEnd.git
cd IntensivaoFrontEnd
```

2. Abra o arquivo `index.html` diretamente no navegador (duplo clique) ou use um servidor estático local para evitar restrições de CORS em alguns navegadores:

```bash
# Com Python 3 (porta 8000)
python3 -m http.server 8000
# então abra http://localhost:8000
```

Alternativa com npm (se preferir):

```bash
npm install -g serve
serve -s .
```

## O que tem em `index.html` (resumo das seções e demos)

- Introdução: o que é JavaScript e as formas de incluí-lo (inline, interno, externo).
- Variáveis: demonstração de `var`, `let` e `const`, e boas práticas de declaração.
- Tipos de Dados: visão geral de tipos primitivos, objetos e arrays, e dicas práticas.
- Operadores e Condicionais: exemplos de operadores aritméticos, comparação, lógicos e estruturas condicionais.
- Funções: exemplos de declaração, expressão e arrow functions; calculadora simples como demo.
- Eventos: manipulação de `click`, `input`, `mouseover` e `mouseout` com handlers.
- DOM: criação (`createElement`), inserção (`appendChild`), manipulação de classes e limpeza de nós.
- APIs e Fetch: consumo de API pública (JSONPlaceholder) com `fetch()` e tratamento básico de erros.

Cada demo possui duas partes visíveis: controles interativos (inputs/botões) e um bloco com o código usado — ideal para demonstrar a ligação entre código e comportamento.

## Boas práticas e sugestões de extensão

- Separe o CSS e JS em arquivos próprios (`styles.css`, `main.js`) para demonstrar organização de projetos.
- Converta o exemplo de `fetch` para `async/await` e explique a diferença de escrita/legibilidade.
- Substitua `innerHTML` por manipulação segura do DOM quando trabalhar com dados não confiáveis (para evitar XSS).
- Adicione um pequeno servidor de desenvolvimento (ex.: Vite) para mostrar fluxo moderno de desenvolvimento.

## Contribuições

Contribuições são bem-vindas. Faça fork, crie uma branch, teste localmente e abra um pull request com uma descrição clara das mudanças.
