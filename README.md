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

# Tecnologias utilizadas

<img src="https://user-images.githubusercontent.com/114461353/213862777-ecf1f682-fd00-4f59-ac5b-e270894c13d0.png" alt="java" width="500" height="200"/> </a> 

## Domain Model
<img src="https://user-images.githubusercontent.com/114461353/213862744-fbe74065-90af-4f16-a0c0-a8228116b6f7.png" alt="java" width="800" height="300"/> </a> 


## Domain Instance 
<img src="https://user-images.githubusercontent.com/114461353/213862751-3d8e7111-20eb-47c5-b88c-a387020cc168.png" alt="java" width="800" height="450"/> </a> 


## Logical Layers 
<img src="https://user-images.githubusercontent.com/114461353/213861344-e8765c95-9004-443e-b3b3-f83da23c126a.png" alt="java" width="600" height="400"/> </a> 

# H2
<img src="https://user-images.githubusercontent.com/114461353/213884153-cd474f81-ecdd-45a3-b514-2ef7a1422055.png" alt="java" width="400" height="400"/> </a>
<img src="https://user-images.githubusercontent.com/114461353/213884163-7ef20b36-1f60-4e6d-a5ee-fd64371dbb99.png" alt="java" width="400" height="400"/> </a> 

# Postman 
<img src="https://user-images.githubusercontent.com/114461353/213884177-d8d2ba4d-d468-4d50-8856-dbefb75d617c.png" alt="java" width="800" height="500"/> </a> 



# Como executar o projeto

#### 🛑 Pré-requistos

- [x] Git Bash
- [x] Spring Tool Suite 4
- [x] Postman


```bash
# clonar repositório
git clone https://github.com/jnorgini/workshop-springboot-jpa

# abrir o Spring Tool Suite 4
1. ir em file
2. Open Projects from File System
3. Directory / localizar o repositório clonado / selecionar a pasta workshop-springboot-jpa
4. Finish

# executar o projeto no STS
📁 src/main/java
 📂 com.educandoweb.course
  ➡️ CourseApplication.java / Run As / Spring Boot App

# testes e modificações no banco de dados
⌨️ Navegador http://localhost:8080/h2-console/ ➡️ Connect 
🛠️ Postman http://localhost:8080/categories ou /orders ou /products ou /users
Obs: também é possível manipular as tabelas especificando o id. Exemplo: /products/5
```

## Autoria

Juliana Norgini

 ## Contato
 
 [![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-6633cc?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/juliana-norgini)](https://www.linkedin.com/in/juliana-norgini)
[![Gmail Badge](https://img.shields.io/badge/-jnorgini@gmail.com-6633cc?style=flat-square&logo=Gmail&logoColor=white&link=mailto:jnorgini@gmail.com)](mailto:jnorgini@gmail.com)
