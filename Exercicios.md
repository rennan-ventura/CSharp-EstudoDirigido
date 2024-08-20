# CSharp-EstudoDirigido

Semana 1 - Fundamentos no C#

	Estruturas de Controle:

		Crie um programa que use um loop for para imprimir os números pares de 0 a 20.
		Implemente um switch-case para classificar notas (A, B, C, D, F) com base em uma pontuação numérica.


	Array e Coleções:

		Crie um array de inteiros e use um loop foreach para calcular a soma de todos os elementos.
		Implemente uma List<string> de nomes e adicione/remova elementos, depois ordene a lista.


	Método e Parâmetros:

		Escreva um método que aceite dois parâmetros inteiros e retorne o maior deles.
		Crie um método com parâmetros opcionais para calcular o volume de uma caixa.


	OOP:

		Crie uma classe Carro com propriedades (marca, modelo, ano) e métodos (Acelerar, Frear).
		Implemente uma classe derivada CarroEletrico que herda de Carro e adicione propriedades específicas.


	Exceções:

		Escreva um programa que leia um arquivo e trate as exceções FileNotFoundException e IOException.
		Crie uma exceção personalizada e lance-a em uma situação específica em seu código.



Semana 2 - Estrutura de Dados

	Lista (List<T>):

		Crie uma List<int> e implemente métodos para adicionar, remover e buscar elementos.


	Filas (Queue<T>):

		Simule uma fila de impressão usando Queue<string>, adicionando e removendo "documentos".


	Pilhas (Stack<T>):

		Use uma Stack<char> para verificar se uma string é um palíndromo.


	Dicionários (Dictionary<TKey, TValue>):

		Crie um dicionário de palavras e suas definições, permitindo adicionar, buscar e atualizar entradas.


	Conjuntos (HashSet<T>):

		Use HashSet<int> para encontrar elementos únicos em uma lista de números.


	Árvore e Grafo:

		Implemente uma árvore binária simples com métodos para adicionar nós e percorrer em ordem.



Semana 3 - LINQ

	Sintaxe de Consulta e Método:

		Crie uma lista de objetos Produto e use LINQ para filtrar produtos por preço (sintaxe de consulta e método).


	Operadores LINQ Comuns:

		Use Where, Select, OrderBy, GroupBy e Join para analisar uma coleção de Pedido e Cliente.


	LINQ to Objects e XML:

		Crie um arquivo XML simples e use LINQ to XML para extrair e manipular dados.



Semana 4 - Fundamentos do .NET


	CLR e Garbage Collection:

		Escreva um programa que demonstre o ciclo de vida de objetos e force a coleta de lixo.


	Assemblies e Namespaces:

		Crie dois projetos de biblioteca de classes e um projeto console, demonstrando o uso de assemblies e namespaces.



Semana 5 - Programação Assíncrona

	async e await:

		Implemente um método assíncrono que simule o download de várias imagens da web.


	Task e Task<T>:

		Crie um programa que execute várias tarefas em paralelo e agregue os resultados.


Padrões Assíncronos:

	Implemente um padrão produtor-consumidor usando um BlockingCollection<T>.


Semana 6 - Entity Framework Core

	Code First:

		Crie um modelo de domínio simples (ex: Blog e Post) e gere o banco de dados usando migrações.


	CRUD Operations:

		Implemente operações CRUD para o modelo criado, incluindo consultas com filtros e ordenação.


	Relacionamentos:

		Adicione um relacionamento muitos-para-muitos (ex: Tags para Posts) e demonstre como trabalhar com ele.



Semana 7 - ASP.NET Core MVC

	MVC Básico:

		Crie um aplicativo de lista de tarefas com operações CRUD, implementando Model, View e Controller.


	Roteamento e Actions:

		Implemente rotas personalizadas e ações com diferentes verbos HTTP.


	Views e Validação:

		Use Razor para criar views dinâmicas e implemente validação de formulários no lado do cliente e servidor.



Semana 8 - Web API com ASP.NET Core

	API RESTful:

		Crie uma API para o aplicativo de lista de tarefas da semana anterior.


	Serialização e Desserialização:

		Implemente endpoints que aceitem e retornem JSON, lidando com diferentes formatos de data.


	Autenticação Básica:

		Adicione autenticação JWT à sua API e proteja endpoints específicos.