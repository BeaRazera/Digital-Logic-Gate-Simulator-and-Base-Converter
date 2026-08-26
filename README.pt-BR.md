### `README.pt-BR.md` (Português)

**Português** | [ English ](README.md)

# Simulador de Lógica Digital e Conversor Numérico de 8 Bits

Uma ferramenta web interativa desenvolvida com tecnologias padrão da web (HTML5, CSS3 e JavaScript) para simular portas lógicas digitais, gerar tabelas verdade em tempo real e realizar conversões de bases numéricas de 8 bits.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

## Funcionalidades

- **Portas Lógicas Suportadas:** AND (E), OR (OU), XOR (OU Exclusivo), NOT (NÃO A), NAND (NÃO E), NOR (NÃO OU) e XNOR (NÃO OU Exclusivo).
- **Entradas Dinâmicas:** Suporte para alternar entre simulação com 2 entradas (A e B) ou 3 entradas (A, B e C).
- **Tabela Verdade Interativa:** Gerada dinamicamente, destacando visualmente a linha correspondente aos valores atuais de entrada.
- **Conversão Numérica de 8 Bits:** Cálculo e exibição em tempo real do resultado em Decimal, Binário de 8 bits (`00000000`) e Hexadecimal (`0x00`).
- **Indicador Visual LED:** Display de LED com efeito luminoso para sinalizar saídas ativas (`1` / `0`).
- **Zero Dependências:** Código puro (Vanilla HTML/CSS/JS) sem bibliotecas ou frameworks externos.

## Como Funciona

1. **Alterar Entradas:** Clique nos botões de entrada (A, B ou C) para alternar o nível lógico entre `0` (Inativo) e `1` (Ativo).
2. **Habilitar 3ª Entrada:** Marque a opção "Habilitar Terceira Entrada (Entrada C)" para testar expressões de 3 entradas.
3. **Selecionar Porta Lógica:** Escolha a porta desejada no menu para calcular o resultado instantaneamente.
4. **Visualizar Resultados:**
   - O indicador LED acende sempre que a saída for equivalente a `1`.
   - Acompanhe a conversão do valor de saída nos painéis de Decimal, Binário e Hexadecimal.
   - Verifique a linha da combinação destacada na tabela verdade.
