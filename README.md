# Guessing Game 

Um jogo simples de adivinhação construído com HTML, CSS e JavaScript puro (Vanilla JS), com feedback por voz usando a API do ResponsiveVoice.

## Sobre

O jogo sorteia um número secreto entre **1 e 100**. O jogador deve tentar adivinhar o número recebendo dicas a cada tentativa até acertar.

## Funcionalidades

- Geração de número aleatório sem repetição durante a mesma "rodada" de sorteios
- Contagem de tentativas
- Feedback textual e em áudio (voz em português) a cada chute
- Validação de entrada (impede chutes vazios ou fora do intervalo permitido)
- Botão "Novo jogo" para reiniciar, habilitado apenas após acertar
- Interface responsiva

## Tecnologias utilizadas

- HTML5
- CSS3 (Google Fonts: Chakra Petch e Inter)
- JavaScript (ES6+)
- [ResponsiveVoice.js](https://responsivevoice.org/) para síntese de voz

## Como rodar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repo.git
   cd nome-do-repo
   ```
2. Abra o arquivo `index.html` diretamente no navegador, ou sirva a pasta com uma extensão como **Live Server** (VS Code).

É um projeto 100% estático.

## Observação sobre o ResponsiveVoice

O script do ResponsiveVoice usado no projeto (`responsivevoice.org/js`) é a versão gratuita, que atualmente pode exigir uma chave de API (`?key=SUA_CHAVE`) dependendo do domínio de uso. Caso a voz pare de funcionar após o deploy, verifique a [documentação oficial](https://responsivevoice.org/api/) para gerar uma chave gratuita para o seu domínio do Vercel.

## Licença

Este projeto está sob a licença MIT. Sinta-se à vontade para usar e modificar.
