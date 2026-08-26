[ Português ](README.pt-BR.md) | **English**

# Digital Logic Gate Simulator & Base Converter

An interactive web-based tool for simulating digital logic gates, generating dynamic truth tables, and performing 8-bit numerical base conversions in real-time.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

## Features

- **Logic Gates Supported:** AND, OR, XOR, NOT, NAND, NOR, XNOR.
- **Dynamic Inputs:** Switch between 2-input and 3-input modes.
- **Dynamic Truth Table:** Generates truth tables on the fly and highlights the active row matching current inputs.
- **8-Bit Base Conversion:** Instant conversion of output values to Decimal, 8-Bit Binary (`00000000`), and Hexadecimal (`0x00`).
- **Visual Output Indicator:** Animated LED display reflecting current output logic states (`HIGH`/`LOW`).
- **Zero External Dependencies:** Built entirely with plain HTML, CSS, and vanilla JavaScript.

## How It Works

1. **Toggle Inputs:** Click on the Input buttons (A, B, or C) to switch between logic levels `0` (LOW) and `1` (HIGH).
2. **Enable 3rd Input:** Check the "Habilitar Terceira Entrada (Entrada C)" box to test 3-input logic operations.
3. **Select Logic Gate:** Use the dropdown menu to choose the desired logic gate.
4. **Observe Outputs:** 
   - Watch the virtual LED indicator turn ON (`1`) or OFF (`0`).
   - Check numerical representations in Decimal, Binary, and Hexadecimal.
   - Trace current inputs highlighted in the generated Truth Table.
