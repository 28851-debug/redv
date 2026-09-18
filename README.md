# Exercício POO - Banda Escolar

**Aluno:**  Allyson de Santana Almeida e Rafael Andrade Simiao

## Parte 2 - Perguntas de Extração

### 1. Quantas classes concretas o texto descreve?

São 2 classes concretas:

- Violao
- Bateria

### 2. Quais atributos aparecem em todos os instrumentos?

Os atributos comuns são:

- nome
- material
- afinado

### 3. Qual atributo é exclusivo de cada instrumento?

- Violao: quantidade de cordas
- Bateria: quantidade de tambores

### 4. Quais são os comportamentos?

O método `tocar()` é diferente para cada instrumento, por isso é um método abstrato.

O método `afinar()` é igual para todos os instrumentos, por isso é um método concreto na classe `InstrumentoMusical`.

### 5. Qual recurso do Java garante que não seja possível criar um instrumento genérico?

A palavra-chave `abstract`, utilizada na classe `InstrumentoMusical`.

### 6. Para percorrer todos os instrumentos no mesmo laço, qual tipo a lista deve ter?

A lista deve ser:

`List<InstrumentoMusical>`
