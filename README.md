# Trabalho com Machine Learning no Azure ML

## Passo 1

Logo ao iniciar no Microsoft Azure, pesquise Machine Learning.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/dacd5074-4766-4ffc-92ec-a049121579b0)

Vá em Criar > Novo Workspace.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/84d0c6c8-10fe-4134-b2a1-ca15a0bcdaa1)

Após preencher todos os campos clique em Examinar + criar e depois de alguns segundos criar novamente

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/b7778c78-fad0-4db4-8284-c1c120c4f89b)

Após que alguns segundos a implantação foi concluída, logo em seguida clique em Ir para o recurso.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/a37c311e-27b8-440f-87da-5a0407240a5d)

Vá em inicar o estúdio.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/7e98ab10-72a1-416e-880a-724f1b0774d1)

## Passo 2 

Ao aparecer Estudio de Aprendizado de Máquina, vá em ML Automatizado

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/8f1c24f0-dd99-4cfe-9e83-022da36ef639)

Clique em Novo trabalho de ML automatizado

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/b4bdba04-ed92-4383-9194-b68db6322cd2)

Preencha os campos necessários

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/462bcc25-fd88-4690-87a5-bbd5e7bcf093)

Altera o tipo de tarefa para Regressão e clique em Criar

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/72342d8e-eb07-46f7-8fe8-55c66abbd09f)

Preencha os campos

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/699bc958-8abb-43ca-aaa4-1726b3e474b4)

Selecione tipo De Arquivos Da Web e clique em Avançar

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/81919b8c-7d16-4798-a1b2-2d7a8c8a1865)

Preencha o campo URL da Web com a URL *https://aka.ms/bike-rentals* para conseguirmos extrair os seus dados.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/586edbe1-5297-4f06-af3a-d4fe46ea8906)

Altere apenas o campo Cabeçalhos de coluna para Somente o primeiro arquivo tem cabeçalhos

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/230c8223-1d31-4483-a3dc-7c2f0b5cd8e0)

Não precisa alterar nada, pode apenas clicar em Avanaçar

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/e61f04d2-40d1-43e4-bcbd-4f24a5069f92)

Você pode avaliar se suas alterações e padrões estão corretos, se estiver apenas clique em Criar. Caso tenha algo de errado pode clicar no botão Voltar.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/a0a15739-127b-4827-8f3f-beface16f437)

Após o ativo de dados ser criado com sucesso, selecione o dado e clique em Avançar

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/bf83db38-99bf-47a5-b175-b89ba95ee35b)

Primeiro revise se o tipo de tarega e Dados estão corretos, logo em seguida selecione em Coluna de destino o campo rentals e vá na engrenagem.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/5b7a257f-c1b0-482e-b4b7-a1fd622cc716)

Desmarque os campos marcados e altere o campo Modelos permitidos, depois clique em Salvar.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/9c99a7ec-2b5c-4540-a82b-e89ab98f28a1)

Voltando a etapa Configurações de tarefas expande a aba Limites e preencha os campos e marque Habilitar encerramento antecipado. Em Validar e testar, no campo Tipo de validação selecione Divisão de validação de treinamento e dê continuidade no Avançar.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/d1d323f9-52af-4aa5-8f0b-447771153b90)

Na penúltima etapa pode manter o que a Azure recomenda e clique em Avançar

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/9f05f551-a7f3-42bc-aa4e-3017a97b07c9)

Você pode avaliar se suas alterações e padrões estão corretos, se estiver apenas clique em Enviar trabalho de treinamento. Caso tenha algo de errado pode clicar no botão Voltar.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/2e7cd3ac-2912-45de-a85a-a3b1e87185c6)

Em alguns minutos o Status mostrará implantação concluida.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/9a50f834-4ff0-49d1-bf2b-4fdc42bbc850)

## Passo 3

Após implantação clique no nome do algoritmo que aparece a você.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/7228376a-3811-4fbe-ada2-759ecb7a6756)

Vá em Implantar > Serviço Web e preencha todos esses campos dessa maneira.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/dc834791-b618-48aa-b2b5-72e9eeb9f47f)

Clique no nome em Status de implantação.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/c1129e6b-9d0f-44a2-a012-24aa8bf13308)

Aguarde até que o status da implantação mude para Succeeded. Isso pode levar de 5 a 10 minutos.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/7063454d-01a9-43bb-8236-580efe979036)

Por fim, este é o número previsto de aluguéis.

![image](https://github.com/jotapesb/ml-Azure/assets/147784947/b526d4f9-5658-4ec8-9d56-2370de74a90c)
