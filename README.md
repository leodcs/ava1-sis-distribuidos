# FACULDADE DE PETROLINA (FACAPE)

Projeto de avaliação I unidade - Sistemas distribuídos.

- Composto por 3 componentes: `src/Cliente.java`, `src/Servidor1.java` e `src/Servidor2.java`
- O Servidor1 é responsável pelas operações básicas.
- O Servidor2 é responsável pelas operações de porcentagem, raiz quadrada e potenciação.
- Tratamento de: operação inválida e divisão por zero


## Endereçamento
Ambos os servidores estão localizados no localhost (127.0.0.1).

## Portas
O socket do Servidor1 é inicializado na porta 9998, já o do Servidor2 na porta 9999.

## Comunicação
Os principais métodos usados para a comunicação entre servidores e clientes são da classe [ObjectOutputStream](https://docs.oracle.com/javase/7/docs/api/java/io/ObjectOutputStream.html).