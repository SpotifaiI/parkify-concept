# Parkify

Introdução e apresentação do projeto Parkify.

# Tabela de Conteúdos

- [Parkify](#parkify)
- [Tabela de Conteúdos](#tabela-de-conteúdos)
- [Requisitos](#requisitos)
  - [Funcionais](#funcionais)
  - [Não Funcionais](#não-funcionais)
- [Arquitetura](#arquitetura)

# Requisitos

## Funcionais

## Não Funcionais

- A Inteligência Artificial deve ser desenvolvida com Python, enquanto os atuadores e componentes serão comandados via Arduino, desenvolvidos com C++.
- A aplicação deve fornecer atualizações em tempo real sobre a disponibilidade de vagas, minimizando a latência entre a detecção do sensor e a exibição na interface de visualização.
- O sistema deve ser escalável para suportar múltiplos estacionamentos e um grande número de sensores e atuadores simultaneamente, mantendo o desempenho constante.
- A inteligência artificial que analisa padrões de estacionamento deve ser otimizada para lidar com grandes quantidades de dados, como tráfego de veículos e ocupação de vagas, sem degradação de performance.
- O sistema deve estar disponível 24/7 com mínima interrupção para garantir que os motoristas sempre possam localizar vagas disponíveis.
- Deve haver mecanismos de recuperação rápida para lidar com falhas, como redes de sensores ou interrupções no servidor, para minimizar o impacto na operação.
- Sensores e atuadores devem ser monitorados continuamente para garantir que estão funcionando corretamente e detectar qualquer anomalia no sistema.
- Toda a comunicação entre os sensores, atuadores, bancos de dados e a interface de usuário deve ser protegida por criptografia para prevenir interceptação e manipulação de dados.
- A aplicação deve garantir que somente dispositivos autorizados (como sensores e atuadores) possam se conectar à rede para enviar ou receber dados.
- A inteligência artificial deve ser protegida contra manipulação de dados, garantindo que os resultados das análises (como vagas disponíveis) não sejam comprometidos.
- O sistema deve ser modular para facilitar futuras atualizações ou expansões, como a inclusão de novos sensores, novas funcionalidades de IA ou integração com sistemas de terceiros.
- O sistema deve ter ferramentas integradas para monitorar o desempenho da IA e da infraestrutura, facilitando a manutenção e a identificação de possíveis gargalos ou falhas.
- A aplicação deve ser compatível com diferentes tipos de sensores (proximidade, luminosidade, pressão, etc.) para facilitar a integração com diferentes tecnologias de estacionamento.
- O sistema deve seguir padrões de comunicação como MQTT e HTTP para permitir a integração com diferentes plataformas e dispositivos, além de suportar diferentes sistemas operacionais e dispositivos móveis.
- Sensores e atuadores devem ser energeticamente eficientes, especialmente em estacionamentos ao ar livre onde os dispositivos podem depender de energia solar ou baterias.
- O sistema deve minimizar o tráfego de dados desnecessário, especialmente ao lidar com grandes volumes de informações transmitidas pelos sensores.
- A interface para os usuários (motoristas) deve ser fácil de usar, com informações claras e atualizadas sobre a disponibilidade de vagas próximas, incluindo instruções de navegação.
- A aplicação deve ser responsiva e compatível com dispositivos móveis, permitindo que os motoristas acessem as informações de vagas disponíveis enquanto estão em movimento.
- Em caso de falhas de rede ou interrupções temporárias de conexão, o sistema deve ser capaz de operar em modo offline, armazenando dados localmente e sincronizando com o servidor quando a conectividade for restaurada.
- A IA deve ser capaz de prever com alta precisão a disponibilidade de vagas com base em dados históricos, padrões de movimento de veículos, e condições atuais do estacionamento.
- O modelo de IA deve ser continuamente treinado com novos dados para melhorar sua capacidade de prever e adaptar-se a mudanças nas condições de ocupação das vagas e comportamento dos motoristas.

# Arquitetura

![Architecture diagram exploring both hardware and services flow](assets/architecture-diagram.png)
