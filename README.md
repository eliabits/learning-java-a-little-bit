🚀 Roadmap Java para ADS (3º Período)

Objetivo: Aprender Java do zero até um nível suficiente para desenvolver aplicações orientadas a objetos, consumir banco de dados e criar APIs com Spring Boot.

Recomendação: Estudar de 1 a 2 horas por dia, praticando mais do que assistindo aulas.

📚 Trilha de Estudos Java
Etapa 1 — Preparação do Ambiente
Objetivos
Instalar Java
Configurar VS Code ou IntelliJ IDEA
Aprender a compilar e executar programas
O que estudar
O que é Java
JDK
JVM
JRE
Variáveis de ambiente (JAVA_HOME)
Exercícios

Criar programas que exibam:

System.out.println("Olá Mundo!");
System.out.println("Meu nome é Eliabe Rafael");
Estrutura do repositório
java-roadmap/
│
├── etapa-01-introducao/
│   ├── OlaMundo.java
│   └── MeuNome.java
│
└── README.md
Commit
git add .
git commit -m "Etapa 1 - Configuração do ambiente e primeiros programas"
git push
Etapa 2 — Variáveis e Tipos de Dados
Objetivos

Aprender a armazenar informações.

Estudar
int
double
float
char
boolean
String
Exercícios

Criar programas:

Cadastro de aluno
String nome = "Eliabe";
int idade = 20;
Calculadora de média
double nota1 = 8;
double nota2 = 9;
Conversor Celsius/Fahrenheit
Estrutura
etapa-02-variaveis/
│
├── CadastroAluno.java
├── MediaAluno.java
└── ConversorTemperatura.java
Commit
git commit -m "Etapa 2 - Variáveis e tipos de dados"
git push
Etapa 3 — Operadores
Estudar
Matemáticos
+
-
*
/
%
Relacionais
==
!=
>
<
>=
<=
Lógicos
&&
||
!
Exercícios
Calculadora simples
Verificador de maior idade
Verificador de número par
Commit
git commit -m "Etapa 3 - Operadores matemáticos e lógicos"
git push
Etapa 4 — Estruturas Condicionais
Estudar
if
if(condicao){
}
if/else
else if
switch
Exercícios
Aprovação de aluno
Sistema de notas
Calculadora com switch
Commit
git commit -m "Etapa 4 - Estruturas condicionais"
git push
Etapa 5 — Estruturas de Repetição
Estudar
for
for(int i=0;i<10;i++){
}
while
do while
Exercícios
Tabuada
Contador de 1 a 100
Soma dos números pares
Fatorial
Commit
git commit -m "Etapa 5 - Estruturas de repetição"
git push
Etapa 6 — Métodos
Estudar
public static void nomeMetodo(){
}
Conceitos
Parâmetros
Retorno
Escopo
Exercícios
Método de soma
Método para calcular média
Método para verificar maior idade
Commit
git commit -m "Etapa 6 - Métodos e funções"
git push
Etapa 7 — Vetores e Matrizes
Estudar
Arrays
int[] numeros = new int[5];
Matrizes
int[][] matriz = new int[3][3];
Exercícios
Média de turma
Buscar elemento
Jogo da velha simples
Commit
git commit -m "Etapa 7 - Vetores e matrizes"
git push
Etapa 8 — Orientação a Objetos (IMPORTANTE)
Estudar
Classes
public class Pessoa{
}
Objetos
Pessoa p = new Pessoa();
Atributos
Métodos
Construtores
Encapsulamento
Getters e Setters
Exercício

Criar:

Classe Pessoa
Pessoa
Classe Aluno
Aluno
Classe Produto
Produto
Commit
git commit -m "Etapa 8 - Programação Orientada a Objetos"
git push
Etapa 9 — Herança e Polimorfismo
Estudar
Herança
extends
Polimorfismo
Sobrescrita
@Override
Classes Abstratas
Interfaces
Exercícios
Pessoa
 ├── Aluno
 └── Professor
Veiculo
 ├── Carro
 └── Moto
Commit
git commit -m "Etapa 9 - Herança e Polimorfismo"
git push
Etapa 10 — Collections
Estudar
ArrayList
ArrayList<String>
HashMap
HashMap<Integer,String>
HashSet
HashSet<String>
Exercícios
Cadastro de alunos
Lista de produtos
Agenda de contatos
Commit
git commit -m "Etapa 10 - Collections Framework"
git push
Etapa 11 — Tratamento de Exceções
Estudar
try
catch
finally
throw
Exercícios
Divisão por zero
Validação de idade
Leitura de arquivos
Commit
git commit -m "Etapa 11 - Tratamento de exceções"
git push
Etapa 12 — Banco de Dados com Java
Estudar
JDBC
Conexão com banco
INSERT
UPDATE
DELETE
SELECT
Banco sugerido
MySQL
Projeto

Sistema de cadastro de clientes.

Commit
git commit -m "Etapa 12 - JDBC e banco de dados"
git push
Etapa 13 — Projeto CRUD Completo
Criar

Sistema de:

Clientes
Produtos
Vendas
Funcionalidades
Cadastrar
Listar
Atualizar
Excluir
Commit
git commit -m "Projeto CRUD completo em Java"
git push
Etapa 14 — Spring Boot
Estudar
Maven
Spring Boot
REST API
Controller
Service
Repository
JPA
Projeto

API de gerenciamento de usuários.

Endpoints
GET /usuarios

POST /usuarios

PUT /usuarios/{id}

DELETE /usuarios/{id}
Commit
git commit -m "Primeira API REST com Spring Boot"
git push
Etapa 15 — Projeto Final para Portfólio
Sistema de Oficina Mecânica

Como você já trabalhou em modelagem de oficina, esse projeto é excelente para o GitHub.

Entidades
Cliente
Veiculo
OrdemServico
Servico
Peca
Mecanico
Tecnologias
Java
Spring Boot
MySQL
JPA
Git
GitHub
Funcionalidades
CRUD completo
Banco de dados
API REST
Relacionamentos
Commit
git commit -m "Projeto final - Sistema de Oficina Mecânica"
git push
📅 Cronograma Sugerido
Semana	Conteúdo
1	Etapas 1 e 2
2	Etapas 3 e 4
3	Etapas 5 e 6
4	Etapa 7
5	Etapa 8
6	Etapa 9
7	Etapa 10
8	Etapa 11
9	Etapa 12
10	Etapa 13
11	Etapa 14
12	Etapa 15
🎯 Meta Final

Ao concluir este roadmap você deverá ser capaz de:

✅ Criar programas em Java do zero
✅ Aplicar Programação Orientada a Objetos
✅ Trabalhar com Arrays e Collections
✅ Utilizar Banco de Dados MySQL
✅ Desenvolver APIs REST com Spring Boot
✅ Versionar projetos com Git e GitHub
✅ Construir projetos completos para estágio e portfólio

Repositório Final
java-roadmap/
│
├── etapa-01-introducao
├── etapa-02-variaveis
├── etapa-03-operadores
├── etapa-04-condicionais
├── etapa-05-repeticao
├── etapa-06-metodos
├── etapa-07-arrays
├── etapa-08-poo
├── etapa-09-heranca
├── etapa-10-collections
├── etapa-11-excecoes
├── etapa-12-jdbc
├── etapa-13-crud
├── etapa-14-springboot
├── etapa-15-projeto-final
└── README.md