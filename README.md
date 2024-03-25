## Como criar um conta no Microsoft Azure

- Você vai entrar no site da **[microsoft azure](azure.microsoft.com)**
	> Dentro do site você vai clicar em criar uma **conta teste** e preencher o formulário para cadastro. 


## Como  criar um modelo

- Clique em **criar um recurso** no menu esquerdo
	> Nesse seção você vai pesquisar por **Azure Machine Learning** e criar o modelo.
	
	> Em **Resource group** clique em **create new** e escreva uma nome para o modelo.

### Workspace details

- Name: fica a sua escolha (exemplo: laboratorioai900)
- Region: East US
- `Review + Create` 
- `Create` 
>**É importante que você espere o termino do Deploy antes de sair desse tela.**

- `Go to resouce`
- `Launch Studio`

### ML automatizado

No menu esquerdo clique na opção **ML automatizado**

- Clique em: `+ Novo trabalho de ML automatizado`;
- Preencha os campos de acordo com a sua documentação;
- Depois de configurar todo o seu ML espere ele ser executado 100% (tempo estimado: **15 minutos**).

### Tarefas (jobs)
Depois que seu ML estiver completo, vá para para a seção de Tarefas localizado no menu esquerdo.

- Abra a sua tarefa;
- Escolha a com melhor resultado;
- Abra a opção **implantar** e escolha **Serviço web**

#### Serviços Web
Preencha os campos desse forma:

- Nome: (pessoal)
- Descrição: (pessoal)
- Tipo de computação: ICA
- `Implantar`

#### Modelos

- Vá para modelos;
- Abra o seu modelo;
- Clique na opção: **pontos de extremidade**;

#### ponto de extremidade
- Selecione o seu modelo e espere ele ser carregado!
-  Clique em testar e substitua o .json com as informações desejadas! 
