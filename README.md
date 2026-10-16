# Projeto Educacional de Criptografia com Python — DIO

## Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio educacional da Digital Innovation One (DIO), com o objetivo de estudar conceitos de criptografia simétrica e manipulação de arquivos utilizando Python.

A atividade demonstra um processo básico de criptografia e descriptografia de arquivos com o algoritmo AES no modo CTR, em um ambiente controlado.

## Tecnologias utilizadas

- Python 3
- Biblioteca `pyaes`
- Algoritmo AES no modo CTR
- Kali Linux em máquina virtual
- Git e GitHub

## Arquivos do projeto

| Arquivo | Descrição |
|---|---|
| `encrypter.py` | Demonstra o processo de criptografia de um arquivo de teste. |
| `decrypter.py` | Demonstra o processo de descriptografia utilizando a chave correspondente. |

## Conceitos estudados

- Fundamentos da criptografia simétrica.
- Funcionamento do AES no modo CTR.
- Leitura e escrita de arquivos binários.
- Documentação e versionamento de código.

## Execução

Instale a dependência necessária:

```bash
python3 -m pip install pyaes
```

Antes de executar os scripts, confira o código-fonte e os nomes dos arquivos esperados. Utilize exclusivamente arquivos descartáveis em um ambiente isolado.

## Considerações de segurança

Este projeto tem finalidade exclusivamente educacional. Os scripts podem remover ou sobrescrever arquivos durante o processamento, portanto, não devem ser utilizados em documentos pessoais ou dados importantes.

O modo CTR, isoladamente, não garante a integridade nem a autenticidade dos dados. Esta implementação não é destinada ao uso em produção.

## Referência

Desafio educacional original da DIO:

https://github.com/cassiano-dio/cibersecurity-desafio-ransomware

## Aprendizados

O projeto proporcionou a prática de conceitos de Python, criptografia simétrica, manipulação de arquivos e documentação técnica, reforçando a importância de realizar testes em ambientes controlados.
