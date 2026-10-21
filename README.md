# PCBView

Visualizador de placas e esquemáticos no navegador — também instalável como aplicativo (PWA).

- Placas `.pcb` e esquemáticos `.sch` (binário e ASCII)
- Placas `.PcbDoc` e esquemáticos `.SchDoc`
- Camadas, componentes, redes, BOM, medição, rotação da vista e visualização 3D (com modelos STEP)
- Gera o esquemático a partir da placa; cria e edita esquemáticos e salva em `.sch` (ASCII) ou `.SchDoc` (binário, como o Altium)

Os arquivos são abertos localmente, no próprio navegador: nada é enviado para servidores.

Esta é a versão publicada (minificada) — versão 1.7.52.

Bibliotecas incluídas: [three.js](https://threejs.org) (MIT), [occt-import-js](https://github.com/kovacsv/occt-import-js) (LGPL-2.1) e [Clipper](http://www.angusj.com/clipper2/) (Boost); licenças em `vendor/`.

Footprints e símbolos das bibliotecas oficiais do KiCad ([footprints](https://gitlab.com/kicad/libraries/kicad-footprints), [símbolos](https://gitlab.com/kicad/libraries/kicad-symbols); CC-BY-SA 4.0, com exceção para uso em projetos) além das bibliotecas da [Espressif](https://github.com/espressif/kicad-libraries) (CC-BY-SA 4.0, mesma exceção) e da [SparkFun](https://github.com/sparkfun/SparkFun-KiCad-Libraries) (CC-BY 4.0), são baixados sob demanda e guardados no navegador.
