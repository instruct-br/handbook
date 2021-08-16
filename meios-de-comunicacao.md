# Meios de comunicação

Como a Instruct é uma empresa 100% remota e distribuída, contamos com a ajuda de algumas ferramentas para nos comunicarmos no dia a dia. A escolha do canal deve ser feita de acordo com alguns fatores como urgência, importância da informação e audiência. Abaixo tem a lista de canais disponíveis para se comunicar com outras pessoas da Instruct e orientações para escolher o canal mais adequado.

## Fundamentos

Não tenha medo de se pronunciar perante um colega, líder, gerente ou até mesmo um cliente. Pondere o que será dito e contextualize a situação de maneira estruturada e tangível.

Ouça o que seus colegas de trabalho têm para compartilhar, independente do nível profissional. Estes são necessários para determinar a complexidade de tarefas e demandas de cada um, maturidade profissional e emocional, e autonomia para tomada de decisões. Não são pautados pelo tempo de experiência e não devem ser vistos como barreiras entre as equipes.

Os feedbacks devem ser incentivados e vistos como uma ajuda mútua entre os colegas. Cada um tem seu domínio de conhecimento e isso não o impede de ampliar suas perspectivas para uma visão global.

## Chat (síncrono)

Para comunicação síncrona contamos com uma instância privada de Mattermost.

Envie mensagens curtas, com informações que podem ser perdidas ou não precisam ser consultadas depois. Espera que sua mensagem seja respondida (ou lida) em alguns minutos.

Buscar informações antigas em ferramentas de chat geralmente é uma experiência limitada, pois o resultado pode estar no meio de outras mensagens e a interface não é adequada para isso.

Informações importantes devem persistir na documentação dos projetos ou no portal.

### Canais privados de time

O seu time conta com um canal privado, contendo apenas pessoas do seu time e a gestão para eventual apoio.

Use esse canal para enviar mensagens de caráter efêmero, como:

* Pedir ajuda para solucionar um problema;
* Pedir uma revisão de uma tarefa (mas não faça a revisão pelo canal);
* Combinar uma reunião, comunicar ausência nos próximos dias;
* Pedir para alguém continuar o acompanhamento de algum problema reportado por um cliente;
* Enviar referências para a documentação de um projeto;

O canal do seu time não deve ser usado para planejamento de atividades, registro de decisões importantes para o projeto, revisão de código ou para tirar dúvidas que não precisem de uma resposta imediata.

Como o canal do seu time é privado, usá-lo para o registro de informações ou dúvidas importantes prejudica a transparência e visibilidade do trabalho do seu time.

### Canais públicos

Além dos canais privados para cada time, existem também três categorias de canais públicos:

* Avisos: canais reservados para anúncios importantes e para nosso robô de bater ponto.
* Cafezinho: canais com o prefixo “Cafezinho” são canais informais para falar sobre assuntos não necessariamente relacionados ao trabalho. Apesar de abertos para discutir qualquer assunto, o código de conduta ainda se aplica e comportamento ofensivo não será tolerado.
* Meta-times ou canais de plataforma: os produtos e serviços que cada time trabalha geralmente se encaixam em uma plataforma maior. Discussões relacionadas à recursos compartilhados entre os times são feitas nesses canais. Exemplos: problemas nos runners da plataforma de CI/CD, problemas no cluster Kubernetes, adição ou remoção de um padrão para múltiplos serviços.

### Canais com clientes

Evite a todo custo se comunicar com o cliente através de mensagens diretas e privadas.

Esse trabalho invisível é extremamente prejudicial, pois decisões não ficam formalizadas, piora a acurácia de nossas estimativas e dificulta a contabilização de esforço investido nos projetos.

Procure manter atenção ao aceitar possíveis novas demandas através de comunicação privada, sem passar pelo conhecimento do seu time ou gestão.

### Mensagens 1:1 (direct)

Use o chat privado (1 para 1, mensagem direta) apenas para tratar de assuntos pessoais.

Alguns exemplos:

* Comunicar ausência para um gestor
* Comunicar algum problema pessoal
* Reportar alguma violação do código de conduta.

Não use mensagens diretas para tratar de assuntos que são pertinentes ao conhecimento do seu time, como tomada de decisões ou dúvidas sobre as atividades em que você esteja envolvido. Publique no canal do time.

### Threads e pinagem de mensagens

Nas conversas em canais, use threads para identificar uma conversa. Isso evita que, caso haja dois assuntos diferentes sendo discutidos simultaneamente, um não atrapalhe o outro. Além de facilitar na busca caso queira encontrar alguma conversa antiga.

Caso veja uma mensagem que é forte candidata a ser pinada (fixada) nos canais, considere criar um post no Portal ao invés de fixar. Geralmente é algo importante e que não queremos perder com facilidade e o Portal é a ferramenta recomendada para isso.

## Portal (assíncrono)

Nossa instância privada de Discourse deve ser usada para comunicação assíncrona. Se você tem uma dúvida que não precisa ser respondida imediatamente, tome seu tempo para estruturá-la em um tópico na seção de perguntas e respostas: descreva o problema e o que você já tentou fazer para solucionar, o que não funcionou. Quanto mais informações, melhor.

Crie um tópico para projetos de longa duração, categorizado conforme o cliente e unidade de negócio. A primeira mensagem deste tópico deve conter um resumo do projeto e referências para encontrar mais informações, como o Design Doc e gravações de reuniões de kick-off.

Adicione respostas neste tópico conforme o projeto evolui para criar uma linha do tempo, que facilita o embarque de novas pessoas no projeto. Essas respostas podem conter atas de reuniões do projeto, resumo de entregas e mudanças de escopo ou decisões de grande impacto.

Atas e registros de qualquer encontro para compartilhamento de conhecimento também devem ser registrados no portal, para ser consultável de maneira fácil no futuro.

Evite usar o portal para documentar aspectos mais técnicos dos projetos, dando preferência em manter essa documentação próxima ao código e versionada com o projeto.

## Email (assíncrono)

A comunicação com o cliente deve ser primariamente feita através de email. É importante que toda nova requisição, ou alteração de projeto fique registrada. Caso algo seja decidido por videoconferência, um email com a gravação e a ata deve ser produzido para que isso fique registrado e visível tanto para a Instruct como para o cliente.

Algumas atividades administrativas também são feitas através de email. Você receberá seus holerites por email, por exemplo.

## Videoconferência (síncrono)

Contamos com ferramentas para fazer chamadas de videoconferência. Use-as para fazer sessões de pareamento, tirar alguma dúvida rápida ou discutir alguma ideia que ainda está em fase embrionária. Reuniões para esses fins não precisam ser gravadas.

Reuniões de caráter institucional, entrevistas de processo seletivo e reuniões de compartilhamento técnico devem ser realizadas em ferramentas mais estáveis. Reuniões de compartilhamento técnico devem ser gravadas e registradas no portal junto de uma ata comentando alguns dos tópicos abordados.

Algumas regras se aplicam independente da reunião: verifique a qualidade do áudio de seu microfone antes de começar a falar. Faça testes ou pergunte para alguém no início de uma reunião se conseguem te ouvir bem. Tenha a mesma postura quando for compartilhar a tela de seu computador, confirme se as pessoas conseguem enxergar bem o que você deseja mostrar.

Se ninguém estiver compartilhando a tela, e você estiver com uma boa conexão de internet, mantenha sua câmera ligada para os participantes poderem te ver. Isso atenua muito o distanciamento causado pelo trabalho remoto.

## Agenda e calendário

Quando necessário, marque os compromissos com os colegas de time no seu calendário, convidando apenas as pessoas realmente necessárias para essa reunião.

Registre também horários de indisponibilidade para facilitar a definição de agendas na sua ausência.

Por padrão, todas as agendas de cada colaborador são públicas.