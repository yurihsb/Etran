# Etran - Money Transfers Made Simple
O Etran é uma plataforma de gestão financeira e transferências de capital desenvolvida para facilitar o fluxo de caixa de empresas e empreendedores. O sistema permite o controle de despesas, emissão de cartões virtuais e acompanhamento de ativos em tempo real, eliminando burocracias tradicionais como verificações de crédito pessoal.

🚀 Funcionalidades
Gestão de Transferências: Envio e recebimento de valores com liquidação rápida.

Controle de Despesas: Painel administrativo para monitorar gastos operacionais.

Emissão de Cartões: API para geração de cartões virtuais e gestão de cartões físicos para equipes.

Segurança Biométrica: Integração preparada para autenticação de dois fatores e acesso seguro.

Rendimento: Sistema de cálculo automático de juros sobre saldo em conta.

🛠️ Tecnologias Utilizadas
Backend: Django 5.0

Database: PostgreSQL (Recomendado para produção)

Autenticação: Django REST Framework Auth / JWT

Frontend: Django Templates (ou integração com React/Vue via API)

Estilização: CSS3 / Tailwind CSS (seguindo a paleta de cores verde oliva do protótipo)

📋 Pré-requisitos
Antes de começar, você precisará ter instalado em sua máquina:

Python 3.10 ou superior

Pip (Gerenciador de pacotes do Python)

Virtualenv

🔧 Instalação e Configuração
Clone o repositório:

Bash
git clone https://github.com/seu-usuario/etran-django.git
cd etran-django
Crie e ative o ambiente virtual:

Bash
python -m venv venv
# No Windows:
venv\Scripts\activate
# No Linux/Mac:
source venv/bin/activate
Instale as dependências:

Bash
pip install -r requirements.txt
Configure as variáveis de ambiente:
Crie um arquivo .env na raiz do projeto e adicione suas chaves:

Snippet de código
DEBUG=True
SECRET_KEY=sua_chave_secreta_aqui
DB_NAME=etran_db
DB_USER=seu_usuario
DB_PASSWORD=sua_senha
Execute as migrações do banco de dados:

Bash
python manage.py migrate
Inicie o servidor de desenvolvimento:

Bash
python manage.py runserver
📂 Estrutura do Projeto
O projeto segue a estrutura padrão do Django, dividida em aplicações modulares:

core/: Configurações principais do projeto.

accounts/: Gestão de usuários, perfis e autenticação.

transactions/: Lógica de transferências, depósitos e histórico.

cards/: Gerenciamento de cartões físicos e virtuais.

dashboard/: Visualização de dados e métricas financeiras.

🎨 Interface
A interface do projeto foi baseada no design moderno em tons de verde oliva, focando em uma experiência de usuário (UX) limpa e direta, conforme os mockups iniciais.

📄 Licença
Este projeto está sob a licença MIT - veja o arquivo LICENSE para detalhes.
