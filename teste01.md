#Tema: Segurança de redes: Conheça as vulnerabilidades de servidores e clientes<h1>

1. O que é um ataque DDoS e como posso me proteger?
   Um ataque DDoS é um ataque realizado a um determinado servidor alvo que hospeda algum tipo de serviço no qual os atacantes querem deixar o serviço fora do ar, impedindo os usuários de utilizar ele. O método consiste em esgotar os recursos do servidor com milhares de acessos simultâneos, repetidamente, realizados por Botnets, máquinas de usuários infectados por vírus.
   Podemos nos proteger colocando etapas de verificação de usuários para realizar o acesso, como cadastros, e verificações com captcha, além de investimentos na robustez da infraestrutura, como equipamentos de rede IDS, que consegue identificar anomalias no tráfego, e o IPS que consegue impedir que esse tráfego se espalhe para outros pontos da rede.

2. Por que o firewall é uma ferramenta muito importante de proteção?
   O firewall é uma ferramenta de proteção importante porque ele isola uma rede interna do restante da internet, controlando o tráfego entre as duas, tornando-a mais segura contra ataques externos.

Tema: Git e GitHub

3. Explique de forma sucinta, o fluxo e envio de um arquivo novo para o repositório do projeto.
   Devemos estar no repositório e na branch que queremos “commitar”, executamos o comando git add seguido do nome do arquivo, em seguida executamos o comando git commit -m seguido de uma breve descrição e finalizamos com git push caso exista um repositório remoto.

4. Descreva sobre os ganhos de se utilizar a funcionalidade da branch do git.
   A funcionalidade branch nos permite criar uma ramificação paralela do projeto que deixa o desenvolvimento mais organizado e com a possibilidade de várias pessoas trabalharem em paralelo, normalmente em cada branch fica separada uma funcionalidade da aplicação.

5. Explique a diferença entre criar o repositório na nuvem e iniciar o repositório a partir de um código existente local.

6. Qual a diferença entre Git e GitHub?
   O git é um sistema de versionamento de arquivo e o github é uma plataforma de hospedagem dos arquivos versionados em git, guardando remotamente os repositórios da sua máquina. O github também possui outras funcionalidades como fork, pesquisar códigos e podemos utiliza-lo como portifólio.

Tema: Fundamentos de Agilidade: seus primeiros passos para a transformação ágil

7. Quais as principais diferenças entre o modelo ágil e o waterfall (modelo em cascata)?
   Modelo em cascata o trabalho é feito em fases, e cada fase depende da anterior para podermos avançar
   Cascata existe maior demora maior para entregar valor, e maior demora para recebermos feedbacks, e não performa bem em mercados mais voláteis.
   O método ágil quebra o tamanho da entrega para resolvermos estas questões, são priorizados as funcionalidades que entregam mais valor, constante fluxo de tarefas sendo executadas e metas segmentadas, rápido feedback, ciclos rápidos

8. Quais são as 3 perguntas que devem ser respondidas na Daily?
   O que fizemos no dia anterior?
   O que vamos fazer no dia de hoje?
   E se tivemos impedimentos, quais?
9. Qual o intuito das seguintes cerimônias?

• Daily
A daily é utilizada para sabermos como está progredindo o trabalho do time, se existem impedimentos e o que será feito no dia.
Resolver obstáculos do dia dia
Reunião de duração rápida 15min, participa o time todo, sempre no mesmo horário e sempre no mesmo local

• Planning
É a reunião de planejamento feito no início do ciclo, aqui o p.o. traz a product backlog e negocia com o time inteiro as tarefas a serem executadas na sprint que está para começar.
Timebox 5% da sprint, time todo participa, p.o. traz as tarefas, o time transforma a product backlog na sprint backlog

• Refinamento
O refinamento é um processo que cabe ao p.o. do time fazer com o topo da lista da product backlog que está organizada por ordem de prioridade para o cliente, os itens que entregam maior valor de negócio. As histórias mais prioritárias têm sua clareza melhorada, e as funcionalidades maiores são quebradas em pedaços menores que já possuem valor para o cliente.

• Review
A review é o momento da apresentação do que foi feito durante a sprint para o cliente
Levar somente itens prontos
Time inteiro de desenvolvimento participa da reunião
Timebox de 2,5% da sprint
e também uma boa oportunidade para testarmos o produto com o usuário
P.o. deve gerar uma lista de itens organizado por prioridades do cliente a product backlog

• Retrospectiva
A retrospectiva é o momento de avaliarmos o ciclo inteiro,
devemos gerar uma lista de ações, para promovermos o processo de melhoria contínua para sermos melhores na próxima sprint, o time inteira deve participar da retrospectiva, seu timebox tem duração de 5% da sprint

10. O que é a estimativa na metodologia ágil?
    Entender a complexidade do item proposto na product backlog e estimar quanto de esforço empregar na tarefa de maneira confiável, o processo é repetido em todos os itens até completarmos a sprint backlog

Tema: Fundamentos HTTP

11. O que é o protocolo HTTP? Qual a diferença entre HTTP e HTTPS?
    Protocolo http são regras de comunicação entre as partes dentro da internet
    Significa hypertext transfer procol
    Navegador – internet – Servidor (Cliente servidor)
    A diferença entre o http e o https é a segurança, no https os dados trafegam criptografados por ssl ou tls
    Chave pública e privada criptografia assimétrica
    No http os dados trafegam abertos

12. Cite 4 métodos HTTP.
    Get, Post, Put e Delete
    Posso estar falando oq faz cada um etc
