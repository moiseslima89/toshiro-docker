# 🐳 Desafio Toshiro Shibakita - Microsserviços com Docker

Este projeto é uma implementação prática baseada no curso "**Docker: Utilização prática no cenário de Microsserviços**", utilizando a história de **Toshiro Shibakita** como inspiração. O objetivo é criar uma estrutura com múltiplos microsserviços utilizando **Docker** e **Docker Compose**.

---

## 📦 Tecnologias Utilizadas

- **Docker**
- **Docker Compose**
- **Node.js** (serviços)
- **Nginx** (gateway reverso)
- **MongoDB** (banco de dados)
- **Redis** (cache)
- **Linux** (comandos e terminal)

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
- Docker instalado
- Docker Compose instalado

### Passos:

```bash
# Clone este repositório (se ainda não fez)
git clone https://github.com/seu-usuario/toshiro-docker.git
cd toshiro-docker

# Suba os containers
docker-compose up --build
```

A aplicação será exposta em:  
📍 **http://localhost:8080**

---

## 🗂️ Estrutura do Projeto

```
toshiro-docker/
├── nginx/               # Configuração do proxy reverso
├── service1/            # Primeiro microsserviço
├── service2/            # Segundo microsserviço
├── docker-compose.yml   # Orquestração dos containers
├── .env                 # Variáveis de ambiente
└── README.md            # Documentação do projeto
```

---

## 📌 Melhorias Possíveis

- Adicionar CI/CD com GitHub Actions
- Implementar autenticação JWT entre serviços
- Deploy com Docker Swarm ou AWS ECS
- Monitoramento com Prometheus + Grafana

---

## 📚 Base de Referência

- Curso de Docker e Microsserviços por [Denilson Bonatti](https://github.com/denilsonbonatti)
- Projeto original: [toshiro-shibakita](https://github.com/denilsonbonatti/toshiro-shibakita)

---

## ✍️ Autor do Repositório

**Seu Nome Aqui**  
🔗 [https://github.com/moiseslima89](https://github.com/moiseslima89)

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License**.  
Sinta-se à vontade para usar, estudar e adaptar!
