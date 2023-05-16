# Olá, Django!

- [Documentação](https://docs.djangoproject.com/en/4.2/)
- [Documentação do suporte ao fuso horário](https://docs.djangoproject.com/pt-br/4.0/topics/i18n/timezones/)

## Projeto ou Aplicativo?

De forma resumida, um projeto pode conter um ou vários aplicativos e um aplicativo pode estar em vários projetos. Agora de modo mais detalhado, temos:

- Um projeto normalmente envolve a definição dos objetivos, escopo, cronograma, orçamento, alocação de recursos e gestão de riscos para alcançar o resultado desejado.
- Um aplicativo é um software que pode ter diferentes propósitos, como fornecer entretenimento, facilitar tarefas, permitir comunicação, realizar transações comerciais, entre outros.

Um projeto de desenvolvimento de um aplicativo envolveria atividades como análise de requisitos, design, programação, testes e implantação do aplicativo.

## Então esse repositório é um aplicativo ou um projeto?

O objetivo principal deste repositório é conhecer o Framework Django e suas possibilidades de aplicação. Ao seguir o roteiro de implementação do primeiro app em Django, eles reconhecem que o diretório criado (siriusb neste caso), é um projeto que pode conter um ou mais aplicativos. 

### Aplicativos do projeto

- [Polls](https://docs.djangoproject.com/pt-br/4.0/intro/tutorial01/#creating-the-polls-app): aplicativo de enquete.

## Como alterar seus modelos no banco de dados?

1. Mude seus modelos em models.py
2. Rode python manage.py makemigrations para criar migrações para suas modificações
3. Rode python manage.py migrate para aplicar suas modificações no banco de dados

- [Documentação do django-admin](https://docs.djangoproject.com/pt-br/4.0/ref/django-admin/) para saber mais sobre o utilitário manage.py
