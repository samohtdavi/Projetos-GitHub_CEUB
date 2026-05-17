# Sistema de Segurança Cibernética

### Controle de Acesso, Proteção de Dados e Filtro Inteligente

 Projeto acadêmico desenvolvido para a disciplina de **Introdução à Computação**
 Curso: Engenharia da Computação

---

## Sobre o Projeto

Este projeto propõe uma solução de **segurança digital em duas camadas**, voltada principalmente para pequenas empresas e ambientes familiares, com foco em:

* Proteção contra invasões e ataques cibernéticos
* Controle de acesso seguro a dados
* Monitoramento de atividades digitais
* Filtragem inteligente de conteúdos

A solução integra tecnologias modernas como **computação em nuvem, autenticação multifator (2FA), biometria e inteligência artificial**, garantindo maior segurança, controle e eficiência.

---

##  Problema

Muitas pequenas empresas e usuários domésticos não possuem sistemas robustos de segurança, o que resulta em:

* Vazamento de dados sensíveis
* Acesso não autorizado
* Exposição a conteúdos impróprios
* Crescimento de golpes e fake news

---

##  Solução Proposta

O sistema implementa:

###  Camada 1 — Segurança de Dados

* Autenticação com login e senha criptografada
* Autenticação em dois fatores (2FA)
* Reconhecimento biométrico (digital/face)
* Armazenamento híbrido (Cloud + Servidor Local)

### Camada 2 — Filtro e Monitoramento

* Análise de conteúdo com IA (texto, imagem e vídeo)
* Bloqueio de conteúdos impróprios
* Controle parental
* Monitoramento de atividades
* Limite de tempo de uso

---

##  Arquitetura do Sistema

O sistema segue uma arquitetura **cliente-servidor**, composta por:

*  Cliente (Mobile/Desktop)
*  Camada de autenticação (2FA + biometria)
*  API Backend (regras de negócio)
*  Banco de dados em nuvem
*  Servidor local (cache e redundância)

---

##  Tecnologias Utilizadas

### Backend

* Node.js
* Express
* API REST

### Segurança

* Autenticação 2FA
* Criptografia de senhas
* Controle de acesso

### Inteligência Artificial (simulada)

* Filtro de palavras-chave
* Análise de conteúdo

### Ferramentas

* GitHub (versionamento)
* PowerPoint (diagrama)
* (Opcional) Figma / Canva (protótipo)

---

##  Como Executar o Projeto

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/seguranca-digital.git

# Entrar na pasta
cd seguranca-digital

# Instalar dependências
npm install

# Rodar o servidor
npm start
```

Servidor disponível em:
 http://localhost:3000

---

##  Endpoints da API

###  Login

```
POST /auth/login
```

Exemplo:

```json
{
  "username": "admin",
  "password": "1234"
}
```

---

###  Análise de Conteúdo

```
POST /content/analyze
```

Exemplo:

```json
{
  "text": "site de apostas online"
}
```

Resposta:

```json
{
  "safe": false,
  "reason": "Conteúdo bloqueado: apostas"
}
```

---

##  Resultados Esperados

* Redução de riscos de invasão
* Proteção de dados sensíveis
* Controle eficiente de acesso
* Ambiente digital mais seguro
* Auxílio no combate à desinformação

---

##  Melhorias Futuras

* Integração com IA real (Machine Learning)
* Reconhecimento facial via câmera
* Dashboard web interativo (React)
* Sistema de notificações em tempo real
* Integração com banco de dados real (MongoDB/PostgreSQL)

---

##  Autor

**Davi Thomas Ribeiro e Silva**
CEUB – Engenharia da Computação

---

##  Licença

Este projeto é acadêmico e possui fins educacionais.
