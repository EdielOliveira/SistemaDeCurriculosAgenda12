<h2 align="center"> Agenda 12 - Sistema de Currículos | ETEC </h2>

<div align="center">
  
<img width="200" height="60" alt="Logo 1" src="https://github.com/user-attachments/assets/7de739ab-4092-4383-ac38-350d3ac586e4" />

![GitHub repo size](https://img.shields.io/github/repo-size/EdielOliveira/Agenda12?style=for-the-badge)

[![My Skills](https://skillicons.dev/icons?i=php,html,css,mysql&theme=dark)](https://skillicons.dev)

</div>

<div align="center">

![image](http://www.unow.com.br/emDesenvolvimento.gif)

<img src="http://img.shields.io/static/v1?label=STATUS&message=%20FINALIZADO&color=YELLOW&style=for-the-badge"/>

</div>

<div align="center">
  
## Índice
  
- [Abrindo o Código](#-abrindo-o-código)
- [Visão Geral](#visão-geral)
- [Arquitetura MVC](#arquitetura-mvc)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Desenvolvedor](#-desenvolvedor)

</div>

<h1 align="left">
🚀 Abrindo o Código
</h1>

Este projeto está disponibilizado **exclusivamente para fins de estudo, análise de código e avaliação da arquitetura MVC**.

**Aviso importante:**  
No momento, **a execução local completa do sistema não está disponível**, pois o projeto depende de uma estrutura de banco de dados que não acompanha o repositório.

Dessa forma, recomenda-se:
- Analisar a **estrutura do projeto**
- Avaliar a **organização MVC**
- Ler os **Models, Controllers e Views**
- Verificar a implementação dos **CRUDs**

A disponibilização do ambiente completo de execução poderá ser considerada em versões futuras.

<h1 align="center">
Visão Geral
</h1>

Este repositório contém um **Sistema Web de Currículos**, desenvolvido em **PHP**, utilizando o padrão **MVC (Model–View–Controller)**.

O sistema permite o gerenciamento completo de currículos, incluindo:

- Cadastro e autenticação de usuários
- Gerenciamento de dados pessoais
- Formação acadêmica
- Experiência profissional
- Outras formações
- Área administrativa para visualização e controle dos cadastros

O projeto foi desenvolvido como parte da **Agenda 12** do curso técnico em **Desenvolvimento de Sistemas**, com foco em organização, boas práticas e separação de responsabilidades.

<h1 align="center">
Arquitetura MVC
</h1>

O projeto segue o padrão **MVC**, garantindo maior organização e manutenibilidade:

- **Model:** Responsável pela lógica de negócio e comunicação com o banco de dados  
- **View:** Responsável pela interface e apresentação dos dados  
- **Controller:** Responsável por intermediar as ações do usuário entre Model e View  

<h1 align="center">
Estrutura do Projeto
</h1>

<img src= https://github.com/user-attachments/assets/628e9f32-1414-40d8-be17-e28f14b7b182/>

<div align="left">

📁 **Controller/**  
Contém os controladores responsáveis pelas regras de negócio e navegação do sistema:

- `UsuarioController.php` – Controle de usuários e autenticação  
- `AdministradorController.php` – Controle da área administrativa  
- `FormacaoAcadController.php` – Formação acadêmica  
- `ExperienciaProfissionalController.php` – Experiência profissional  
- `OutrasFormacoesController.php` – Cursos e formações adicionais  
- `Navegacao.php` – Controle de rotas e redirecionamentos  

📁 **Model/**  
Contém as classes de acesso a dados e regras de negócio:

- `ConexaoBD.php` – Conexão com o banco de dados  
- `Usuario.php` – Entidade usuário  
- `Administrador.php` – Entidade administrador  
- `FormacaoAcad.php` – Formação acadêmica  
- `ExperienciaProfissional.php` – Experiência profissional  
- `OutrasFormacoes.php` – Outras formações  

📁 **View/**  
Responsável pelas interfaces do sistema:

- Telas de login
- Painel administrativo
- Visualização de cadastros
- Listagens e detalhes de usuários  

📁 **Css/**  
Arquivos de estilização do sistema:

- `styles.css`
- `login.css`
- `forms.css`
- `cards.css`
- `navigation.css`
- `sections.css`

📁 **Mensagens/**  
Arquivos de feedback ao usuário:

- `loginNaoRealizado.php`
- `operacaoNaoRealizada.php`

📁 **Img/**  
Imagens utilizadas no sistema

<h1 align="left">
📋 CRUDs do Sistema
</h1>

Este projeto é composto por **4 CRUDs principais**, desenvolvidos seguindo o padrão **MVC (Model–View–Controller)**, garantindo organização, clareza e facilidade de manutenção.

<div align="left">

### 👤 CRUD de Usuário
📁 `Model/Usuario.php`  
📁 `Controller/UsuarioController.php`

**Funcionalidades:**
- Create – Cadastro de usuário
- Read – Consulta de dados do usuário
- Update – Atualização de informações
- Delete – Não implementado explicitamente

📌 utilizado para autenticação e gerenciamento de dados do usuário.

### 🎓 CRUD de Formação Acadêmica
📁 `Model/FormacaoAcad.php`  
📁 `Controller/FormacaoAcadController.php`

**Funcionalidades:**
- Create – Cadastro de formação acadêmica
- Read – Listagem de formações
- Update – Atualização de registros
- Delete – Exclusão de formações

### 💼 CRUD de Experiência Profissional
📁 `Model/ExperienciaProfissional.php`  
📁 `Controller/ExperienciaProfissionalController.php`

**Funcionalidades:**
- Create – Cadastro de experiência profissional
- Read – Listagem de experiências
- Update – Atualização de dados
- Delete – Exclusão de experiências

### 📚 CRUD de Outras Formações
📁 `Model/OutrasFormacoes.php`  
📁 `Controller/OutrasFormacoesController.php`

**Funcionalidades:**
- Create – Cadastro de cursos e formações adicionais
- Read – Listagem de cursos
- Update – Atualização de registros
- Delete – Exclusão de formações

</div>


</div>

<h1 align="center">🤝 Desenvolvedor</h1>

<table align="center">
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/113260177?s=400&v=4" width="150px;" alt="Foto do Desenvolvedor"/><br>
        <sub>
          <b>Ediel Oliveira</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/12d933c6-c44f-4ed8-95ab-ec92d5b65256" width="150px;" alt="Foto do Desenvolvedor"/><br>
      <sub>
          <b>GEEAD</b>
        </sub>
    </td>
  
</table>

<p align="center">
Projeto desenvolvido como atividade acadêmica na ETEC, durante o curso técnico em Desenvolvimento de Sistemas.
</p>




