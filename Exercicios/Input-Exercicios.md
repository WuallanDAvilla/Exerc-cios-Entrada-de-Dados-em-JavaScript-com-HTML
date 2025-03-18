## Exercícios: Entrada de Dados em JavaScript com HTML

**Instruções:** Crie um arquivo HTML para cada exercício. Inclua o HTML, CSS (opcional para estilização) e JavaScript necessários para que o exercício funcione corretamente. Valide sempre os dados inseridos pelo usuário!

**Nível 1: Básico**

1.  **Calculadora Simples:**

    *   Crie um formulário com dois campos de entrada de texto para números e um menu suspenso (`<select>`) com as opções: "Somar", "Subtrair", "Multiplicar", "Dividir".
    *   Ao clicar em um botão "Calcular", realize a operação selecionada com os dois números fornecidos e exiba o resultado em um elemento `<p>`.
    *   **Validação:** Verifique se os campos de entrada estão preenchidos com números válidos antes de realizar a operação.


2.  **Conversor de Temperatura:**

    *   Crie um formulário com um campo de entrada de texto para a temperatura, um menu suspenso com as opções "Celsius para Fahrenheit" e "Fahrenheit para Celsius", e um botão "Converter".
    *   Realize a conversão de temperatura com base na opção selecionada e exiba o resultado.
    *   **Validação:** Verifique se o campo de entrada é um número válido.

  

3.  **Validador de Email:**

    *   Crie um campo de texto para o usuário inserir um endereço de e-mail e um botão "Validar".
    *   Use JavaScript para verificar se o endereço de e-mail inserido é válido (use uma expressão regular básica).
    *   Exiba "Email válido" ou "Email inválido" em um elemento `<p>`.


**Nível 2: Intermediário**

4.  **Lista de Tarefas:**

    *   Crie um campo de texto para o usuário inserir uma nova tarefa e um botão "Adicionar".
    *   Quando o botão "Adicionar" for clicado, adicione a tarefa a uma lista não ordenada (`<ul>`).
    *   Cada item da lista deve ter um botão "Remover" que, ao ser clicado, remove a tarefa da lista.

  

5.  **Formulário de Feedback:**

    *   Crie um formulário com os seguintes campos:
        *   Nome (texto)
        *   Email (email)
        *   Avaliação (radio buttons: "Excelente", "Bom", "Regular", "Ruim")
        *   Comentários (textarea)
    *   Ao enviar o formulário, exiba um resumo do feedback em um elemento `<div>`, mostrando os valores inseridos pelo usuário.
    *   **Validação:**
        *   Verifique se o nome e o email estão preenchidos.
        *   Verifique se o email tem um formato válido.
        *   Verifique se uma avaliação foi selecionada.

  

**Nível 3: Avançado**

6.  **Calculadora de IMC (com Gráfico):**

    *   Crie um formulário com campos para altura (metros) e peso (kg).
    *   Ao calcular o IMC, exiba o resultado e uma mensagem indicando a faixa de peso (Abaixo do Peso, Peso Normal, Sobrepeso, Obesidade).
    *   Use um elemento `<canvas>` para criar um gráfico simples que mostre a posição do IMC do usuário em relação às faixas de peso.

7.  **Sistema de Cadastro com Armazenamento Local:**

    *   Crie um formulário de cadastro com campos para nome, email, senha e confirmação de senha.
    *   Valide se as senhas coincidem e se o email tem um formato válido.
    *   Ao cadastrar, armazene os dados do usuário no localStorage do navegador.
    *   Crie uma página de login que permita ao usuário inserir seu email e senha.
    *   Verifique se as credenciais correspondem às informações armazenadas no localStorage e redirecione para uma página de "Boas-vindas" se o login for bem-sucedido.




**Capacidades Técnicas:**

*   **3. Interpretar os requisitos do sistema, tendo em vista a elaboração dos componentes em ambiente mobile:** Os exercícios exigem interpretar o que se espera que o formulário faça (calcular, converter, validar, etc.) e traduzir isso em elementos HTML e lógica JavaScript.
*   **4. Definir os elementos de entrada, processamento e saída para a codificação das funcionalidades mobile:** Os exercícios focam em definir quais elementos HTML serão usados para *entrada* (campos de texto, botões de rádio), qual código JavaScript irá *processar* esses dados, e onde a *saída* (resultado, mensagem de erro) será exibida.
*   **5. Projetar interfaces para dispositivos móveis:** Embora os exercícios não se aprofundem no design visual, eles requerem projetar a estrutura básica da interface do usuário (quais campos, botões, mensagens estarão presentes).
*   **6. Implementar o código respeitando as características da linguagem na plataforma mobile:** Os exercícios envolvem escrever código JavaScript que interage com o DOM (Document Object Model) dos elementos HTML, que é a base para criar interfaces web interativas em dispositivos móveis.
*   **8. Realizar a integração de dispositivos móveis aos serviços web:** Embora os exercícios em si não integrem serviços web, a capacidade de coletar e manipular dados do usuário é um passo fundamental para depois enviar esses dados para um servidor web.
*   **9. Realizar os testes unitários nos componentes do sistema mobile:** Validar os dados inseridos pelo usuário pode ser visto como um tipo de teste unitário básico, garantindo que o código reage corretamente a diferentes entradas.

**Capacidades Socioemocionais:**

*   **1. Demonstrar autogestão:** Ao trabalhar nos exercícios, os alunos precisam gerenciar seu tempo, organizar seu código e seguir as instruções.
*   **2. Demonstrar pensamento analítico:** Os exercícios exigem analisar o problema (o que precisa ser feito com os dados inseridos), identificar os passos necessários para resolver o problema e implementar a solução de forma lógica.
*   **4. Demonstrar autonomia:** Idealmente, os alunos devem tentar resolver os exercícios por conta própria, buscando recursos e experimentando diferentes soluções.

**Justificativa:**

Os exercícios focam na interação do usuário com a interface através de formulários e elementos de entrada. A lógica JavaScript é usada para capturar, validar e processar esses dados, e os resultados são exibidos na página. Essa é uma habilidade fundamental para o desenvolvimento mobile, onde a interação com o usuário é crucial. As capacidades técnicas listadas refletem diretamente as habilidades necessárias para criar essas interfaces interativas e manipular os dados inseridos pelo usuário. As capacidades socioemocionais são desenvolvidas ao enfrentar os desafios dos exercícios e buscar soluções de forma independente e organizada.


