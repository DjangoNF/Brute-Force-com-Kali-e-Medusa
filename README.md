# Projeto de Cybersegurança: Simulação de Ataque Brute Force com Medusa

## 📌 Sobre o Projeto

Este projeto foi desenvolvido com fins exclusivamente educacionais e de treinamento em Cybersegurança, utilizando um ambiente controlado de laboratório virtual. O objetivo principal foi compreender o funcionamento de ataques de força bruta (Brute Force), identificar vulnerabilidades relacionadas à autenticação e praticar técnicas de análise de segurança ofensiva de forma ética e autorizada.

O laboratório foi composto por uma máquina atacante executando o sistema operacional **Kali Linux** e uma máquina alvo **Metasploitable**, amplamente utilizada para estudos e testes de segurança.

---

## 🎯 Objetivos

- Compreender o funcionamento de ataques de força bruta.
- Aprender a utilizar ferramentas de auditoria de autenticação.
- Praticar técnicas de enumeração de usuários.
- Identificar credenciais fracas em serviços vulneráveis.
- Desenvolver experiência prática em ambientes de testes de segurança.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

- Kali Linux
- Medusa
- Metasploitable
- SMB (Server Message Block)
- Virtualização de ambientes de laboratório
- Listas personalizadas de usuários e senhas

---

## 🏗️ Estrutura do Projeto

### Arquivo de Usuários

Foi criado o arquivo:

```text
smb_users.txt
```

Responsável por armazenar uma lista de possíveis usuários utilizados nos testes de autenticação.

### Arquivo de Senhas

Foi criado o arquivo:

```text
senhas_spray.txt
```

Contendo combinações de senhas utilizadas na técnica de Password Spraying e validação de credenciais.

---

## 🔍 Metodologia

1. Identificação do endereço IP da máquina alvo (Metasploitable).
2. Levantamento das portas e serviços disponíveis.
3. Criação de listas de usuários e senhas para testes controlados.
4. Utilização da ferramenta Medusa para automatizar tentativas de autenticação.
5. Execução de testes contra o serviço SMB da máquina alvo.
6. Identificação de credenciais válidas através da análise dos resultados.
7. Documentação das vulnerabilidades encontradas e das medidas de mitigação recomendadas.

---

## 🚩 Resultados Obtidos

Através da utilização do Medusa e das listas personalizadas de usuários e senhas, foi possível realizar testes de autenticação e identificar credenciais válidas configuradas na máquina de laboratório.

O projeto demonstrou na prática como credenciais fracas ou previsíveis podem representar um risco significativo para a segurança de sistemas e redes.

---

## 📚 Conhecimentos Aplicados

Durante o desenvolvimento deste projeto foram aplicados conceitos relacionados a:

- Ethical Hacking
- Brute Force Attack
- Password Spraying
- Enumeração de Usuários
- Segurança de Redes
- Testes de Penetração
- Gestão de Credenciais
- Segurança em Serviços SMB
- Análise de Vulnerabilidades

---

## 🔐 Lições Aprendidas

- A importância da utilização de senhas fortes e complexas.
- A necessidade de políticas de bloqueio de conta após múltiplas tentativas de login.
- A relevância da autenticação multifator (MFA).
- A importância do monitoramento e registro de tentativas de autenticação.
- Como ferramentas ofensivas podem ser utilizadas para fortalecer a segurança quando aplicadas de forma ética.

---

## ⚠️ Aviso Ético

Este projeto foi realizado exclusivamente em ambiente de laboratório controlado, utilizando máquinas destinadas ao aprendizado em Cybersegurança.

Todas as atividades foram conduzidas com finalidade educacional, de pesquisa e desenvolvimento profissional. O conhecimento adquirido visa fortalecer habilidades na área de Segurança da Informação e contribuir para a formação como futuro profissional de Cybersegurança.

O uso dessas técnicas contra sistemas sem autorização é ilegal e contrário aos princípios éticos da área.

---

## 👨‍💻 Autor

Projeto desenvolvido como parte da minha jornada de aprendizado em Cybersegurança, visando aprimorar conhecimentos práticos em testes de penetração, análise de vulnerabilidades e segurança de redes.

**Objetivo profissional:** desenvolver competências técnicas e experiência prática para atuar de forma ética e responsável na área de Segurança da Informação.
