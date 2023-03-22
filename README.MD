# Mock JSON Grande

## Este repo é uma api express simples que retorna um json grande, que resulta em uma requisição de aproximadamente 8.7MB, na rota /

Basta rodar npm i, npm start e utilizar um programa como o ngrok para gerar uma url disponível na internet.

A porta padrão que esta api express roda é 3000.

Baixar o ngrok: https://ngrok.com/.

Rodar o comando de configuração de token: "ngrok config add-authtoken [token]".

Comando básico: "ngrok http 3000".

Após isso esta api já está visível globalmente na internet.