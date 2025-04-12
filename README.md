# sistema de cadastro em java

projeto simples feito em java para simular o cadastro de pessoas — clientes e funcionários — utilizando os princípios da programação orientada a objetos.

## 📦 estrutura do projeto

o sistema conta com as seguintes classes:

- `Pessoa` — interface com métodos obrigatórios para nome e documento.
- `Cliente` — herda de `Endereco` e implementa `Pessoa`.
- `Funcionario` — também herda de `Endereco` e implementa `Pessoa`, com campo extra para `cargo`.
- `Main` — classe principal para testes com objetos.

```bash
.
├── Cliente.java
├── Funcionario.java
├── Pessoa.java
└── Main.java
