# meu-primeiro-pipeline
# Meu Primeiro Pipeline com GitHub Actions

Este projeto foi criado como parte do meu aprendizado em DevSecOps.  
Aqui, montei meu **primeiro pipeline de integração contínua (CI)** usando o GitHub Actions para testar um código Python simples.

---

## Objetivo

Aprender os fundamentos de CI/CD criando um robô (pipeline) que:
- Verifica automaticamente se o código está funcionando
- Roda testes sempre que eu fizer uma mudança no repositório
- Me avisa se algo estiver quebrado

---

## O que foi feito

1. Criei um repositório chamado `meu-primeiro-pipeline`
2. Escrevi um código simples em Python (`main.py`) com uma função de soma
3. Criei um arquivo de teste (`test_main.py`) para verificar se a função funciona corretamente
4. Configurei um pipeline usando GitHub Actions (`ci.yml`) que:
   - Clona o repositório
   - Instala o Python
   - Instala o `pytest` (ferramenta de testes)
   - Roda os testes automaticamente

---

## Tecnologias Utilizadas

| Tecnologia        | Finalidade                                                                 
|                   |
| **GitHub**        | Hospedar o projeto e usar o GitHub Actions para automação                 
| **GitHub Actions**| Criar o pipeline que executa os testes automaticamente                    
| **Python**        | Linguagem usada para escrever o código e os testes                        
| **pytest**        | Biblioteca de testes para verificar se o código está funcionando corretamente 
| **YAML**          | Linguagem usada para configurar o pipeline (`ci.yml`)                     

---

## Estrutura do Projeto
meu-primeiro-pipeline/
├── main.py # Função de soma 
├── test_main.py # Testes da função 
└── .github/ 
└── workflows/ 
└── ci.yml # Pipeline do GitHub Actions

---

## Como funciona o pipeline

Sempre que eu fizer uma mudança no repositório (push ou pull request), o GitHub Actions:
1. Acorda o robô (pipeline)
2. Clona o código
3. Instala o Python e o pytest
4. Roda os testes
5. Me mostra se tudo passou ou se deu erro

---

## Aprendizado

Com este projeto, aprendi:
- Como criar um repositório no GitHub
- Como escrever testes simples em Python
- Como configurar um pipeline básico com GitHub Actions
- Como usar automação para verificar qualidade do código

---

## Sobre mim

Sou Gabriel Guimarães, estudante de Análise e Desenvolvimento de Sistemas e aspirante a profissional na área de **DevSecOps**.  
Este projeto é o primeiro passo da minha jornada para entender como segurança, automação e desenvolvimento se conectam.

---

## Contato

-  [LinkedIn](https://linkedin.com/in/gabrie-s-guimaraes)
-  [GitHub](https://github.com/guimaraes997)


