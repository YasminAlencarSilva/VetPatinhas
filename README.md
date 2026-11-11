# 🐾 VetPatinhas — Sistema de Gestão Veterinária

O **VetPatinhas** é um sistema web desenvolvido para facilitar o gerenciamento de uma clínica veterinária, centralizando o atendimento aos tutores e as atividades administrativas e médicas em uma única plataforma.

O projeto foi desenvolvido com foco na organização dos serviços veterinários, no gerenciamento de consultas e no acesso às informações dos pacientes.

## ✨ Funcionalidades

### 👤 Área dos tutores
- Cadastro e login de usuários.
- Gerenciamento de perfil.
- Agendamento de consultas.
- Consulta de exames e resultados.
- Acesso aos prontuários veterinários.
- Consulta de serviços oferecidos pela clínica.

### 🩺 Área administrativa e médica
- Gerenciamento de consultas e calendário.
- Administração de prontuários.
- Envio de exames e documentos.
- Gerenciamento de estoque de medicamentos.
- Atualização de informações administrativas.

## 🛠️ Tecnologias utilizadas

- **PHP** — desenvolvimento da aplicação e funcionalidades do sistema.
- **MySQL** — armazenamento e gerenciamento dos dados.
- **HTML5** — estruturação das páginas.
- **CSS3** — estilização e identidade visual.
- **JavaScript** — validações e interações.

## 📁 Estrutura do projeto

```text
VetPatinhas/
│
├── db/
│   └── Database.sql
│
├── docs/
│   └── DocCompletoPatinhas.pdf
│
├── src/
│   ├── adm/          # Área administrativa e médica
│   ├── connect/      # Conexão e controle de acesso
│   ├── cssAdm/       # Estilos administrativos
│   ├── cssIndex/     # Estilos das páginas públicas
│   ├── img/          # Imagens e recursos visuais
│   ├── Index/        # Páginas e funcionalidades dos tutores
│   └── js/           # Scripts JavaScript
│
├── .gitignore
└── README.md
```

## 🚀 Como executar o projeto

### Pré-requisitos
- PHP.
- MySQL.
- Servidor local, como XAMPP.
- Navegador atualizado.

### Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/YasminAlencarSilva/VetPatinhas.git
   ```

2. Coloque a pasta do projeto no diretório do servidor local, como `htdocs` no XAMPP.

3. Inicie o Apache e o MySQL.

4. Acesse o phpMyAdmin e importe o arquivo:

   ```text
   db/Database.sql
   ```

5. Configure os dados de conexão com o banco de dados no arquivo:

   ```text
   src/connect/conexao.php
   ```

6. Acesse o sistema pelo navegador, utilizando o endereço local correspondente à pasta do projeto.

## 🎯 Objetivo do projeto

O VetPatinhas foi desenvolvido como projeto acadêmico, com o objetivo de aplicar conhecimentos de desenvolvimento web, integração com banco de dados, organização de código e implementação de funcionalidades para um sistema de gestão veterinária.

## 📌 Observação

Este projeto possui finalidade acadêmica e demonstrativa. Os dados de exemplo não devem ser utilizados em ambientes reais. Antes de uma implantação em produção, são necessárias melhorias de segurança, especialmente no tratamento de senhas, autenticação e proteção dos dados.

---

**VetPatinhas — Tecnologia e cuidado para quem faz parte da nossa família de quatro patas. 🐶🐱**
