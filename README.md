# 🖥️ Projeto TCC - Site Administrativo Geral e Site Administrativo das UBS

Este repositório contém o código do **site administrativo** do projeto TCC (FarmaSUS).  
O sistema tem como objetivo **gerenciar os dados do aplicativo** [FarmaSUS](https://github.com/du4ards09/FarmaSUS-Mobile), que exibe as UBSs (Unidades Básicas de Saúde) mais próximas com os medicamentos disponíveis.

O projeto é composto por **dois sites administrativos**, ambos interligados a um único projeto Laravel e conectados a **dois bancos de dados distintos**.

---

## 📌 Descrição

### 🔷 Site 1: Administração Geral (Ministério da Saúde)

Responsável pelo gerenciamento geral do sistema:

- Cadastro, edição, desativação e visualização de dados (medicamentos, UBSs, clientes, etc).
- Visualização de **gráficos** e **tabelas**.
- Filtros e **barras de pesquisa** para facilitar buscas.
- Exibição de **atividades recentes**.

### 🟩 Site 2: Administração das Farmácias UBS

Voltado para o controle das farmácias dentro das UBSs:

- Visualização de **estoque**.
- **Entradas e saídas de medicamentos**.
- Cadastro de medicamentos já existentes no sistema.
- Filtros, pesquisa e exibição do **status do estoque** e atividades recentes.

Ambos os sites se conectam ao aplicativo, permitindo que os usuários visualizem a disponibilidade de medicamentos nas UBSs mais próximas.

---

## ⚙️ Funcionalidades

- Cadastro e gerenciamento de medicamentos, UBSs, clientes e funcionários.
- Sistema de filtros e **pesquisa avançada**.
- Visualização de **gráficos** e **atividades recentes**.
- Cadastro de farmácias das UBSs com **controle de estoque em tempo real**.

---

## 🛠️ Tecnologias Utilizadas

- **Backend:** Laravel (PHP)
- **Frontend:** HTML, CSS, JavaScript
- **Banco de Dados:** MySQL
- **API:** Postman (para integração com o app)
- **Servidor:** Ngrok (para execução local)

---

## 🗃️ Banco de Dados

O sistema utiliza dois bancos de dados distintos em MySQL:

- `bdAdminGeral`: armazena dados gerais como medicamentos, UBSs e clientes.
- `bdFarmaciaUBS`: gerencia estoques e movimentações internas de medicamentos.

> Após o cadastro de uma UBS no site geral, um e-mail é enviado com o link do painel da UBS, permitindo o acesso apenas aos seus próprios dados.  
> O estoque da UBS depende dos medicamentos previamente cadastrados no banco principal.

---

## 📸 Imagens dos Sites

### 🟦 AdmGeral (Administração Geral)

<p align="center">
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0002.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0003.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/Imagem%20do%20WhatsApp%20de%202025-07-04%20%C3%A0(s)%2000.47.22_b3f5edb5.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/Imagem%20do%20WhatsApp%20de%202025-07-04%20%C3%A0(s)%2000.47.42_166cd5fa.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0004.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0005.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0006.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0021.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0022.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0023.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0027.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0031.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0033.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0034.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0038.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0041.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0042.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0043.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0047.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0050.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0051.jpg" height="180" />
  <img src="https://github.com/du4ards09/FarmaSUS-Desktop/blob/main/Imagens/IMG-20250704-WA0055.jpg" height="180" />
</p>
---

### 🟩 AdmFarmácia (Administração das Farmácias)

<p align="center">
  <img src="./imagens/admin8.png" height="180" />
  <img src="./imagens/admin9.png" height="180" />
  <img src="./imagens/admin10.png" height="180" />
  <br>
  <img src="./imagens/admin11.png" height="180" />
  <img src="./imagens/admin12.png" height="180" />
  <img src="./imagens/admin13.png" height="180" />
  <br>
  <img src="./imagens/admin14.png" height="180" />
</p>

## 📬 Contato

Caso tenha dúvidas ou sugestões, entre em contato com a equipe:  
📧 `contato@glow.com` (substituir pelo real, se desejar)

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais informações.
