# Launcher de Minecraft Personalizado

Um launcher de Minecraft com interface gráfica estilosa, animações suaves, botões com bordas arredondadas e slideshow com efeito blur. Este launcher é totalmente funcional e capaz de iniciar o jogo Minecraft.

## Características

- Interface moderna com animações suaves
- Botões com bordas arredondadas
- Slideshow com efeito blur
- Sistema completo de autenticação Microsoft
- Integração com Forge para mods
- Detecção e instalação automática do Java
- Sistema de lançamento do jogo funcional

## Requisitos

- Node.js (versão 14 ou superior)
- npm (versão 6 ou superior)
- Electron (instalado automaticamente via npm)

## Instalação

1. Clone ou extraia este repositório
2. Abra um terminal na pasta do projeto
3. Execute o comando para instalar as dependências:

```bash
npm install
```

4. Inicie o launcher:

```bash
npm start
```

## Uso

1. Faça login com sua conta Microsoft
2. Selecione a versão do Minecraft desejada
3. Opcionalmente, selecione uma versão do Forge para jogar com mods
4. Ajuste a memória alocada conforme necessário
5. Clique no botão "JOGAR" para iniciar o jogo

## Personalização

Você pode personalizar a aparência do launcher editando os arquivos:

- `app/assets/css/style.css` - Estilos e animações
- `app/assets/js/renderer.js` - Imagens do slideshow e comportamentos

## Estrutura do Projeto

- `app/` - Arquivos da interface do usuário
  - `assets/` - Recursos (CSS, JavaScript, imagens)
  - `index.html` - Estrutura HTML principal
- `index.js` - Arquivo principal do Electron
- `package.json` - Configurações do projeto

## Solução de Problemas

Se você encontrar problemas ao iniciar o launcher:

1. Verifique se todas as dependências foram instaladas corretamente
2. Certifique-se de que o Java está instalado em seu sistema (o launcher tentará instalar automaticamente se necessário)
3. Verifique se você tem uma conexão ativa com a internet para autenticação e download de arquivos

## Créditos

Este launcher foi desenvolvido com base nas seguintes tecnologias:

- Electron
- Node.js
- minecraft-launcher-core (MCLC)
- electron-store
