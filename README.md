# SGE - Sistema de Gestão Empresarial

## Descrição
O SGE é um sistema de gestão empresarial desenvolvido com Django. Ele permite gerenciar marcas, categorias e fornecedores de forma eficiente.

## Estrutura do Projeto
O projeto está organizado da seguinte forma:
```
sge/
│
├── app/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│
├── brands/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   └── migrations/
│
├── categories/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   └── migrations/
│
├── suppliers/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   └── migrations/
│
├── db.sqlite3
├── manage.py
├── README.md
└── requirements.txt
```

## Instalação
1. Clone o repositório:
    ```sh
    git clone <URL_DO_REPOSITORIO>
    cd sge
    ```

2. Crie um ambiente virtual e ative-o:
    ```sh
    python -m venv venv
    source venv/bin/activate  # No Windows use `venv\Scripts\activate`
    ```

3. Instale as dependências:
    ```sh
    pip install -r requirements.txt
    ```

4. Execute as migrações:
    ```sh
    python manage.py migrate
    ```

5. Inicie o servidor de desenvolvimento:
    ```sh
    python manage.py runserver
    ```

## Aplicações
- **Brands**: Gerenciamento de marcas.
- **Categories**: Gerenciamento de categorias.
- **Suppliers**: Gerenciamento de fornecedores.

## Contribuição
1. Faça um fork do projeto.
2. Crie uma nova branch (`git checkout -b feature/nova-feature`).
3. Faça commit das suas alterações (`git commit -am 'Adiciona nova feature'`).
4. Faça push para a branch (`git push origin feature/nova-feature`).
5. Crie um novo Pull Request.

## Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
