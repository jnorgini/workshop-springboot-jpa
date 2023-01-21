# Web services com Spring Boot e JPA / Hibernate 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/jnorgini/workshop-springboot-jpa/blob/main/licence) 

# Objetivos
1. Criação do projeto Spring Boot Java
2. Implementação do modelo de domínio
3. Estruturação das camadas lógicas: resource, service, repository
4. Configuração do banco de dados de teste (H2)
5. Povoar o banco de dados
6. CRUD - Create, Retrieve, Update, Delete
7. Tratamento de exceções 

## Domain Model
<img src="https://user-images.githubusercontent.com/114461353/213862744-fbe74065-90af-4f16-a0c0-a8228116b6f7.png" alt="java" width="900" height="400"/> </a> 


## Domain Instance 
<img src="https://user-images.githubusercontent.com/114461353/213862751-3d8e7111-20eb-47c5-b88c-a387020cc168.png" alt="java" width="900" height="400"/> </a> 


## Logical Layers 
<img src="https://user-images.githubusercontent.com/114461353/213861344-e8765c95-9004-443e-b3b3-f83da23c126a.png" alt="java" width="600" height="350"/> </a> 


# Tecnologias utilizadas

<img src="https://user-images.githubusercontent.com/114461353/213862777-ecf1f682-fd00-4f59-ac5b-e270894c13d0.png" alt="java" width="600" height="220"/> </a> 


# Como executar o projeto

#### Pré-requisitos: Git Bash | Spring Tool Suite 4 | Postman


```bash
# clonar repositório
git clone https://github.com/jnorgini/workshop-springboot-jpa

# abrir o Spring Tool Suite 4
1. ir em file
2. Open Projects from File System
3. Directory / localizar repositório clonado / selecionar a pasta workshop-springboot-jpa
4. Finish

# executar o projeto no STS
📁 src/main/java
 📂 com.educandoweb.course
  ➡️ CourseApplication.java / Run As / Spring Boot App

# testes e modificações no banco de dados
⌨️ Navegador http://localhost:8080/h2-console/ ➡️ Connect 
🛠️ Postman http://localhost:8080/categories ou /orders ou /products ou /users
Obs: também é possível verificar as tabelas especificando o id. Exemplo: products/5
```

# Autoria

Juliana Norgini

https://www.linkedin.com/in/juliana-norgini
