# INICIALIZAÇÃO
npm init -y

npm add express

**RODAR O SERVIDOR**

node server.js

# Todos
1. **GET**:
   - `http://localhost:3000/clients`

# Pessoas específicas 
2. **GET**:
   - `http://localhost:3000/clients/:id`

3. **POST /clients**:
   - `http://localhost:3000/clients`
     {
       "nome": "Pesso Nova",
       "email": "pessoa@exemplo.com"
     }

4. **PUT /clients/:id**:
   - `http://localhost:3000/clients/:id`
     {
       "nome": "Pessoa Atualizada"
     }

5. **DELETE /clients/:id**:
   - `http://localhost:3000/clients/:id`
