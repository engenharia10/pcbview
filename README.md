# PCBView

Visualizador de placas e esquemáticos no navegador — também instalável como aplicativo (PWA).

- Placas `.pcb` e esquemáticos `.sch` (binário e ASCII)
- Placas `.PcbDoc` e esquemáticos `.SchDoc`
- Camadas, componentes, redes, BOM, medição, rotação da vista e visualização 3D (com modelos STEP)
- Gera o esquemático a partir da placa; cria e edita esquemáticos e salva em `.sch` ou `.SchDoc` (ASCII)

Os arquivos são abertos localmente, no próprio navegador: nada é enviado para servidores.

Esta é a versão publicada (minificada) — versão 1.6.23.

Bibliotecas incluídas: [three.js](https://threejs.org) (MIT) e [occt-import-js](https://github.com/kovacsv/occt-import-js) (LGPL-2.1); licenças em `vendor/`.

Footprints da [biblioteca oficial do KiCad](https://gitlab.com/kicad/libraries/kicad-footprints) (CC-BY-SA 4.0, com exceção para uso em projetos) são baixados sob demanda e guardados no navegador.
