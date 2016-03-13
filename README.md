CardDig - Sistema de cardápio digital
=====================================

Esse sistema visa atender restaurantes e estabelecimentos que desejam automatizar
e melhorar a experiência de seus clientes usando tecnologia.

Ambiente
========

Este projeto foi testado e desenvolvido com:
* Python 3.5.1
* Django 1.9.4

Instalação
==========

Pegue o código do repositório da seguinte maneira:

    git clone git@github.com:henriquenogueira/carddig.git

Copie o arquivo contrib/env-sample para o root do projeto com o nome .env:

    cp contrib/env-sample .env

Gere uma SECRET_KEY e a coloque no .env:

    SECRET=$(python contrib/gen_secret.py)

Instale as dependências necessárias:

    pip install -r requirements/dev.txt

Lance o servidor Django:

    python manage.py runserver

Testes
======

Os testes do CardDig foram implementados usando o
[framework de testes do Django](https://docs.djangoproject.com/en/1.9/topics/testing/overview/).

Para a execução dos testes:

    python manage.py test

Problemas conhecidos
====================

Nenhum problema reportado até então.
