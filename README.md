# COMPUTAÇÃO EM NUVEM
### Definição

Entrega de servidores, armazenamento, redes entre outros recursos de T.I pela internet, sem a necessidade de possuir infraestrutura propria, quem utiliza paga pelo uso, podendo ser acessado de qualquer lugar, proporciona flexibilidade e escalabilidade e redução de custos.

----

### Modelos de Nuvem

#### Nuvem Pública
Fornecido por provedores externos: (AWS, Google Cloud, Azure), serviço compartilhado com varios clientes e acessivel a qualquer pessoa que assine.
 - Paga-se apenas pelo que é utilizado.
 - Controle menor
 - Escalabilidade Alta
 - Ideal para startups, hospedagem de sites, desenvolvimento e testes

#### Nuvem Privada
Recursos utilizados exclusivamente por uma única organização, que tem controle total sobre os recursos e a segurança, as organizações também sao responsáveis pela manutenção.
 - Total controle
 - Maior segurança
 - Alto custo inicial
 - Escalabilidade depende da infrestrutura interna
 - Ideal para bancos, hospitais, tudo que envolva dados confidenciais

#### Nuvem Híbrida
Combina nuvens públicas e privadas, podendo sob a escolha da organização compartilhar de dados entre elas, as organizações também controlam a segurança.
 - Controle parcial apenas sob a parte privada
 - Custo intermediário
 - Segurança e flexibilidade balanceada
 - Grandes empresas que precisam de sistemas locais com nuvem escalável

----

### CapEx e OpEx

#### CapEx
 - Gasto em infrestrutura
 - Despesas que se reduz com o tempo

#### OpEx
 - Pagamento baseado no uso
 - Custos conforme a demanada
 - Mais flexível e previsível

----
### Beneficios da Nuvem
 - Escalabilidade: Capacidade de aumentar ou reduzir recursos conforme demanda.
 - Elasticidade: Capacidade de ajustar dinamicamente recursos conforme demanda abaixando ou diminuindo em tempo real.
 - Confiabilidade: Garantia de alta disponibilidade do serviço.
 - Previsibilidade: Controle e previsão sobre os gastos e nivel de serviço.
 - Segurança: Recursos e práticas que o provedor fornece para proteção de dados, infraestrutura e ataques mal-intencionados, o uso dos recursos fica sob a responsabilidade do cliente.
 - Governança: Capacidade de controle e criação de regras para o uso responsável dos recursos em nuvem, por exemplo, uma política de quem pode acessar determinado banco de dados.
 - Gerenciabilidade: Capacidade de monitorar e administrar os recursos em nuvem.

----

### Acordo de Nível de Serviço(SLA): 
Descreve a taxa de disponibilidade (99%, 99.9%, 99.99%), tempo de resposta, políticas de segurança, e outros detalhes específicos do serviço que o provedor garante, caso o provedor não cumpra, o cliente pode receber creditos financeiros ou o poder de recisão contratual sem multa.

----

### Tipos de serviço
 - IaaS: Estrutura como serviço, fornece a estrutura de T.I, servidores, armazenamento, redes, você fica responsavel pela gestão do sistema operacional, aplicativos e todo o resto.
 - PaaS: Plataforma como serviço, fornece a estrutura de T.I e o sistema operacional, ferramentas de desenvolvimento, tudo ja pronto, deixando você responsável apenas pelo desenvolvimento da aplicação.
 - SaaS: Software como serviço, aplicações prontas para uso via internet, por exemplo o Office365, Gmail.
 - DbaaS: Banco de dados como serviço, fornece o banco de dados, sem precisar instalar e configurar os servidores, você apenas utiliza o banco.

----

### Mensageria
Ferramentas e recursos para comunicação assíncrona entre os sistemas.
 - Mensagens: Um pacote com dados brutos, que espera que o consumidor tenha alguma ação.
 - Evento: Notificação de uma condição ou alteração de estado, por exemplo, notifica mudanças numa API, "Arquivo X foi criado", "Arquivo X foi alterado", não carregando o Arquivo X dentro da notificação, sem se preocupar se o consumidor vai tomar alguma ação quanto ao que foi recebido, ou seja sua ideia é apenas informar.
 - Filas: Método um-para-um, entram e são processadas em ordem de chegada (FIFO), e é consumida apenas por 1 "destinatário".
 - Tópicos: Metodo um-para-muitos, baseado em pub/sub, vários "destinatários" podem receber a mensagem, podendo notificar vários serviços por exemplo, um bom exemplo é um canal no youtube (tópico), o criador de conteúdo (pub do tópico) posta um vídeo e os inscritos (sub do tópico) recebem o vídeo automáticamente.

