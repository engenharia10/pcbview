# PCBView

Visualizador de placas e esquemáticos no navegador — também instalável como aplicativo (PWA).

- P-CAD 2006: placas `.pcb` e esquemáticos `.sch` (binário e ASCII)
- Altium: `.PcbDoc` e `.SchDoc`
- Camadas, componentes, redes, BOM, medição, rotação da vista e visualização 3D (com modelos STEP)
- Gera o esquemático a partir da placa e salva em P-CAD ASCII (`.sch`)

Os arquivos são abertos localmente, no próprio navegador: nada é enviado para servidores.

Esta é a versão publicada (minificada) — versão 1.3.2.

Bibliotecas incluídas: [three.js](https://threejs.org) (MIT) e [occt-import-js](https://github.com/kovacsv/occt-import-js) (LGPL-2.1); licenças em `vendor/`.
