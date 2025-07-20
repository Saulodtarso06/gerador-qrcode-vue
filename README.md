# Gerador de QR Code

Um projeto simples de Gerador de QR Codes utilizando HTML, CSS, JavaScript e a biblioteca [QRious](https://github.com/neocotic/qrious).

## Funcionalidades

- Geração de QR Code em tempo real apartir de um link
- Entrada personalizada de texto ou URL
- A imagem gerada do qrcode pode ser salva em formato png.
- Responsivo e leve

## Tecnologias

- HTML
- CSS
- JavaScript (Vanilla)
- [QRious v4.0.2](https://github.com/neocotic/qrious)


## Captura da tela

<div align="left">
      <img src="https://github.com/user-attachments/assets/b3869775-0c9e-4100-a32f-364bd54dca30" width="350px"/> 
</div>

## Como rodar o projeto

1. Clone o repositório:
   ```
   git clone https://github.com/Saulodtarso06/gerador-qrcode-vue.git
   ```
### Pré-requisitos
Obs: Os navegadores de internet devem estar atualizados.

Abri o projeto com o Editor de texto VS Code (**de preferência**)

### Passos para rodar
Clone o repositório, (Prompt de comando, PowerShell, Git Bash) e execute:

```
git clone <URL-do-repositório>
```
Substitua <URL-do-repositório> pelo link do seu repositório no GitHub.

Navegue até a pasta do projeto

```
cd nome-da-pasta-do-projeto
```
Abra o arquivo HTML no navegador

Você pode abrir diretamente o arquivo index.html:

No explorador de arquivos do seu sistema, dê um duplo clique no arquivo index.html

Ou abra o navegador e arraste o arquivo para dentro da janela

Ou abra pelo terminal com comando (exemplo no Windows):
```
open index.html
```
Abra o terminal e execute o comando abaixo:
```
npm i
```
para instalar todas as dependências listadas no arquivo package.json.

```
npm run
```
lista todos os script disponiveis para execução.

```
npm run qrcode
```
executar o script qrcode que contem todas as instruções e dependencia do node para rodar o servidor e a pagine web do projeto.
```
Available on:
  http://192.168.0.205:8080 --> segure a tecla (Ctrl + click) para acessar a pagina do servidor
```
Para encerrar o servidor, basta dar o comando **Ctrl + C** dentro do terminal.