# LoginAPI

# EndPoints

- Endpoint de Login
- Endpoint de trocar senha
- Endpoint de envio de email
- Endpoint de Logout
- Endpoint de Resgisto

# Pré Requisitos para funcionar

- PostgreSQL(Login e senha devem ser alterados em application.properties para funcionar)
- SpringBoot
- JDK 18
- Necessário rodar este comando sql para que seja possível a implementação dos cargos:

```
INSERT INTO cargo("name") VALUES('CARGO_USUARIO');
INSERT INTO cargo("name") VALUES('CARGO_MODERADOR');
INSERT INTO cargo("name") VALUES('CARGO_ADMIN'); 
```

## Como acessar as endpoints no postman ##

<details>
<summary> Registro de Usuario </summary>

![image](https://i.ibb.co/PGX3NZN/Registro.png)

</details>

---

<details>
<summary> Login de Usuario </summary>

![image](https://i.ibb.co/BNB8Nyn/Login.png)

</details>

---

<details>
<summary> Esqueci Senha </summary>

![image](https://i.ibb.co/Yp89JS0/Email.png)

</details>

---

<details>
<summary> Resetar Senha </summary>

![image](https://i.ibb.co/FJt3Z07/Senha.png)

</details>

---




