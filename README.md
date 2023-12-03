# Introdução

Para utilizar o projeto a seguir é necessário primeiro clonar o repositório, para tal basta em seu terminal executar os seguintes comandos:

1. `git clone https://github.com/ /cookies-n-soda`
2. `cd cookies-n-soda`

Este é um projeto feito para representar um sistema teórico de compras de cookies e beidas.

# Executar

Para apenas executar o repositório da maneira que está sem fazer modificações no projeto basta rodar o seguinte comando em seu terminal:

`docker-compose up --build`

Mas para antes é necessário que o [Docker](https://www.docker.com/) e [docker-compose](https://docs.docker.com/compose/) estejam instalados e configurados na sua máquina!

# Instalar

Caso queira interagir com o projeto, você deverá antes instalar ele na sua máquina, para tal precisará do [Python](https://www.python.org/) e do [PIP](https://pypi.org/project/pip/) instalados nela; em seguida basta rodar os seguintes comandos em seu terminal:

1. `pip install --break-system-packages -r requirements.txt`
2. `python manage.py migrate`

# Cadastro de produtos

1. Rode no terminal `python manage.py createsuperuser` para criar o usuário administrador do sistema
2. Execute o projeto e abra a url: http://localhost/admin/
3. Em Items há a opção de adicionar -- um mais seguido de Add --, clique nela
4. Preencha as informações com o item que deseja adicionar
