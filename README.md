# 🛄 Sistema de Cadastro e Controle de Bagagens

## 📌 Descrição
Este projeto é um sistema simples, desenvolvido em **Python**, que simula o acesso e as funcionalidades básicas de um sistema de cadastro de clientes para viagens e controle de limite de bagagens.  
O sistema possui autenticação de usuário e senha, cadastro de clientes e verificação das regras de despacho de bagagem de acordo com a categoria do cliente.

---

## 🚀 Funcionalidades
- **Login** com usuário e senha  
- **Menu interativo** com três opções:
  1. **Cadastro de cliente**: solicita nome, CPF, altura e ano de nascimento, calculando idade e verificando idade mínima (≥ 16 anos).  
  2. **Limite de bagagem**: verifica se o peso da bagagem está dentro do limite permitido para cada tipo de cliente (PREMIUM, GOLD ou REGULAR) e informa se há necessidade de pagamento adicional.  
  3. **Sair** do sistema.  

---

## 🛠 Tecnologias Utilizadas
- **Python 3.x**  

---

## 📂 Estrutura do Código
O código é organizado em:
1. **Autenticação**: valida se o usuário é `ADMIN` e a senha é `123`.
2. **Menu principal**: laço `while` para apresentar e executar as opções.
3. **Cadastro de clientes**: coleta e exibe os dados formatados.
4. **Verificação de bagagens**: lógica condicional para cada tipo de cliente.

---

## 📥 Como Executar
1. Instale o Python 3 em sua máquina ([Download Python](https://www.python.org/downloads/)).
2. Salve o código em um arquivo com o nome, por exemplo:
   ```
   sistema_viagem.py
   ```
3. No terminal ou prompt de comando, execute:
   ```bash
   python sistema_viagem.py
   ```

---

## 📋 Exemplo de Uso
```
Informe o usuário que deseja acessar o sistema: ADMIN
Informe a senha: 123
Acesso autorizado!

1 - Realizar cadastro
2 - Limite de bagagem
3 - Sair
Digite a opção desejada: 1
Cadastro de cliente para viagem
Por favor, informe o seu nome completo: João Silva
Por favor, informe o seu CPF: 12345678900
Por favor, informe a sua altura em cm: 180
Por favor, informe o ano de nascimento: 1990
	NOME: João Silva
	CPF: 12345678900
	ALTURA: 180cm
	IDADE: 35
	TEM IDADE MINIMA PARA VIAJAR: True
```

---

## 👤 Autor
- Joabe Bragança 

