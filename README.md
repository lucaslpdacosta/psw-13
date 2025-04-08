# Projeto Full Stack com Django - Mentorfy

Este projeto é uma plataforma web desenvolvida com [Django](https://www.djangoproject.com/), criada para simplificar a conexão entre mentores e mentorados, oferecendo uma experiência prática e intuitiva para organização, definição de metas e agendamento de encontros.

## Pacotes e Tecnologias Utilizadas
- Asgiref
- Django
- Pillow
- Sqlparse
- Tailwind CSS
- Ttzdata

## Funcionalidades - Mentores
- Criação de contas na plataforma com usernames;
- Organização de horários para agendamento com os mentorados;
- Cadastro e monitoramento do progresso de seus mentorados;
- Estabelecimento de metas individuais para cada mentorado;

## Funcionalidades - Mentorados
- Acesso via token único, sem necessidade de cadastro
- Visualização das metas estabelecidas pelo mentor
- Marcação de "check" nos objetivos atingidos

### Passos para rodar o projeto
1. Clone o repositório:
   ```sh
   git clone --branch 1 --single-branch https://github.com/lucaslpdacosta/psw-13.git
   ```
2. Crie o ambiente virtual:
   ```sh
   Linux: python3 -m venv venv
   Windows: python -m venv venv
   ```
3. Ative o ambiente virtual:
   ```sh
   Linux: source venv/bin/activate
   Windows: venv\Scripts\Activate
   ```
4. Instale as dependências:
   ```sh
   pip install -r requirements.txt
   ```
5. Execute as migrations:
   ```sh
   python manage.py migrate
   ```
5. Inicie a aplicação:
   ```sh
   python manage.py runserver
   ```
6. Acesse a aplicação em: http://localhost:8000/usuarios/login/

### Telas da Aplicação
![Image](https://github.com/user-attachments/assets/6c33d561-e76d-4e5a-a3d0-bcd46adcb15a)
![Image](https://github.com/user-attachments/assets/5d32dfcf-b510-4201-8cd1-a495681fedee)
![Image](https://github.com/user-attachments/assets/fbfc9fbb-3b94-4e06-9328-efe901fbb349)
![Image](https://github.com/user-attachments/assets/ddf71174-4140-4665-9c3d-e25cc32775b2)
![Image](https://github.com/user-attachments/assets/098777be-66db-47cc-8f5a-9f49ddcdb4cb)
![Image](https://github.com/user-attachments/assets/86386c0a-b33c-45a9-a55b-b7c0c800b019)
![Image](https://github.com/user-attachments/assets/a52a1036-6c12-48d6-ac9a-8c4dbcf3c9f4)
![Image](https://github.com/user-attachments/assets/cb6c15e8-d3df-4ba5-8fcd-6bd763218b1d)
