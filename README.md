# metas-IncentivaCursos
Metas para Funcionarios


Esse código HTML é uma página da web que contém uma interface para calcular metas e resultados para uma "Consultoria de Carreira Interna". Vamos analisar os elementos principais do código:

1. **Meta Tags**: As meta tags são usadas para fornecer informações sobre a página para os navegadores e mecanismos de busca, como a codificação do caractere, a versão do IE a ser usada e a escala de exibição em dispositivos móveis.

2. **Título**: O título da página é definido como "METAS ESCOLA", que provavelmente representa o propósito da página.

3. **Barra de Navegação**: Uma barra de navegação é criada como uma lista não ordenada (ul) contendo quatro itens de lista (li) que são links para diferentes seções do site.

4. **Conteúdo Principal**: O conteúdo principal da página é dividido em duas seções principais:
   - **menuPrimario**: Contém uma seção de entrada de dados chamada "INCENTIVA CURSOS" e duas tabelas.
   - **menuSecundario**: Contém campos de entrada para a receita, dias, quantidade de atendimentos e quantidade total.
   - **table-container**: Contém duas tabelas: uma com o id "dateTable" e outra com o id "secondTable".

5. **Script**: O script contém um código JavaScript que é responsável por calcular os resultados com base nos dados fornecidos nos campos de entrada e preencher as tabelas com os resultados.

6. **calculateResult()**: Essa função é acionada sempre que um dos campos de entrada é modificado. Ela obtém os valores dos campos de entrada, calcula os resultados para cada dia e preenche as tabelas com os valores resultantes.

7. **Tabelas**: As tabelas têm cabeçalhos e corpos, mas inicialmente, os corpos estão vazios. Quando a função calculateResult() é chamada, ela preenche o corpo das tabelas com os resultados calculados para cada dia.

Essa página permite que o usuário insira os dados da "Consultoria de Carreira Interna", como a receita, dias trabalhados, quantidade de atendimentos e quantidade total, e, em seguida, exibe os resultados calculados com base nessas informações nas tabelas.

Observação: O código também faz uso de classes CSS para estilizar a página, mas o arquivo CSS externo não está incluído no código fornecido. Portanto, os estilos não estão visíveis aqui, mas eles são essenciais para a aparência final da página.

Lembre-se de que, em geral, esse código precisa ser executado em um servidor web para que o JavaScript funcione corretamente e os estilos sejam aplicados corretamente.
