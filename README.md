# Payroll System (Folha de Pagamento)

Sistema de gerenciamento de folha de pagamento desenvolvido para aplicar conceitos fundamentais de Programação Orientada a Objetos (POO) em Java, com foco em composição e tipos enumerados.

## 🚀 Tecnologias e Ferramentas
* **Java 17**
* **Maven** (Gerenciamento de dependências)
* **IntelliJ IDEA**
* **Git/GitHub** (Versionamento e fluxo de trabalho profissional)

## 🎯 Objetivos do Projeto
O software foi construído para resolver o problema de cálculo de salários baseados em contratos e níveis de cargo, aplicando:
* **Composição de Objetos**: Relacionamento entre Departamentos, Trabalhadores e Contratos.
* **Enumerations (Enums)**: Definição de níveis de senioridade (`JUNIOR`, `MID_LEVEL`, `SENIOR`).
* **Lógica de Data**: Manipulação de `Calendar` e `SimpleDateFormat` para processamento de ganhos mensais.

## 🏗️ Estrutura do Projeto (Maven)
```text
src/
 └── main/
     └── java/
         └── com.payroll/
             ├── entities/       # Classes de domínio (Trabalhador, Contrato, etc.)
             ├── enums/          # Definições de cargos/status
             └── application/    # Classe principal com o entry point (Main)