# Especificação do Projeto

## Perfis de Usuários

[Enumere e faça o detalhamento dos perfis de usuários. Utilize o modelo de tabela abaixo para sintetizá-los.]

<table>
<tbody>
<tr align=center>
<th colspan="2">Perfil 1: Vendedores de skins </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Usuários interessados em vender suas skins.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>1. Vender na plataforma de forma segura suas skins;
    2. Uma plataforma de fácil uso e visibilidade de suas skins;
    3. Rapidez no processo de venda e recebimento dos fundos.<td>
</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr align=center>
<th colspan="2">Perfil 2: Compradores de skins </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Usuários interessados em comprar novas skins.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>1. Comprar em uma plataforma de forma segura e confiável suas skins;
    2. Uma plataforma de fácil uso e visibilidade de suas skins;
    3. Agilidade no momento da compra e no prazo de recebimento da skin comprada.</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr align=center>
<th colspan="2">Perfil 3: Jogadores de e-sports</th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Usuários que jogam e gostam de e-sports.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>1. Navegar no site para encontrar skins do seu jogo preferido;
    2. Identificar possíveis skins para compra;
    3. Análisar preços de venda e compra de skins;
    4. Facilidade no processo de navegação e busca das skins do seu jogo preferido. </td>
</tr>
</tbody>
</table>


## Histórias de Usuários

Com base na análise dos usuários que irãoa acessar o site, foram identificadas as seguintes histórias de usuários:

|EU COMO... `Usuário`   | QUERO/PRECISO ... `Funcionalidade`       |PARA ... `Motivo`                 |
|--------------------|---------------------------------------------|----------------------------------|
|Vendedor de skins   | Um site seguro e confiável para vender as skins. | Se sentir mais seguro em realizar transações de venda.|
|Vendedor de skins   | Um site para navegar e análisar os preços das skins. | Auxiliar o usuário a definir um preço modelo a se vender suas skins.|
|Vendedor de skins   | Agilidade em receber os fundos após uma venda. | Garantir que os fundos do usuário esta disponível para ele o mais breve possível. |
|Comprador de skins  | Um site seguro e confiável para comprar as skins. | Se sentir mais confortável em realizar transações de compra e receber suas skins compradas.|
|Comprador de skins  | Facilidade em buscar suas skins e comparar preços para compra. | Garantir que o usuário consiga comparar preços e escolher o melhor preço para compra da skin desejada.|
|Comprador de skins  | Garantir a transferência das skins comprada para o inventário do usuário de forma rápida | Permitir que o usuário receba a skin comprada o mais breve possível. |
|Jogadores de e-sports   | Garantir uma plataforma de livre acesso para consultas. | Permitir que os usuários caveguem no site para localizar e ver skins do seu jogo preferido. |
|Jogadores de e-sports   | Otimizar a navegação de busca e vizsualização das skins. | Disponibilizar fácil acesso e busca de skins. |
|Todos os usuários   | Garantir uma fácil e ágil navegação pelo site.  | Dar um conforto de uma plataforma simples e rápida para busca e navegação. |
|Todos os usuários   | Permitir que os usuários comparem preços de skins listadas para venda. | Permitir que os usuários possam comparar preços antes de realizar uma compra/venda de skins. |

## Requisitos do Projeto

[Com base nas Histórias de Usuários, enumere os requisitos da solução. Lembre-se que cada requisito deve corresponder a uma, e somente uma, característica alvo da solução. Além disso, certifique-se de que todos os aspectos capturados nas Histórias de Usuário foram cobertos.]

### Requisitos Funcionais

[Utilize o modelo de tabela abaixo para apresentar os requisitos funcionais]

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-01| A aplicação deve permitir ao usuário cadastrar uma conta.   | ALTA | 
|RF-02| A aplicação deve permitir ao usuário fazer o login da sua conta.   | ALTA | 
|RF-03| A aplicação deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário localizar/buscar skins.    | ALTA |
|RF-04| A aplicação deve permitir ao usuário fazer uma venda de sua skins, caso esteja logado em sua conta.    | ALTA |
|RF-05| A aplicação deve permitir ao vendedor receber seus fundos após realização de uma venda.  | ALTA |
|RF-06| A aplicação deve permitir ao comprador receber suas skins compradas de forma ágil.  | ALTA |
|RF-07| A aplicação deve permitir ao comprador ter um histórico de compras.  | ALTA |
|RF-08| A aplicação deve permitir aos usuários logados uma segurança no momento de efetuar transações.  | ALTA |
|RF-09| A aplicação deve apresentar ao usuário todas suas skins que estão sendo vendidas e o valor.  | ALTA |
|RF-10| A plataforma deve permitir ao usuário visualizar as informações sobre a skins.    | MÉDIA |
|RF-11| A plataforma deve permitir ao usuário, mesmo sem logar em sua conta, buscar suas skins de forma fácil.   | MÉDIA |
|RF-12| A plataforma deve permitir ao usuário verificar as informações registradas no cadastro na página Perfil, após fazer seu login.  | MÉDIA |
|RF-13| A aplicação deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário localizar a skin desejada para compra.  | MÉDIA |
|RF-14| A aplicação deve permitir ao usuário realizar a compra/venda de skins.  | ALTA |
|RF-15| A aplicação deve solicitar dados de confirmação de compra/venda para concluir transações.   | ALTA |
|RF-16| A plataforma deve ser de fácil utilização e navegação.   | BAIXA |
|RF-17| A plataforma deve permtiir que os usuários realize contado com o vendedor.   | BAIXA |

**Prioridade: Alta / Média / Baixa. 

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-01| Deve haver autenticação de dois fatores para o login dos usuários.  | ALTA | 
|RNF-02| Todas as transações e dados de usuários devem ser criptografados.  | ALTA | 
|RNF-03| Deve atender às normas de acessibilidade.  | MÉDIA | 
|RNF-04| A aplicação deve ser compatível com os navegadores O site deve ser compatível com os principais navegadores do mercado: Google Chrome, Firefox e Microsoft Edge.  | ALTA |
|RNF-05| O sistema deve permitir a adição de novas funcionalidades ou integrações (como novos métodos de pagamento ou jogos)  | MÉDIA | 
|RNF-06| O sistema deve suportar até X usuários simultâneos sem degradação significativa no desempenho.  | ALTA | 
|RNF-07| O site deve carregar as páginas de forma rápida.  | MÉDIA | 
|RNF-08| Deve ser capaz de lidar com até X transações de skins por minuto em horários de pico.  | ALTA |

**Prioridade: Alta / Média / Baixa. 

