# Projeto Sorteador

## Visão Geral
Este projeto implementa um sorteador de números aleatórios usando tecnologias web modernas e práticas de desenvolvimento front-end.

## Tecnologias Utilizadas

### Linguagens
- HTML5
- CSS3 (via LESS)
- JavaScript (ES6+)

### Pré-processadores
- LESS: Para uma estilização mais eficiente e manutenível

### Automação e Build
- Grunt: Task runner para automatizar processos de desenvolvimento
  - grunt-contrib-less: Compilação de arquivos LESS para CSS
  - grunt-replace: Substituição de strings em arquivos
  - grunt-contrib-htmlmin: Minificação de arquivos HTML
  - grunt-contrib-watch: Observação de mudanças em arquivos
  - grunt-contrib-clean: Limpeza de diretórios
  - grunt-contrib-uglify: Minificação e ofuscação de JavaScript

### Gerenciamento de Dependências
- npm: Gerenciador de pacotes do Node.js

### Estrutura do Projeto
- src/: Diretório fonte
- dev/: Ambiente de desenvolvimento
- dist/: Distribuição final (minificada e otimizada)

## Funcionalidades
- Geração de números aleatórios baseada em um valor máximo definido pelo usuário
- Interface responsiva e amigável
- Exibição dinâmica do resultado do sorteio

## Como Executar
1. Clone o repositório
2. Instale as dependências com `npm install`
3. Execute `npm run grunt` para iniciar o ambiente de desenvolvimento
4. Para build de produção, execute `npm run build`

Este projeto demonstra a aplicação prática de conceitos modernos de desenvolvimento web, incluindo automação de tarefas, pré-processamento de CSS e otimização para produção.
