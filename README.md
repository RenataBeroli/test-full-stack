# DESAFIO PARA DESENVOLVEDOR(A) FULL STACK

Powered by
[![N|Solid](https://static.wixstatic.com/media/ef1fe4_150ad6ed3f6f4c21883b3d68db773c9c~mv2.png/v1/fill/w_181,h_69,al_c,q_85,usm_0.66_1.00_0.01/biome-hub-1_cor.webp)](https://www.biome-hub.com/)

**Seguem as instruções do teste para a posição de Desenvolvedor(a) Full Stack na BiomeHub Biotechnologies.**

- O deadline para entrega é dia 7 dias após recebimento deste e-mail. 
- O objetivo do teste é analisar sua familiaridade com o Django, Django Rest Framework (DRF), Vue.js, SCSS, HTML e práticas de programação.
<p>&nbsp;</p>

> **Lembre-se: o teste de composto por vários módulos e várias possibilidades de avaliação, então não deixe de enviar por não ter concluído completamente.**
<p>&nbsp;</p>

### Requisitos

- Deve ser construída uma aplicação para listar e editar clientes utilizando um framework da sua preferencia (de preferencia Vue.js) e outra em Django 3+.

- O Frontend deve interagir com o Backend por meio de uma API REST em Django, para exibir e permitir editar uma lista de clientes.

**Backend:**

- **RF01** - Criar endpoint no Backend para o Frontend consultar ( GET ) deve ser como esse exemplo: 
http://private-92a969-processoseletivo1.apiary-mock.com/customers ;
- **RF02** - A população dos dados para esse endpoint deve ser feita manualmente via SQL ou ORM.
- **RF03** - A listagem deve possuir paginação server side a cada 10 clientes;
- **RF08** - Ao clicar no botão de “salvar” na tela de edição os dados atualizados do cliente devem ser enviados ( PUT ) para um endpoint de edição do cliente. Conforme este exemplo:
“https://private-92a969-processoseletivo1.apiary-mock.com/customers/{id_do_cliente}/”;

**Frontend:**

- **RF04** - A listagem deve ser ordenável e filtrável por Id, nome, idade e cidade;
- **RF05** - Deve haver um botão de “editar” cliente em cada linha da tabela;
- **RF06** - Ao clicar no botão de “editar” o usuário deve ser redirecionado para uma outra rota com os dados do cliente em formato editável;
- **RF07** - Deve ser adicionado na tela de edição um botão de “salvar” e um de “cancelar”;
- **RF09** - Sendo que, depois do retorno da requisição ( PUT ) o usuário deve ser redirecionado para listagem e a aplicação deve apresentar a ele uma notificação dizendo “Cliente {nome_do_cliente} atualizado com sucesso!”;

<p>&nbsp;</p>

### Requisitos não funcionais

- **RNF010** - A aplicação deve ser hospedada em algum servidor de sua preferência, podendo ser Python Any Where, Github Pages ou onde você achar melhor;
- **RNF011** - O código fonte deve ser publicado no GitHub e o link deverá ser enviado como
resposta deste e-mail;

### Bônus

- **RF12** - Adicionar um validador reativo no input de idade para tamanho de no mínimo 1 e máximo de 3 números. Este validador só é acionado se o usuário tocar no campo. Caso o usuário digite algum valor que seja errado o botão de salvar deve ficar desabilitado;
- **RNF13** - Adicionar testes nos endpoints;
- **RNF14** - Utilizar docker;
- **RN15** - Gerar um PWA da aplicação.

<p>&nbsp;</p>

**Desejamos sucesso em seu teste desde já! Nos colocamos a disposição para esclarecer quaisquer dúvidas.**
<p>&nbsp;</p>

### Links para auxílio:

- https://www.djangoproject.com/start/
- https://vuejs.org/v2/guide/
- https://www.docker.com/get-started