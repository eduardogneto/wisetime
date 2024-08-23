WiseTime: Sistema de Gerenciamento de Ponto

Resumo

  O documento apresenta o "WiseTime", um sistema de gerenciamento de ponto desenvolvido para atender às demandas tanto dos administradores     quanto dos funcionários. Com uma abordagem inovadora, o WiseTime oferece uma visão abrangente do registro de horas, permitindo aos administradores acessar todo o histórico de horas dos funcionários, identificar horários de início e término de cada dia de trabalho e visualizar um relatório detalhado de horas positivas e negativas. Além disso, o sistema facilita a gestão administrativa ao permitir o processamento de solicitações de atestados ou adição manual de pontos de forma transparente e rastreável. Para os funcionários, o WiseTime oferece uma interface intuitiva e simplificada para o registro de entrada e saída. Em resumo, o WiseTime promove transparência, precisão e eficiência no gerenciamento de ponto para ambas as partes envolvidas.

1. Introdução
   
1.1 Contexto

  Atualmente, a gestão eficiente do tempo é essencial para o sucesso de organizações de todos os portes. Com a expansão do trabalho remoto e flexível, bem como a necessidade de conformidade com regulamentações trabalhistas cada vez mais rigorosas, surge uma demanda crescente por soluções de registro de ponto que sejam acessíveis e eficientes. Nesse contexto dinâmico, a necessidade de desenvolver sistemas de bater ponto inovadores e eficazes se torna uma prioridade para as empresas modernas.

1.2 Justificativa

  A implementação do WiseTime é justificada pela necessidade urgente de simplificar e aprimorar a gestão das horas trabalhadas. Ao oferecer uma plataforma abrangente tanto para administradores quanto para funcionários, o sistema visa reduzir o tempo dedicado à administração de ponto, minimizar erros e inconsistências nos registros, e garantir a conformidade com as regulamentações trabalhistas vigentes. Além disso, ao promover a transparência e eficiência no controle de jornada, o WiseTime contribui para a construção de um ambiente de trabalho mais produtivo e equitativo.

  Para o campo da engenharia de software, a relevância do projeto é substancial. O desenvolvimento e a implementação do WiseTime envolvem o uso de práticas avançadas de engenharia de software, como integração contínua, desenvolvimento ágil e a aplicação de algoritmos de análise de dados para otimizar a precisão dos registros de tempo. Este projeto serve como um estudo de caso significativo para a aplicação de técnicas de design de sistemas, arquitetura de software e gestão de projetos em um contexto real e crítico. Além disso, a criação de uma solução robusta e escalável que atenda às necessidades de diferentes usuários e empresas pode fornecer insights valiosos para futuras inovações e melhorias no campo. O WiseTime não apenas resolve um problema prático importante, mas também contribui para o avanço do conhecimento e das práticas na engenharia de software, destacando a importância de soluções tecnológicas eficientes e bem projetadas para a gestão de recursos humanos.

1.3 Objetivos

Os objetivos principal:

• Facilitar o registro de ponto para os funcionários, proporcionando uma interface intuitiva e de fácil utilização.

Os objetivos segundarios:

• Capacitar os administradores a acessar e gerenciar o histórico de horas dos funcionários de maneira eficiente e eficaz.
• Fornecer uma solução confiável e segura para o registro de ponto, garantindo transparência, precisão e conformidade com as regulamentações vigentes.
• Por meio desses objetivos, o WiseTime busca otimizar o processo de gestão de tempo nas organizações, impulsionando a eficiência e o desempenho global.

2. Descrição do Projeto
   
Tema do Projeto
• WiseTime é um sistema de gerenciamento de ponto baseado na web. O WiseTime oferecerá uma plataforma completa para registro de entrada e saída de funcionários, bem como ferramentas de gestão e análise para administradores.

Problemas a Resolver

• Dificuldades na gestão eficiente do tempo de trabalho dos funcionários.
• Erros e inconsistências nos registros de ponto devido a métodos tradicionais e manuais.
• Complexidade na visualização e análise do histórico de horas trabalhadas pelos administradores.
• Falta de transparência e dificuldades na comunicação entre funcionários e empregadores relacionadas aos registros de ponto.

Limitações:

O projeto WiseTime não abordará os seguintes aspectos:

• Integração com sistemas de folha de pagamento ou outros sistemas de RH.
• Customizações muito específicas para necessidades de empresas altamente especializadas, como indústrias reguladas por normas de segurança específicas.

3. Especificação Técnica

3.1. Requisitos de Software

Requisitos Funcionais:

• RF01 - Registro de Ponto: Os funcionários devem poder registrar sua entrada e saída de forma 
intuitiva e simplificada através da interface do WiseTime. 
• RF02 - Mostrar saldo de horas: O sistema mostra o saldo de horas do usuario. 
• RF03 - Validar usuario admin e comum: O sistema valida o login de usuario admin ou usuario 
convencional. 
• RF04 - Processamento de Solicitações de Atestados: O WiseTime deve possibilitar o 
processamento de solicitações de atestados pelos funcionários de forma transparente e 
rastreável, registrando adequadamente as horas relacionadas.
• RF05 - Adição Manual de Pontos: Os administradores devem ter a capacidade de adicionar 
manualmente pontos de entrada e saída para os funcionários quando necessário, garantindo 
transparência e rastreabilidade. 
• RF06 - Cadastrar novo funcionario: Possibilidade do usuario administrador cadastrar um 
funcionario novo para supervisionar. 
• RF07 - Mostrar relatorio de saldo de horas: O sistema mostra todo o relatório de entrada, saida e 
saldo dos funcionarios. 
• RF08 - Mostrar solicitacoes de atestado: O sistema mostra todas as solicitacoes em abertas de 
atestado, dando possibilidade de aprovar ou reprovar. 
• RF09 - Mostrar solicitacoes de alteração de ponto: o O sistema mostra todas as solicitacoes de 
alteracao de ponto, podendo aprovar uma edição, inserção ou exclusão. o Prioridade: Baixa. 


Requisitos Não Funcionais:

• RNF01 - Interface Intuitiva e Simplificada: A interface do WiseTime deve ser 
intuitiva e simplificada, garantindo que os funcionários possam registrar seu 
ponto facilmente, sem a necessidade de treinamento extensivo. 
• RNF02 - Segurança: O sistema deve garantir a segurança dos dados dos 
funcionários, implementando medidas robustas de proteção e criptografia. 
• RNF03 - Conformidade com Regulamentações Trabalhistas: O WiseTime deve 
estar em conformidade com as regulamentações trabalhistas vigentes, 
garantindo que os registros de ponto sejam precisos e atendam aos requisitos 
legais. 
• RNF04 - Desempenho e Escalabilidade: O sistema deve ser capaz de lidar com 
um grande volume de registros de ponto e usuários simultâneos, mantendo um 
desempenho rápido e eficiente. 
• RNF05 - Disponibilidade: o O WiseTime deve estar disponível de forma 
confiável, com um tempo de inatividade mínimo para garantir que os 
funcionários possam registrar seus pontos a qualquer momento necessário.

3.2. Considerações de Design

3.2.1 Visão geral

• A estrutura do WiseTime será baseada em uma aplicação monolítica devido aos diversos benefícios que essa arquitetura oferece, especialmente na fase inicial do projeto e considerando o escopo das funcionalidades previstas. A escolha de uma arquitetura monolítica proporciona várias vantagens significativas, como simplicidade de desenvolvimento, facilidade de testes e debugging, desempenho otimizado, facilidade de implantação e gerenciamento, e evolução rápida durante as fases iniciais do projeto.

3.2.2 Padrões de Arquitetura Utilizados

• Arquitetura MVC (Model-View-Controller): A arquitetura MVC foi escolhida como a estrutura principal do projeto devido à sua comprovada eficiência na separação de responsabilidades. O padrão MVC divide a aplicação em três componentes principais: Model, View e Controller, facilitando a manutenção e a escalabilidade.
• Modelo C4: O Modelo C4 (Context, Container, Component, and Code) foi adotado para fornecer uma representação clara e compreensível da arquitetura do sistema em diferentes níveis de abstração, complementando a arquitetura MVC.
• TDD (Test-Driven Development): O Desenvolvimento Orientado a Testes (TDD) é seguido para assegurar a qualidade do código, promovendo a escrita de testes antes do desenvolvimento das funcionalidades.
Metodologia Ágil com Jira: Utilizamos o Jira para gerenciamento de projetos, adotando metodologias ágeis como Kanban e Scrum para visualização do fluxo de trabalho, gestão contínua das tarefas, e definição clara de metas a curto prazo.

3.3. Stack Tecnológica

3.3.1 Linguagens de Programação

• Java 21 (Backend): Escolhemos Java 21 devido à sua robustez, ampla adoção na indústria e suporte a recursos modernos de programação.
• JavaScript (Frontend): Utilizaremos JavaScript para o desenvolvimento do frontend, com foco principal no ReactJS.

3.3.2 Frameworks e Bibliotecas

• ReactJS (Frontend): Escolhido pela sua eficiência na criação de interfaces de usuário interativas e reativas.
• Sass (Frontend): Utilizado para customização de estilos, facilitando a manutenção e organização do código CSS.
• Axios (Integração Frontend-Backend): Usado para requisições HTTP entre o frontend e o backend.
• Hibernate (Backend): Utilizado como framework ORM para mapear objetos Java para as tabelas do banco de dados PostgreSQL.
• Spring Boot (Backend): Adotado para facilitar a configuração e o desenvolvimento do backend.

3.3.3 Banco de Dados

• PostgreSQL: Utilizado devido à sua robustez, escalabilidade e suporte a recursos avançados como consultas complexas e transações ACID.

4. Conclusão

O WiseTime é um sistema inovador que atende às necessidades de gerenciamento de ponto de empresas modernas, promovendo a eficiência, precisão e transparência no registro de horas trabalhadas. Com uma abordagem focada tanto nos administradores quanto nos funcionários, o sistema oferece funcionalidades robustas e uma interface intuitiva para facilitar a gestão do tempo de trabalho.
