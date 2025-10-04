# 📚 JAVA-03-JAVA-04

Exercícios de Variáveis e Operadores em Java – Generation Brasil

## 📋 Sobre o Projeto

Este repositório contém exercícios práticos de Java focados em variáveis, operadores aritméticos e entrada/saída de dados. Os programas foram desenvolvidos como parte do bootcamp da Generation Brasil.

## 🗂️ Estrutura do Projeto

```
JAVA-03-JAVA-04/
├── README.md
└── src/
    └── exercicios/
        ├── DiferencaEntreValores.java
        ├── MediaFinal.java
        ├── NovoSalario.java
        └── SalarioLiquido.java
```

## 💻 Exercícios Implementados

### 1. Diferença Entre Valores
**Arquivo:** `DiferencaEntreValores.java`

Calcula a diferença absoluta entre dois valores fornecidos pelo usuário.

**Exemplo de Execução:**
```
Digite o primeiro valor: 10.5
Digite o segundo valor: 3.2
Diferença entre os valores: 7.30
```

---

### 2. Média Final
**Arquivo:** `MediaFinal.java`

Calcula a média aritmética de 4 notas fornecidas pelo usuário.

**Exemplo de Execução:**
```
Nota 1: 8.5
Nota 2: 7.0
Nota 3: 9.0
Nota 4: 6.5
Média final: 7.75
```

---

### 3. Novo Salário
**Arquivo:** `NovoSalario.java`

Calcula o novo salário após adicionar um abono ao salário atual.

**Exemplo de Execução:**
```
Digite o salário: 2500.00
Digite o abono: 300.00
Novo salário: 2800.00
```

---

### 4. Salário Líquido
**Arquivo:** `SalarioLiquido.java`

Calcula o salário líquido considerando salário bruto, adicionais e descontos.

**Exemplo de Execução:**
```
Salário bruto: 3000.00
Adicional: 500.00
Descontos: 450.00
Salário líquido: 3050.00
```

## 🚀 Como Executar

### Pré-requisitos
- Java JDK 8 ou superior instalado
- Terminal/Prompt de Comando ou IDE Java (Eclipse, IntelliJ, VS Code)

### Opção 1: Usando Terminal/Prompt

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/JAVA-03-JAVA-04.git
cd JAVA-03-JAVA-04
```

2. Compile os arquivos:
```bash
javac src/exercicios/*.java
```

3. Execute o programa desejado:
```bash
# Diferença entre valores
java -cp src exercicios.DiferencaEntreValores

# Média final
java -cp src exercicios.MediaFinal

# Novo salário
java -cp src exercicios.NovoSalario

# Salário líquido
java -cp src exercicios.SalarioLiquido
```

### Opção 2: Usando IDE

1. Importe o projeto na sua IDE
2. Navegue até o arquivo desejado em `src/exercicios/`
3. Clique com botão direito e selecione "Run" ou "Executar"

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Java
- **Bibliotecas:** java.util.Scanner
- **Paradigma:** Programação Estruturada

## 📖 Conceitos Aplicados

- Declaração e inicialização de variáveis
- Tipos de dados primitivos (float)
- Operadores aritméticos (+, -, /)
- Entrada de dados com Scanner
- Formatação de saída com printf
- Uso de Math.abs() para valor absoluto
- Boas práticas: fechamento de recursos (scanner.close())

## 👨‍💻 Autor

Desenvolvido durante o bootcamp da **Generation Brasil**

## 📝 Observações

- Todos os programas utilizam a classe `Scanner` para entrada de dados
- Formatação de saída padronizada com 2 casas decimais
- Recursos são devidamente fechados após o uso
- Código documentado com JavaDoc

## 📄 Licença

Este projeto é de código aberto e está disponível para fins educacionais.

---
⭐ Se este repositório foi útil para você, considere dar uma estrela!

💬 Dúvidas ou sugestões? Abra uma issue!
