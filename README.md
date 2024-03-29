# Tecnicas_Programacao_I
Módulo 5 - Vem ser Tech - ADA

# Trabalho conclusão de módulo

Descrição do Projeto:

# Projeto de Técnicas de Programação I

Você trabalha em uma consultoria de dados que foi contratada para realizar a distribuição de materiais didáticos nas escolas da cidade do Rio de Janeiro. Sua missão é realizar tratamentos nos dados de acordo com as normas de padrão definidas pelo cliente e encontrar qual a melhor rota que um caminhão deve realizar para entregar os materiais didáticos de forma a otimizar o seu percurso. 

Para esse projeto você recebeu três arquivos:
- escolas.csv: contém os dados das escolas
- subprefeituras.csv: contém dados de quais bairros pertem a cada subprefeitura
- material_didatico.csv: contém a quantidade de material didático que cada escola deve receber

Como produto final, você deve entregar:
- um arquivo csv no as linhas já estarão ordenas de acordo com a rota a ser seguida. Além disso, os dados devem estar no padrão especificado abaixo e contendo as seguintes colunas: id da escola, nome da escola, tipo da escola (EM, CIEP ou colégio), logradouro da entrega, número, bairro, subprefeitura, latitude, longitude e quantidade de material didático que deve ser entregue. O logradouro da escola deve estar em uma coluna diferente do número;
- um arquivo csv com a quantidade total de material escolar por subprefeitura para que sejam contabilizados os custos por subprefeitura

Como padrão dos dados, considere:
- nome das colunas em snake_case
- strings não devem conter acentos
- todas as strings devem estar em maiúsculo
- padronização do nome dos logradouros sem abreviação (Ex: R. deve estar como Rua)
- latitude e longitude devem conter apenas 5 casas decimais
- os ids da escola devem todos ser strings com 3 caracteres (Ex: '024')

Desafio:

Entregar um plot com a representação da melhor rota que você encontrou, por exemplo:
<img src="rota.png"  width="70%" height="40%">

Obs: O otimizador não é a parte mais importante do projeto. Foque no tratamento dos dados e se preciso, pode reduzir a quantidade de escolas para rodar o otimizador.

