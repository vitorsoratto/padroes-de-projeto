# Padrões de Projeto - Design Patterns

1. O que é um padrão de projeto?
2. Por que devo aprender padrões?
3. Quais as Características de um bom projeto de software?
4. O que são os princípios solid?
5. O que são os padrões de projeto criacionais e seus tipos;
6. O que são os padrões de projeto estruturais e seus tipos;
7. O que são os padrões de projeto comportamentais e seus tipos;

___
### 1. O que é um padrão de projeto?
São formas comuns de resolver problemas recorrentes durante o desenvolvimento de um software, não é um código pronto e sim uma definição melhor de como resolver.

___
### 2. Por que devo aprender padrões?
Os padrões não surgiram do nada, geralmente eles são soluções já testadas anteriormente, o que significa maior ganho de produtividade no desenvolvimento.

Além disso as conversas técnicas caem drasticamente, já que é só citar um design pattern como exemplo de desenvolvimento ao invés do total comportamento.

___
### 3. Quais as Características de um bom projeto de software?
Um bom projeto de software é aquele que tem qualidade tanto para o desenvolvimento quanto para o usuário final no qual fará o uso da ferramenta desenvolvida.

Para o desenvolvimento podemos citar algumas características que o tornam de qualidade
* Utilizar um padrão de projeto compatível com a ideia da corporação
* Boa documentação de software

O usuário final não fica de fora do software, já que é ele que é o objetivo final de todo o projeto
* O sistema consegue se integrar facilmente com outras ferramentas nem sempre desenvolvidas pela mesma empresa
* De facil utilização e sem a necessidade e muito treinamento para o uso
* Em caso de imprevistos o comportamento é agradavel

___
### 4. O que são os princípios SOLID?
SOLID é um acrônimo para cinco postulados de design, destinados a facilitar a compreensão, o desenvolvimento e a manutenção de software.
```
S — Single Responsiblity Principle (Princípio da responsabilidade única)
O — Open-Closed Principle (Princípio Aberto-Fechado)
L — Liskov Substitution Principle (Princípio da substituição de Liskov)
I — Interface Segregation Principle (Princípio da Segregação da Interface)
D — Dependency Inversion Principle (Princípio da inversão da dependência)
```

> Esses princípios ajudam o programador a escrever códigos mais limpos, separando responsabilidades, diminuindo acoplamentos, facilitando na refatoração e estimulando o reaproveitamento do código.

___
### 5. O que são os padrões de projeto criacionais e seus tipos
Os padrões criacionais fornecem vários mecanismos de criação de objetos, que aumentam a flexibilidade e reutilização de código já existente. Fornece uma interface para criar objetos em uma classe pai, mas permite que as classes-filho alterem o tipo de objetos que serão criados.

1. Builder
2. Abstract Factory
3. Factory Method
4. Prototype
5. Singleton

___
### 6. O que são os padrões de projeto estruturais e seus tipos
Os padrões estruturais se preocupam com a forma como classes e objetos são compostos para formar estruturas maiores. Os de classes utilizam a herança para compor interfaces ou implementações, e os de objeto ao invés de compor interfaces ou implementações, eles descrevem maneiras de compor objetos para obter novas funcionalidades.

1. Adapter
2. Bridge
3. Composite
4. Decorator
5. Facade
6. Flyweight
7. Proxy

___
### 7. O que são os padrões de projeto comportamentais e seus tipos
Os padrões de comportamento se concentram nos algoritmos e atribuições de responsabilidades entre os objetos. Eles não descrevem apenas padrões de objetos ou de classes, mas também os padrões de comunicação entre os objetos.

1. Chain of Responsibility
2. Command
3. Interpreter
4. Iterator
5. Mediator
6. Memento
7. Observer
8. State
9. Strateg
10. Template Method
11. Visitor
