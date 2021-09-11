# SOLID
Projeto modelo para estudo dos princípios do SOLID. Com exemplos de violação e como solucionar.

Ao aplicar o SOLID é possível obter benefícios, tais como: 

1. Seja fácil de se manter, adaptar e se ajustar às alterações de escopo.
2. Seja testável e de fácil entendimento.
3. Seja extensível para alterações com o menor esforço necessário.
4. Que forneça o máximo de reaproveitamento.
5. Que permaneça o máximo dde tempo possível em utilização.

- SRP - Simple Responsability Principle
    - "Uma classe deve ter um, e apenas um, motivo para ser modificada"
    - Uma classe deve ter apenas uma responsabilidade

- OCP - Open Closed Principle
    - "Entidades de software (classes, módulos, funções) devem estar abertas para extensão, mas fechadas para modificação".

- LSP - Liskov Substitution Principle
    - "Subclasses devem ser substituíveis por suas Superclasses". Ou seja, uma classe ddeve poder ser substituída por sua classe mãe.
    - "Se nada como um pato, voa como um pato, porém precisa de baterias, provavelmente você possui um problema de abstração". Ou seja, se um pato de brinquedo é um pato original, então eu posso herdar de pato e dar um override nos métodos (ex: nadar) substituindo pelos comportamentos do pato de brinquedo. Porém aí acontece uma falha, pois o pato de brinquedo precisa de baterias para nadar. Existe uma desconexão com a classe original.
    - É sobre herança. É a "prova real" para verificar se sua classe foi herdada corretamente.

- ISP - Interface Segregation Principle
    - "Classes (Classes) não devem ser forçados a depender de métodos que não usam".
    - Muitas interfaces específicas são melhores do que uma interface única.

- DIP - Dependency Inversion Principle
    - "Módulos de alto nível não devem depender de módulos de baixo nível. Ambos devem depender de abstrações; Abstrações não devem depender de detalhes. Detalhes devem depender de abstrações".
    - Dependa de uma abstração e não de uma implementação.
