# API-Rest

Faça o desenho de uma API Rest para um sistema de gerenciamento de alunos.
Essa API deve ser capaz de criar, listar, atualizar e deletar alunos.
Seu desenho deve conter:

- Endpoints
- JSON do recurso

Em um primeiro momento, considere que um aluno tem:

- Nome
- Idade
- Email
- Telefone

---

## Resposta

### GET /students

```json
[
  {
    "id": 1,
    "name": "John Doe",
    "age": 20,
    "email": "john.doe@example.com",
    "phone": "123456789"
  }
]
```

[//]: # (Continue aqui)

---

Em um segundo momento, considere que um aluno pode estar cadastrado em uma disciplina.
Uma disciplina tem:

- Nome
- Carga horária
- Múltiplos alunos

Adapte os endpoints de alunos e também crie endpoints para criar, listar, atualizar e deletar disciplinas.

---

## Resposta

[//]: # (Continue aqui)

---

Em um terceiro momento, considere que uma disciplina pode ser lecionada por múltiplos professores.
Um professor tem:

- Nome
- Idade
- Email
- Telefone
- Múltiplas disciplinas

Adapte os endpoints anteriores e também crie endpoints para criar, listar, atualizar e deletar professores.
Desenhe endpoints para que seja possível listar os alunos de uma disciplina e também listar as disciplinas de um professor.

---

## Resposta

[//]: # (Continue aqui)
