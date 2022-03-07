1) Desenvolva o diagrama de casos de uso para os cenários abaixo. Além do diagrama, você deve apresentar uma breve descrição sobre os ATORES e os CASOS DE USOS que compõem o diagrama.

a) CINEMA
* Um cinema pode ter muitas salas, sendo necessário, portanto, registrar informações a respeito de cada uma, como sua capacidade, ou seja, o número de assentos disponíveis
* O cinema apresenta muitos filmes. Um filme tem informações como título e duração. Assim, sempre que um filme for apresentado, deve-se registrá-lo também.
* Um mesmo filme pode ser representado em diferentes salas e horários diferentes. Cada apresentação em uma determinada sala e horário é chamada de Sessão. Um filme sendo apresentado em uma sessão tem um conjunto máximo de ingressos, determinado pela capacidade de sala.
* Os clientes do cinema podem comprar ou não ingressos para assistir uma sessão. O funcionário deve intermediar a compra do ingresso. Um ingresso deve conter informações como o tipo de ingresso (meia entrada ou entrada inteira). Além disso, um cliente só pode comprar ingressos para sessões ainda não encerradas.


![Cinema_Doc](https://github.com/iuryeng/APS/blob/main/Atividade%2005/Cinema/doc_user_case_cinema.png)

![Cinema_Diagrama](https://github.com/iuryeng/APS/blob/main/Atividade%2005/Cinema/User%20Case%20Cinema.jpg)


**Descrição dos Casos de Uso**

|N° |Caso de Uso |Descrição|Ator|
|:-----:|:----:|:-------:|:-------:|
| 01 | Gerenciar Salas |  Diz respeito ao processo de gerenciamento de salas sendo possível registrar, deletar ou editar as informações cada sala e o número de assentos disponíveis. | Funcionário |
| 02 | Gerenciar Filmes | Diz respeito ao processo de gerenciamento de filmes sendo possível registrar, deletar ou editar as informações de cada filme - titulo, duração e disponibilidade  | Funcionário |
| 03 | Vender Ingresso | Efetua a venda do ingresso para uma sessão de filme específica para um cliente que pode comprar o ingresso (meia entrada ou entrada inteira)  | Funcionário |
| 04 | Gerenciar Sessões | Diz respeito ao processo de gerenciamento de sessões sendo possível registrar, deletar ou editar as informações de cada filme - conjunto máximo de ingressos de acordo com a capacidade, horário e data da exibição do filme  | Funcionário |







b) HOTEL
* Os quartos podem ser alugados no momento em que o hóspede chega ao hotel (desde que existam vagas) ou serem reservados via internet.

* Caso seja a primeira vez que aluga quartos, ou seus dados tenham mudado, o hóspede deve ser cadastrado antes de finalizar o aluguel do quarto.
* Além do aluguel do quarto, o hotel oferece diversos serviços, como restaurante, lavar e/ou passar roupas, etc. Obviamente, qualquer desses serviços, se solicitado, será cobrado na fatura final.
* O hóspede pode também consumir os produtos contidos no frigobar, que também são cobrados pelo hotel.
* As diárias vencem ao meio-dia. A política do hotel exige que as diárias sejam quitadas semanalmente. Quando o cliente for quitar a fatura, quitará não somente as diárias do(s) quarto(s) que alugou, mas também qualquer serviço que tenha solicitado e os itens consumidos no frigobar.
* O hóspede, depois que quitar a fatura, pode permanecer no hotel ou encerrar sua estadia.
* Quando for encerrar sua estadia, o hóspede deverá pagar quaisquer serviços e/ou diárias ainda não pagas.
