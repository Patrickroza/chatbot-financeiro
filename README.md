# chatbot-financeiro<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chatbot Financeiro</title>
    <script src="https://seu-usuario.github.io/chatbot-financeiro/script.js"></script>
    <style>
        #user-input, #stock-symbol {
            width: calc(100% - 100px);
        }

        button {
            width: 80px;
        }

        #messages {
            height: 300px;
            overflow-y: scroll;
            border: 1px solid #ccc;
            padding: 10px;
            margin-bottom: 10px;
        }

        #stock-price {
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div id="chatbox">
        <div id="messages"></div>
        <input type="text" id="user-input" placeholder="Digite sua mensagem...">
        <button onclick="sendMessage()">Enviar</button>
    </div>
    <div id="stockbox">
        <input type="text" id="stock-symbol" placeholder="Digite o símbolo da ação...">
        <button onclick="getStockPrice()">Consultar</button>
        <div id="stock-price"></div>
    </div>
    >veltrix</a>
</body>
</html>
