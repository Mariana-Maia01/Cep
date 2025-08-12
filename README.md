# Busca CEP - Java + API ViaCEP

Este projeto é um programa em **Java** que busca informações de endereço a partir de um **CEP** utilizando a **API ViaCEP**.  
Após a consulta, o resultado é exibido no console e também **salvo automaticamente em um arquivo `.json`** formatado.

---

## Funcionalidades

-  Busca endereço a partir de um CEP válido.
-  Consome dados da API gratuita [ViaCEP](https://viacep.com.br).
-  Retorna:
  - CEP
  - Logradouro
  - Complemento
  - Bairro
  - Cidade
  - Estado
-  Salva os dados retornados em um arquivo JSON com formatação bonita.
-  Utiliza recursos modernos do Java, como **records**.

---

## 🛠️ Tecnologias utilizadas

- **Java 17+** (ou compatível)
- **Gson** para conversão de objetos Java para JSON
- **HttpClient** do Java para requisições HTTP
- **FileWriter** para gravação de arquivos
