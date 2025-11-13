# Jogo WAR - Projeto da Disciplina

## Sobre
Este é um jogo de WAR implementado em C.  
Permite cadastrar territórios, definir cores e quantidade de tropas, e listar os territórios cadastrados.

O programa foi desenvolvido como projeto para a disciplina de [Estrutura de Dados].

---

## Funcionalidades
- Cadastro de até 5 territórios
- Cada território possui:
  - Nome
  - Cor
  - Quantidade de tropas
- Listagem dos territórios cadastrados
- Validação de entradas:
  - O programa impede que a quantidade de tropas seja menor que 1
  - O nome e a cor aceitam apenas texto (letras e espaços)

---

## Como compilar e executar (Linux)

1. Abra o terminal na pasta do projeto.
2. Compile o código com o GCC:
\```
gcc war.c -o war
\```
3. Execute o jogo:
\```
./war
\```

> O arquivo `war` pode ser gerado após a compilação. Certifique-se de ter o GCC instalado.

---

## Estrutura do projeto

\```
jogo-war/
├── war.c         # Código fonte em C
├── README.md     # Este arquivo de instruções
└── .gitignore    # Arquivos a serem ignorados pelo Git
\```

> O `.gitignore` deve incluir o executável e outros arquivos temporários, como:
\```
war
*.o
*.out
*~
\```

---

## Observações
- O projeto foi testado no Linux (CachyOS), mas deve funcionar em qualquer distribuição Linux com GCC instalado.
- Sempre que houver entrada inválida, o programa pedirá novamente até que seja digitado um valor correto.
- Este README serve para facilitar a execução e visualização do projeto, especialmente para professores ou avaliadores.

---

## Como contribuir
- Para alunos: enviar pull request ou adicionar melhorias no código fonte `war.c`.
- Para professores: verificar funcionalidade, testar compilação e execução conforme as instruções acima.

---

## Autor
- [Wagner]
- [Análise e Desenvolvimento de Sistemas, 2º Semestre de 2025]
