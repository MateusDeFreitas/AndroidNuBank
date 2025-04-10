# AndroidNuBank

Este projeto marca meu **primeiro contato com desenvolvimento mobile Android** utilizando **Java**. Inspirado no app da Nubank, o objetivo foi construir um aplicativo simples com múltiplas telas, focando na **passagem de dados entre Activities** e na **manipulação de elementos da interface**.

## 📱 Sobre o Projeto

O app simula uma experiência de transferência de valores com três telas diferentes. O usuário pode incrementar ou decrementar um número, e esse valor é transferido entre as telas, sendo atualizado e reaproveitado em cada etapa.

### 🚀 Funcionalidades

#### ✅ Tela 1 – `MainActivity`:
- Exibe o valor atual
- Botões **+** e **–** para alterar o valor
- Botão para **ir à próxima tela**, enviando o valor via `Intent`

#### ✅ Tela 2 – `PrincipalActivity`:
- Recebe o valor da tela anterior
- Permite modificá-lo com botões **+** e **–**
- Envia o valor para a próxima tela

#### ✅ Tela 3 – `TransferenciaActivity`:
- Recebe o valor atualizado
- Continua permitindo alterações
- Exibe o valor de forma destacada
- Possui botão para retornar à primeira tela, mantendo o valor atualizado

## 🧱 Estrutura do Projeto

- `MainActivity.java` → Primeira tela
- `PrincipalActivity.java` → Segunda tela
- `TransferenciaActivity.java` → Terceira tela
- `activity_main.xml`, `activity_principal.xml`, `activity_transferencia.xml` → Layouts das telas

## 💡 Conceitos Aplicados

- Passagem de dados entre Activities com `Intent`
- Retorno de valores com `ActivityResultLauncher`
- Manipulação de componentes visuais (`TextView`, `Button`, `FloatingActionButton`)
- Criação de layouts com `ConstraintLayout`
- Organização de código para facilitar a reutilização e o entendimento do ciclo de vida das Activities

## 🛠️ Tecnologias Utilizadas

- **Java**
- **Android SDK (API 34)**
- **ConstraintLayout**
- **Material Components (FloatingActionButton)**

---

📘 **Nota:** Desenvolvido em parceria com um colega como parte de uma atividade acadêmica, esse projeto me permitiu explorar a lógica e a estrutura de um app Android, reforçando conceitos de navegação, estado e manipulação de dados em tempo real. Foi um passo importante na minha jornada como desenvolvedor mobile!
