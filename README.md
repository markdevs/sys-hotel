### Sistema de Reservas de Hotel

Este é um sistema simples de reservas de hotel desenvolvido em Python. Ele permite que os usuários façam reservas de quartos de hotel para determinadas datas e exibam informações sobre as reservas feitas.

##Funcionalidades

Hóspede: Registre informações sobre os hóspedes, incluindo nome, número de telefone e e-mail.

Quarto: Adicione quartos ao sistema com número, capacidade máxima de hóspedes e preço por noite.

Reserva: Faça reservas associando um hóspede a um quarto para datas específicas de check-in e check-out. O sistema calculará automaticamente o valor total da reserva com base no preço do quarto e no número de noites.

Hotel: Adicione quartos ao inventário do hotel e faça reservas. O sistema verifica a disponibilidade dos quartos antes de confirmar a reserva.

### Como Usar

1.Adicionar Hóspede:

```
hospede = Hospede("Nome do Hóspede", "Número de Telefone", "Endereço de E-mail")

```

2.Adicionar Quarto

```
quarto = Quarto(numero, capacidade, preco_por_noite)
hotel.adicionar_quarto(quarto)

```
3.Fazer Reserva

```
from datetime import datetime

check_in = datetime(ano, mes, dia)  # Data de check-in
check_out = datetime(ano, mes, dia)  # Data de check-out

hotel.fazer_reserva(hospede, numero_quarto, check_in, check_out)


```
4.Exibir Informações da Reserva:

```
reserva = hotel.reservas[0]  # Acesso à primeira reserva feita
reserva.exibir_informacoes()

```

## Requisitos

Python 3.x

## Contribuição
Fique à vontade para contribuir para este projeto. Você pode abrir problemas (issues) para relatar bugs ou sugerir melhorias. Se desejar adicionar novos recursos, sinta-se à vontade para criar um fork deste repositório, adicionar suas alterações e enviar um pull request.

## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.