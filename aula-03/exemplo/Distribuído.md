*Distribuido

-Conceito e definição:
--é um estilo arquitetural em que uma aplicação é dividida em vários componentes ou sistemas independentes, que trabalham juntos por meio de uma rede.

Na prática, em vez de todo o sistema funcionar em uma única aplicação, suas funcionalidades podem ser executadas em diferentes servidores, máquinas ou serviços. Esses componentes se comunicam por meio de tecnologias como APIs, HTTP, filas de mensagens e protocolos de comunicação.

-Casos de uso comuns: 
--Plataformas de streaming: serviços de vídeo, autenticação, recomendações e pagamentos podem ser executados separadamente e se comunicar entre si.

--Grandes sistemas de comércio eletrônico: funcionalidades como catálogo, carrinho, pagamentos, estoque e pedidos podem ser distribuídas em diferentes serviços, permitindo que cada parte seja escalada de acordo com sua necessidade.

-Principais vantagens:
--Escalabilidade: cada componente pode ser escalado individualmente conforme a demanda.

--Distribuição de carga: o processamento pode ser dividido entre vários servidores.

-Principais desvantagens:
--Maior complexidade: é mais difícil desenvolver, testar e administrar vários componentes independentes.

--Manutenção mais complexa: é necessário monitorar e gerenciar diferentes serviços, servidores e componentes.