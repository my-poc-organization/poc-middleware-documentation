# Barramento de Patins

Este barramento de patins é uma plataforma para gerenciar a disponibilidade e reserva de patins. Ele inclui várias APIs que permitem aos usuários verificar a disponibilidade de patins, reservar e cancelar reservas de patins, bem como alterar as reservas existentes.

## APIs disponíveis

- `GET /patins` - lista todos os patins disponíveis para reserva.
- `GET /patins/{id}` - exibe detalhes de um patin específico.
- `POST /reservas` - cria uma nova reserva de patins.
- `GET /reservas` - lista todas as reservas existentes.
- `GET /reservas/{id}` - exibe detalhes de uma reserva específica.
- `PUT /reservas/{id}` - atualiza uma reserva existente.
- `DELETE /reservas/{id}` - cancela uma reserva existente.

## Como executar o barramento

Para executar este barramento em sua máquina local, siga as etapas abaixo:

1. Certifique-se de que você tenha o .NET Core SDK instalado em sua máquina.
2. Clone este repositório em sua máquina local.
3. Abra um terminal na pasta raiz do projeto e execute o comando `dotnet run`.
4. As APIs agora podem ser acessadas em `http://localhost:5000`.

## Como usar as APIs

Para usar as APIs disponíveis, você pode enviar solicitações HTTP para as URLs listadas acima. Você pode usar ferramentas como Postman ou curl para testar as APIs. Certifique-se de incluir os cabeçalhos apropriados e os dados necessários no corpo da solicitação. Consulte a documentação completa da API para obter mais detalhes.

## Considerações finais

Este barramento de patins foi desenvolvido em .NET Core para ajudar no gerenciamento de patins disponíveis e reservas de patins. As APIs fornecidas são apenas um exemplo de como essa funcionalidade pode ser implementada. Sinta-se à vontade para modificá-las ou estendê-las de acordo com suas necessidades.
