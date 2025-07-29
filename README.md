# TCC-SRC-CA

TCC - CARTA DE ANUÊNCIA


- O QUE É UMA CARTA DE ANUÊNCIA:

É um comprovante de pagamento que deve ser entregue ao cartório para que seja retirado o protesto do nome do cliente.

Após o retorno do cartório a divida retorna para FEMSA e pode seguir dois caminhos:
  
   1- equipe de cobrança
   2- operação de negociação (ex: kita kof)

- COMO IDENTIFICAR NO SAP?

   Deve-se observar o campo BancoEmpr. Caso se encontre nesse campo os códigos 20000, 5601 ou 40013

   Caso os códigos encontrados sejam 10000, 30000 ou 5301 a dívida ainda está em cartório.

O envio da carta de anuência geralmente é feito de maneira automatica após o pagamento da divida protestada (independentemente de o pagamento ter sido realizado diretamente para FEMSA ou para equipe de cobrança), portanto, clientes que entram em contato pedindo envio da carta de anuencia, geralmente estão se referindo a titulos antigos e pagos há algum tempo.

A entrega da carta pode levar até 5 dias úteis.

Caso um cliente entre em contato para informar que a carta de anuencia não foi aceita em cartório pois o mesmo solicita a cópia da procuração ou contrato social, devemos abrir uma solicitção no OMNI usando a tabulação informada no material do serconect.

Existe a possibilidade de um cliente receber um protesto indevido, nesses casos devemos checar se há uma divida protestada registrada no SAP, caso não, devemos solicitar ao cliente que vá ao cartório e solicite uma certidão positiva, documento esse que declara que o individuo possui pendências. Após o recebimento desse documento, que deve nos ser enviado via Email ou WhatsApp devemos seguir com solicitação no OMNI para que seja avaliado o protesto indevido, onde devemos anexar o comprovante de protesto. (Prazo para tratativa de 72 horas).

Em casos onde o cliente alega que existem divergências na carta de anuencia devemos abrir solicitação para o envio de uma nova.

Existem casos onde a entrega da carta de anuência não foi realizada pela UO (o que significa UO??????). Nesses casos devemos abrir solicitação via OMNI com tipo de ocorrência: "Avaliar protesto indevido".

Outra possibilidade é de o cliente entrar em contato informando que o protesto indevido não foi retirado. Nesse caso também abriremos solicitação no OMNI com tipo de ocorrência sendo "Envio de comprovante cancelamento protesto".

PEFIN (negativação registrada no Serasa) - Seguir passo a passo do Serconect.

1 - Confirmar NF e valor que o cliente alega estar negativado.
2 - Confirmar se NF encontra-se compensada.
3 - Se estiver compensada, deve-se validar o banco empresa, caso esteja com os códigos de cartório, seguir com o script de cartório. Caso não tenha alteração no banco empresa, deve ser validado o campo texto, que estará com a informação “PEFIN XX.XX.XX (data da inclusão do pefin)”

Independente do motivo que a partida compensada estiver, deve ser aberto o chamado para analise/retirada do pefin.

 Caso a partida esteja em aberto, deve ser considerado o motivo/banco empresa para sequenciar o atendimento. 

Caso em sistema não possua nenhuma informação de cartório ou pefin, e o cliente alegue que está negativado, pode ser aberto um chamado para analise/retirada do pefin. 



