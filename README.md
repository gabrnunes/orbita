# 🪐 Órbita

Plugin de Wordpress para criar um painel de debates baseado em links, similar ao Hacker News, para o [Manual do Usuário](https://manualdousuario.net).

## Rodar o projeto

Requisitos
- Node.js
- Grunt
- [Child theme do MdU](https://github.com/rghedin/ten-years)

Clone o repositório

```bash
git clone git@github.com:gabrnunes/orbita.git
```

Instale as dependências

```bash
cd orbita
npm install
```

Caso queira alterar o arquivo de estilo `main.scss`

```bash
grunt watch
```

Gerar arquivo `orbita.zip`

```bash
grunt compress
```

## Instalar o plugin

1. Faça login no seu admin do WordPress
2. Visite Plugins > Adicionar novo > Enviar plugin
3. "Escolher arquivo" e selecione o `orbita.zip`
4. Clique em "Instalar agora" e depois em "Ativar plugin"

## Contribuição

Você pode ajudar abrindo um pull request (verifique as issues abertas ou, se preferir, abra uma nova) ou reportando um bug.

Para manter o repositório padronizado:
- escreva as mensagens dos commits em português
- siga os [coding standards do WordPress](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/)