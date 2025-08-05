# das-1-2025-2-a
- 04/08/2025
O que é uma abstração ?
- É o processo de esconder detalhes complexos e não essenciais de um objeto, concentrando-se apenas nos aspectos fundamentais para o contexto específico.

Ocultamento de Informação
- Quando ocultamos detalhes e informções desnecessárias, em java normalmente utilizando getters e setters

Oque é um código com coesão?
- É um código/classe que faz uma coisa bem feita, quando a classe tem uma a tarefa a realizar e consegue de fato executar a aquela tarefa do jeito certo,
facilitando a implementação e manutenção da classe.

1. Herança
Definição:
A herança é um mecanismo pelo qual uma classe filha (ou subclasse) herda atributos e métodos de uma classe pai (ou superclasse).
Representa uma relação “é um” (ex: um cachorro é um animal).

Promove reutilização de código.

✅ 2. Implementação
Definição:
Em POO, implementação geralmente se refere à implementação de interfaces. Uma interface define o que uma classe deve fazer, mas não como. A classe que implementa uma interface precisa fornecer o comportamento (método) definido na interface.
Define uma relação “deve fazer”.
Uma classe pode implementar várias interfaces (Java, C# etc.).
Interface é um contrato.

✅ 3. Associação
Definição:
Associação é um tipo de relacionamento entre duas classes onde uma usa ou se relaciona com a outra. Pode ser de vários tipos:

Tipos de associação:
Simples (uni ou bidirecional): Uma classe usa a outra.

Agregação: “Tem um”, mas com vida independente.

Composição: “É parte de”, com vida dependente.

🔹 Simples (Associação normal)
Editar
class Pessoa {
    String nome;
}

class Empresa {
    Pessoa funcionario; // associação simples
}

🔹 Agregação (tem, mas separadamente)
class Departamento {
    List<Funcionario> funcionarios; // funcionários podem existir fora do departamento
}
🔹 Composição (parte do todo, dependente)
class Casa {
    private Quarto quarto; // o quarto só existe com a casa
}

Acoplamento:
Refere-se aograu de interdependência entre diferentes partes de um sistema de software, como módulos, classes ou funções.

05/08/2025


