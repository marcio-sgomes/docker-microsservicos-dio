# Projeto: Docker - Utilização Prática no Cenário de Microsserviços

Repositório dedicado à entrega do desafio prático da DIO focado na utilização do **Docker**, gestão de volumes, persistência de dados, criação de microsserviços e orquestração de containers com **Docker Swarm** e **NGINX**.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Docker** (Containers, Imagens e Dockerfiles)
* **Docker Compose**
* **Docker Swarm** (Orquestração de clusters)
* **MySQL** (Base de dados em container)
* **NGINX** (Proxy reverso e balanceamento de carga)
* **Linux / Bash**

---

## 📋 Etapas Desenvolvidas no Projeto

1. **Configuração do Primeiro Container:**
   * Definição e execução de containers básicos para entender o ciclo de vida e a gestão de portas.
2. **Criação e Gestão de Container MySQL:**
   * Subida de uma instância do MySQL em container, configurando variáveis de ambiente (password de root, criação de base de dados).
3. **Persistência de Dados (Volumes):**
   * Mapeamento de volumes Docker e bind mounts para garantir que os dados da base de dados persistissem mesmo após a remoção ou reinicialização do container.
4. **Orquestração com Docker Swarm:**
   * Inicialização do modo Swarm na máquina (*Swarm Mode*).
   * Criação de serviços distribuídos no cluster e replicação de instâncias para alta disponibilidade.
5. **Proxy Reverso com NGINX:**
   * Configuração do NGINX para atuar como proxy reverso, direcionando o tráfego de forma eficiente entre os diferentes microsserviços criados no cluster.
6. **Stress Test e Monitorização:**
   * Testes de carga e stress nos containers para avaliar o comportamento do cluster e dos serviços sob pressão.

---

## 🚀 Como Executar o Projeto

1. Clona este repositório para a tua máquina:
   ```bash
   git clone [https://github.com/o-teu-utilizador/o-teu-repositorio.git](https://github.com/o-teu-utilizador/o-teu-repositorio.git)
