# Planilha Datilografada

Uma planilha no navegador com cara de bloco colunar batido à máquina: fita bicolor preta e vermelha, corretivo sobre o que foi alterado, traço duplo de total e som de teclas (opcional).

**Abrir:** https://bruno475beep.github.io/planilha-datilografada/

- Fórmulas em português, com `;` entre argumentos: `=SOMA(C5:C12)`, `=MÉDIA(…)`, `=MÁX(…)`, `=MÍN(…)`, `=CONT(…)`, `=ARRED(x;2)`, `=SE(cond;a;b)`, `=ABS(x)`.
- Números no padrão brasileiro (`1.234,56`); negativos saem em vermelho.
- Seleção de várias células: arraste o mouse, Shift+clique ou Shift+setas (Ctrl+A marca tudo). Negrito, sublinhado, total, fita vermelha, Del e Ctrl+C valem para a faixa.
- Apagar uma célula devolve a cor do papel; só bater por cima deixa a mancha de corretivo.
- Cola blocos copiados do Excel e copia de volta.
- Tudo fica salvo só no seu navegador (localStorage). Não há servidor, conta nem rastreamento.

Um arquivo só (`index.html`), sem dependências além das fontes do Google Fonts (Special Elite, Courier Prime, Barlow Condensed).
