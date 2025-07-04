# 🖥️ Projeto TCC - Site Administrativo Geral e Site Administrativo das UBS

Este repositório contém o código do site administrativo do meu projeto TCC. O site tem como objetivo gerenciar os dados do aplicativo [Link do repositório do Aplicativo](https://github.com/Gabidanety/Projeto-TCC-FarmaSUS-Mobile)
 que mostra as UBSs (Unidades Básicas de Saúde) mais próximas com os medicamentos que deseja. O projeto é composto por dois sites administrativos, ambos interligados a um único projeto Laravel e com dois bancos de dados distintos.


## Descrição

### Site 1: **Administração Geral** (Ministério da Saúde)
Este site é responsável pelo cadastro de medicamentos, UBSs, clientes, entre outros dados essenciais para o funcionamento do sistema. Ele permite:
- Cadastro, edição, desativação e visualização dos dados.
- Visualização de gráficos e tabelas.
- Filtros e barras de pesquisa para facilitar a busca de dados.
- Exibição de atividades recentes.

### Site 2: **Administração das Farmácias UBS**
Este site é dedicado à administração das farmácias dentro das UBSs. Ele permite:
- Visualização de estoque.
- Realização de entradas e saídas de medicamentos.
- Cadastro de medicamentos já existentes no sistema.
- Utilização de filtros e barras de pesquisa.
- Exibição do status do estoque e das atividades recentes.

Ambos os sites são interligados e servem de apoio ao aplicativo, permitindo que os usuários vejam quais medicamentos estão disponíveis nas UBSs mais próximas.

### Funcionalidades
- Cadastro de medicamentos, UBSs, clientes e funcionários.
- Visualização e edição de dados.
- Sistema de filtro e pesquisa avançada.
- Visualização de gráficos e atividades recentes.
- Cadastro de farmácias das UBSs, com controle de estoque.

### Tecnologias Utilizadas
- **Backend**: Laravel (PHP)
- **Frontend**: HTML, CSS, JavaScript
- **Banco de Dados**: MySQL
- **API**: Postman para integração com o aplicativo
- **Servidor**: Ngrok para execução local

### Banco de Dados
O projeto utiliza dois bancos de dados MySQL:  
- **bdAdminGeral**: Contém dados gerais de medicamentos, UBSs, clientes, etc.
- **bdfarmaciaUBS**: Contém dados específicos sobre farmácias e movimentações de estoque.

Após o cadastro de uma UBS no primeiro site, um e-mail é enviado para a UBS com o link do site administrativo correspondente, permitindo que a UBS tenha acesso apenas aos seus próprios dados. Além disso, as entradas e saídas de medicamentos no segundo site devem utilizar os medicamentos já cadastrados no primeiro banco.

## Imagens dos Sites
Site azul é o AdmGeral, Site Verde é o AdmUbs.
</br>
![Screenshot do Site Administrativo 1](ImagenSite/1.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/9.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/10.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/11.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/12.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/13.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/14.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/15.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/16.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/17.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/18.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/19.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/20.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/2.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/3.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/4.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/21.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/22.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/23.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/24.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/25.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/5.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/6.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/7.jpg)
![Screenshot do Site Administrativo 1](ImagenSite/8.jpg)

