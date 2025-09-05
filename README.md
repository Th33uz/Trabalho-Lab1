📌 Projeto - Cálculo de IMC

Trabalho desenvolvido na disciplina Laboratório de Programação I com o professor Thiago.

👨‍💻 Integrantes:

Matheus Abilio da Silva Camargo — Cod: 841929

Maria Fernanda Faria Kurukava — Cod: 841877

📖 Descrição

O projeto consiste em um sistema simples em C++ para cadastrar pessoas e calcular o Índice de Massa Corporal (IMC).
O programa permite:

Cadastrar dados de uma pessoa (nome, idade, peso e altura).

Listar todas as pessoas cadastradas com seus respectivos IMCs.

Pesquisar uma pessoa pelo nome e exibir seu IMC e avaliação.

⚙️ Funcionalidades

Cálculo do IMC a partir do peso e altura.

Classificação do IMC, exibindo mensagens de saúde:

Abaixo do peso

Peso saudável

Sobrepeso

Obesidade

Cadastro de pessoas com nome, idade, peso e altura.

Listagem de pessoas cadastradas.

Pesquisa por nome.

Menu interativo para navegação no sistema.

📊 Fórmula do IMC
𝐼
𝑀
𝐶
=
𝑝
𝑒
𝑠
𝑜
𝑎
𝑙
𝑡
𝑢
𝑟
𝑎
2
IMC=
altura
2
peso
	​


Exemplo:

Peso: 70 kg

Altura: 1.75 m

Cálculo: 70 / (1.75 * 1.75) = 22.86 (Peso saudável)

▶️ Como executar

Compile o programa em um compilador C++ (exemplo usando g++):

g++ main.cpp -o imc


Execute o programa:

./imc

📂 Estrutura do Projeto

main.cpp → código principal do sistema.

🖥️ Exemplo de uso
Bem-vindo qual opção deseja..:
1. Cadastrar pessoa
2. Lista de pessoas cadastradas
3. Pesquisar pessoa por nome
4. Sair
Escolha uma opção: 1

Digite o nome da pessoa: Ana
Digite a idade da pessoa: 25
Digite o peso da pessoa (em kg): 60
Digite a altura da pessoa (em metros): 1.65
Pessoa cadastrada com sucesso!

📌 Observações

O sistema é simples e feito para fins acadêmicos.

Pode ser expandido para incluir salvamento em arquivos ou banco de dados.
