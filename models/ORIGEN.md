# Origen de los modelos

Anota aquí cada modelo que añadas: archivo, herramienta o web de origen, fecha y licencia.

| Archivo | Origen | Fecha | Licencia o condiciones |
| --- | --- | --- | --- |
| `personaje/nino.glb` | Modelado por script en Blender (`scripts/blender/nino.py`, ver `scripts/blender/README.md`). Esqueleto copiado de la Universal Animation Library de Quaternius (solo nombres, jerarquía y orientaciones; posiciones adaptadas). | 4 oct 2026 | Propio; el esqueleto de referencia es CC0 1.0 (Quaternius) |
| `personaje/nino-explorador.glb` | Protagonista «explorador» montado por script en Blender (`scripts/blender/protagonista.py`) con dos paquetes gratuitos de Quaternius descargados de itch.io (versión Standard, 0 $): **Universal Base Characters** (quaternius.itch.io/universal-base-characters; cabeza, ojos y cejas del cuerpo base femenino y el peinado `Hair_SimpleParted`, recortado al flequillo) y **Modular Character Outfits – Fantasy** (quaternius.itch.io/modular-character-outfits-fantasy; traje `Female_Ranger` sin la hombrera ni el segundo cinturón). Proporciones de niño, reposo de la Universal Animation Library, texturas recoloreadas a la paleta y capa generada por código. Originales en `fuentes/quaternius-personajes/` (no van en git). | 5 oct 2026 | CC0 1.0 (Quaternius) |
| `personaje/animaciones.glb` | Universal Animation Library de Quaternius (quaternius.com), 10 animaciones, preparadas con `scripts/prepara-personaje.mjs` | 4 oct 2026 | CC0 1.0 |
| `caballo/caballo.glb` | «Horse» del Animated Animal Pack de Quaternius (quaternius.com), descargado de poly.pizza/m/qvTrSG9pZF. Original en `fuentes/caballo/horse-quaternius.glb`; `scripts/prepara-caballo.mjs` deja solo las animaciones tranquilas. En el juego se recolorea y se suavizan sus normales; la silla y la manta se hacen por código. | 4 oct 2026 | CC0 1.0 |
| `aldeanos/animaciones.glb` | Universal Animation Library de Quaternius (13 animaciones), preparada con `scripts/prepara-aldeanos.mjs`. | 4 oct 2026 | CC0 1.0 |
| `aldeanos/animaciones-oficios.glb` | **KayKit Character Animations 1.1** de Kay Lousberg (kaylousberg.itch.io, esqueleto Rig_Medium; originales en `fuentes/kaykit-animaciones/`, no van en git): Hammering, Digging, Sawing, Chopping, Working_A, Fishing_Idle, Fishing_Cast, Holding_A, Waving, Cheering, Sit_Floor_Idle, Sit_Chair_Idle, Lie_Idle, PickUp, Idle_B y Throw. Adaptadas a nuestro esqueleto (el de la Universal Animation Library) con `scripts/prepara-oficios.mjs`, que además compone clips (andar con un cesto, saludar, celebrar y pescar sentado, echar migas desde un banco). | 5 oct 2026 | CC0 1.0 (Kay Lousberg) |
| `animales/gallina.glb`, `animales/pollito.glb`, `animales/perro.glb` | Quaternius (poly.pizza/m/Z3RCoCYss4, LH96IMq0rE, y4wdQpg767). Preparados con `scripts/prepara-animales.mjs` (sin animaciones de morir ni atacar). | 4 oct 2026 | CC0 1.0 |
| `aldeanos/estilo/{hombre,mujer,anciano,anciana,nina,chico}.glb` | Modelados por script en Blender (`scripts/blender/aldeanos.py`, ver `scripts/blender/README.md`), con el mismo estilo y esqueleto que `personaje/nino.glb` (copiado de la Universal Animation Library de Quaternius: nombres, jerarquía y orientaciones). | 4 oct 2026 | Propio; el esqueleto de referencia es CC0 1.0 (Quaternius) |

## Otros recursos

| Archivo | Origen | Fecha | Licencia o condiciones |
| --- | --- | --- | --- |
| `public/fonts/im-fell-english*.woff2` | Tipografía IM Fell English (Igino Marini), descargada de Google Fonts | 4 oct 2026 | SIL Open Font License 1.1 (gratuita, uso comercial permitido) |
| `public/fonts/cinzel.woff2` | Tipografía Cinzel (Natanael Gama), variable, subconjunto latino, de Google Fonts. Rótulos de lugar y nombres en los diálogos. | 4 oct 2026 | SIL Open Font License 1.1 |
| `public/fonts/alegreya*.woff2` | Tipografía Alegreya (Juan Pablo del Peral, Huerta Tipográfica), variable y cursiva, subconjunto latino, de Google Fonts. Texto de diálogos y misiones. | 4 oct 2026 | SIL Open Font License 1.1 |

Todo lo demás (escenario, texturas y sonido) se genera por código.
