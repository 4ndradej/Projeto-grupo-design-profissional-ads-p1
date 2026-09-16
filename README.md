# Tec Maslah

## Sistema Web para Gestão de Clínicas Populares

A **Tec Maslah** desenvolveu uma plataforma web para facilitar a gestão de uma rede de clínicas populares, conectando pacientes, profissionais e unidades de atendimento em um único sistema.

A solução foi pensada para tornar o processo de agendamento mais simples, organizado e acessível, permitindo que o paciente acompanhe seus atendimentos e receba notificações diretamente pela plataforma.

---

## Sobre o Projeto

O sistema permite que pacientes:

* Realizem agendamentos online;
* Consultem seus próximos atendimentos;
* Acompanhem o histórico de agendamentos;
* Recebam notificações sobre consultas;
* Tenham acesso às informações de seus atendimentos.

Para a gestão da clínica, a plataforma centraliza informações e processos, contribuindo para uma operação mais organizada e eficiente.

---

## Desenvolvimento

O projeto foi desenvolvido seguindo etapas de desenvolvimento de software, desde o planejamento até a implementação da aplicação.

### Gestão de Projeto

Utilização de práticas e ferramentas para organização e acompanhamento do desenvolvimento:

* Kanban;
* GitHub;
  
### Análise de Requisitos

Levantamento das necessidades dos usuários e definição das funcionalidades do sistema.

Principais requisitos:

* Cadastro e autenticação de usuários;
* Agendamento de consultas;
* Consulta e gerenciamento de agendamentos;
* Histórico de atendimentos;
* Sistema de notificações;
* Gestão de clínicas, profissionais e horários.

### UX/UI Design

A interface foi planejada com foco em simplicidade, acessibilidade e facilidade de navegação.

Tecnologias e ferramentas utilizadas:

* Figma;

### Frontend

Responsável pela interface e interação dos usuários com a plataforma.

Tecnologias:

* HTML5;
* CSS3;
* JavaScript;
* React;

### Backend

Responsável pelas regras de negócio, autenticação, gerenciamento dos dados e comunicação entre o sistema e o banco de dados.

Tecnologias:

* Node.js;
* Express;
* API REST;
* JWT;
* Integração com serviços de notificação.

### Banco de Dados

Responsável pelo armazenamento e organização das informações da plataforma.

Tecnologias:

* PostgreSQL;
* SQL;
* Modelagem de dados;
* Relacionamentos entre entidades;
* CRUD;

---

## Arquitetura

A aplicação utiliza uma arquitetura dividida em camadas, facilitando a manutenção, evolução e escalabilidade do sistema.

```text
                    USUÁRIO
                       |
                       v
              +----------------+
              |    Frontend    |
              |     React      |
              +----------------+
                       |
                       v
              +----------------+
              |   API REST     |
              | Node.js/Express|
              +----------------+
                       |
             +---------+---------+
             |                   |
             v                   v
      +-------------+     +-------------+
      | PostgreSQL  |     | Notificações|
      +-------------+     +-------------+
```

---

## Principais Funcionalidades

### Para pacientes

* Cadastro e login;
* Agendamento de consultas;
* Visualização de horários disponíveis;
* Acompanhamento de agendamentos;
* Histórico de consultas;
* Recebimento de notificações.

### Para clínicas

* Gerenciamento de unidades;
* Cadastro de profissionais;
* Controle de horários;
* Gerenciamento de consultas;
* Organização dos agendamentos;
* Centralização das informações.
  
---

## Objetivo

O principal objetivo da plataforma é **digitalizar e simplificar a gestão de clínicas populares**, oferecendo uma experiência mais prática para os pacientes e uma operação mais organizada para as clínicas.

A Tec Maslah busca unir tecnologia, usabilidade e eficiência para transformar processos tradicionais de atendimento em uma experiência digital mais simples.

---

## Estrutura do Projeto

```text
tec-maslah/
│
└── README.md
```

---

## Status

Projeto em desenvolvimento.

Novas funcionalidades e melhorias podem ser adicionadas conforme a evolução da plataforma e as necessidades dos usuários.

---

## Tec Maslah

**Tecnologia para simplificar a gestão e aproximar pessoas dos serviços de saúde.**
