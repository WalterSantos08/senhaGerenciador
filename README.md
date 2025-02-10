# Gerador de Senhas Aleatórias

## Descrição
Este é um simples gerador de senhas aleatórias em Python. O usuário pode definir o tamanho da senha desejada, e o programa gerará uma combinação aleatória de letras (maiúsculas e minúsculas), números e caracteres especiais.

## Tecnologias Utilizadas
- Python 3
- Biblioteca `random`
- Biblioteca `string`

## Como Utilizar
1. Execute o script Python.
2. Informe a quantidade de dígitos desejados para a senha quando solicitado.
3. O programa gerará e exibirá uma senha aleatória com o tamanho especificado.

## Exemplo de Uso
```bash
$ python gerador_senha.py
Quantos digitos na senha? 12
Senha gerada:
abC@1dEf!2G3
```

## Estrutura do Código
- **`password_generator(len_pass=8)`**: Função que gera uma senha aleatória com o comprimento especificado pelo usuário.
  - Usa caracteres alfanuméricos e sinais de pontuação.
- **Entrada do Usuário**: Solicita o tamanho da senha e valida se é um número.
- **Saída**: Exibe a senha gerada.

