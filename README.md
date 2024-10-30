# Assistente Gastronômico com Step Functions: Criando Experiências Românticas
Neste projeto do curso de engenharia de prompts da plataforma DIO, aprendemos a desenvolver um assistente de delivery utilizando a ferramenta Step Functions.

O que é Step Functions? É uma ferramenta low code que nos permite criar fluxos de trabalho visuais.

Dentre os diversos serviços da AWS temos o Amazon SNS e SQS que são serviços de mensagens, sendo:

SQS: Utilizado para comunicação com clientes, de forma instantânea.

SNS: Para comunicação entre sistemas de diferentes áreas do seu aplicativo e de forma organizada.

# Apresentando o ambiente de trabalho do Step Functions
Amazon States Language: utilizada atrás dos panos, com os blocos que vamos arrastando e construindo nosso fluxo de trabalho, a ferramenta vai gerando o código automaticamente baseado em Json.

Fluxo de trabalho: onde construiremos de fato nosso projeto.

![StepFunctions](https://github.com/user-attachments/assets/70765140-a55d-467e-a7b7-d86a7822164c)

# Importante ressaltar que precisamos dar acesso aos modelos para utilizá-los:
1 - Acesse o Bedrock: na tela inicial, selecione na aba de opções à esquerda clique em model access (Acesso ao modelo).

2 - Habilite os modelos: clique em Enable specific models (Habilitar modelos específicos) no botão amarelo ou no botão ao lado Modify model access (Modificar o acesso ao modelo).

3 - Modelos: selecione os modelos que deseja habilitar e clique em next (próximo).

4 - Confirme a Seleção: revise os modelos habilitados. Em seguida, clique em Submit (enviar) para confirmar.

Com os modelos habilitados, podemos integrá-los ao nosso fluxo de trabalho no Step Functions para gerar sugestões personalizadas de menus e restaurantes.

# Como funciona o projeto do assistente de delivery?
Este projeto tem como objetivo criar um assistente virtual que auxilia os usuários a planejar jantares memoráveis, oferecendo sugestões personalizadas de pratos, bebidas e locais. Ao utilizar a flexibilidade do AWS Step Functions, conseguimos construir um fluxo de trabalho automatizado que, a partir de uma simples entrada (prato escolhido), gera um menu completo, recomendações de bebidas e sugestões de restaurantes.

Imagine que você deseja surpreender seu parceiro(a) com um jantar romântico. Com nosso assistente, você poderá informar seu prato favorito e receber um menu completo, harmonizado com as melhores bebidas, além de sugestões de restaurantes com a atmosfera perfeita para a ocasião.

![Slide1](https://github.com/user-attachments/assets/228e6c14-7cb0-400e-aeba-986e5b221326)

# Exemplo de saída.

# Planejar um Jantar Romântico: Um Guia Completo

Que tal transformar seu jantar em uma experiência inesquecível? Com base no seu desejo por um delicioso macarrão à carbonara, vou te ajudar a criar um menu completo e um ambiente perfeito para a sua noite romântica.

Harmonizando Sabores: O que combinar com a Carbonara?A carbonara, com seu sabor intenso e cremoso, pede acompanhamentos que complementem sem sobrecarregar o paladar. Sugiro as seguintes opções:

1 - Uma salada leve e fresca: uma salada caprese, com tomate-cereja, manjericão fresco e mussarela de búfala, é uma excelente opção. O contraste entre o cremoso da mozzarella e o frescor dos tomates equilibra perfeitamente o prato principal.

2 - Pão artesanal com azeite extra virgem: um pão artesanal quentinho, acompanhado de um azeite extra virgem de alta qualidade, é um clássico que nunca falha. Mergulhe o pão no molho da carbonara para uma experiência ainda mais saborosa.

3 - Um toque de acidez: para cortar a riqueza da carbonara, um vinagre balsâmico de boa qualidade pode ser um excelente acompanhamento. Algumas gotas sobre a salada ou no pão com azeite adicionam uma complexidade interessante ao prato.Bebidas para a ocasião: Um toque de Elegância

A escolha da bebida é fundamental para um jantar romântico. Sugiro duas opções que harmonizam bem com a carbonara:

Um vinho branco seco: Um vinho branco seco, como um Sauvignon Blanc ou um Pinot Grigio, é uma excelente opção. A acidez do vinho corta a cremosidade da carbonara, enquanto os aromas frutados complementam os sabores do prato.

Espumante Brut: Para um toque mais sofisticado, um espumante brut é uma ótima escolha. A efervescência e a acidez do espumante limpam o paladar entre as garfadas e criam um clima festivo.Um jantar romântico em Paris: O cenário perfeito.Paris, a cidade do amor, oferece inúmeras opções para um jantar romântico. 

Um dos restaurantes mais famosos e românticos da cidade é o La Tour d'Argent. Com vista para o rio Sena e uma atmosfera elegante, o restaurante oferece uma experiência gastronômica inesquecível.

Montando o Jantar Romântico Perfeito Com base nas suas preferências e nas sugestões acima, podemos montar um menu completo para o seu jantar romântico:

Entrada: Salada caprese com vinagre balsâmico.

Prato principal: Macarrão à carbonara.

Acompanhamento: Pão artesanal com azeite extra virgem.

Bebida: Vinho branco seco ou espumante brut.

Dica: Para tornar o jantar ainda mais especial, prepare a mesa com velas, flores e música suave. Crie um ambiente intimista e romântico para desfrutar da companhia.
