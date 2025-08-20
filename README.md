# Projeto_invest

## Sobre
Projeto desenvolvido em **PHP, HTML, CSS e JavaScript** com foco em práticas de desenvolvimento web.  
O sistema implementa páginas de autenticação, conexão com banco de dados e interfaces de apresentação, servindo como base para aplicações de gerenciamento ou simulação de investimentos.

## Tecnologias Utilizadas
- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: PHP  
- **Banco de Dados**: MySQL/MariaDB  
- (Opcional) Frameworks e ferramentas como Bootstrap, jQuery ou AJAX podem ser adicionados.

## Estrutura de Arquivos

Projeto_invest/
├── .vscode/ - Configurações do Visual Studio Code
├── css/ - Arquivos de estilos (CSS)
├── js/ - Scripts JavaScript
├── src/images/ - Imagens usadas no projeto
├── conexao.php - Script de conexão com banco de dados
├── index.html - Página inicial
├── index2.html - Segunda versão da página inicial
├── leadingpage.html - Landing page / tela inicial
├── login.php - Script e página de login
└── README.md - Este arquivo


### Descrição dos principais arquivos
- **conexao.php**: realiza a conexão com o banco de dados.  
- **login.php**: processa autenticação de usuários.  
- **index.html / index2.html / leadingpage.html**: páginas de interface e navegação inicial.  
- **css/**: arquivos de estilo e layout.  
- **js/**: comportamentos dinâmicos no navegador.  
- **src/images/**: imagens estáticas (logos, ícones, banners).  

## Pré-requisitos
- Servidor web com suporte a PHP (ex: Apache/XAMPP/WAMP)  
- Banco de dados **MySQL** ou **MariaDB**  
- PHP >= 7.4 com PDO ou MySQLi habilitado  

## Instalação e Uso
1. Clone este repositório:
   ```bash
   git clone https://github.com/FMUprojeto/Projeto_invest.git
Copie a pasta para o diretório do seu servidor local (ex: htdocs no XAMPP ou www no WAMP).

Configure o banco de dados:

Crie o schema e as tabelas necessárias.

Ajuste as credenciais em conexao.php (host, usuário, senha, banco).

Acesse no navegador:

bash
Copiar
Editar
http://localhost/Projeto_invest/leadingpage.html
Utilize a página de login (login.php) para testar autenticação.

---
