# Corpo-DSL

**Corpo** is a domain-specific language (DSL) inspired by Western corporate culture, office bureaucracy, and professional jargon, developed for **CPSC 3740 (Group D)** and implemented as a **C++ interpreter**.

## Highlights

- **Corporate-Themed Syntax**: Variables (`kpi`, `signoff`, `memo`), blocks (`kick_off` / `wrap_up`), conditionals (`pending_approval` / `alternatively` / `worst_case_scenario`), loops (`circle_back_while`), functions (`meeting` / `review` / `deliverable`), output (`perMyLastEmail` / `fyi_all`), and comments (`hi ...` and `fyi ... sincerely [name] --`).
- **Reverse BEDMAS**: Addition (`+`) and subtraction (`-`) bind tighter and evaluate *before* multiplication (`*`) and division (`/`).

### Hello World

```corpo
- perMyLastEmail "Hello World!".
```

## Repository Structure

```text
Corpo-DSL/
├── docs/                  # Proposal, grammar specification, and presentation slides
├── src/                   # C++ interpreter implementation
│   ├── lexer/             # Tokenizer / lexical analysis
│   ├── parser/            # Syntax analysis & AST
│   ├── interpreter/       # Runtime evaluation & scoping
│   └── main.cpp           # Interpreter entry point
├── examples/              # Sample Corpo programs
├── tests/                 # Test cases
├── .gitignore
└── README.md
```

## Documentation

- [DSL Proposal & EBNF Grammar](docs/CPSC-3740%20_%20Group-D%20_%20DSL%20Proposal.pdf)
- [Project Presentation](docs/Corpo%20presentation_20261105_120558_0000.pdf)

## Team (Group D)

- **Sarah** 
- **Dax**
- **Okwesilieze** 
- **Emmanuel**
- **Kai**
