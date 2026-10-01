# L5A4 Kalagar

Creados por Kalagar y recopilados y adaptados para Foundry VTT por Panakin.

## Requisitos

Foundry VTT 14 y L5R Unofficial (`l5r4`). La instalación manual previa ha sido probada por Panakin en Foundry 14.368, con l5r4 3.3.1.

## Instalación

En la configuración inicial de Foundry: Módulos → Instalar módulo.
Pega esta URL en el campo URL del manifiesto:

```text
https://raw.githubusercontent.com/fcerezo/l5a-4e-compendios-kalagar/main/module.json
```

Pulsa Instalar, entra en tu mundo y activa **L5A4 Kalagar** en Administrar módulos.
Abre la pestaña Compendios para consultar el contenido.

## Contenido

44 packs: 36 de Items, 5 de macros, 2 de escenas y 1 de diarios.

## Instalaciones anteriores

La versión 1.0.3 cambia el identificador técnico de `panakin-no-densetsu` a `l5a4-kalagar`. Foundry lo reconocerá como un módulo distinto: instálalo mediante la URL del manifiesto y activa **L5A4 Kalagar**. Desactiva el módulo anterior para evitar mostrar ambos juegos de compendios.

El cambio de identificador también cambia los UUID de los compendios. Los enlaces que apunten a `Compendium.panakin-no-densetsu.*` requieren actualizarse a `Compendium.l5a4-kalagar.*`. Conserva una copia de seguridad de la instalación anterior, especialmente si editaste sus packs directamente. Los Items ya importados al mundo permanecen allí, aunque sus referencias al compendio original pueden necesitar actualización.

Para instalación manual, la carpeta debe ser `Data/modules/l5a4-kalagar/` y contener `module.json`.

## Recursos y enlaces

Las bases LevelDB se conservan sin modificar. Algunos recursos apuntan a `worlds/heroes-de-rokugan-iii/` y no vienen en el paquete. Algunos enlaces remiten a compendios del mundo original o a `L5R-4e-Compendium`. Imágenes, enlaces y algunas funciones de las escenas pueden requerir esos recursos en el destino. Las macros no se ejecutan automáticamente.

## Publicar una actualización

Incrementa `version` en `module.json`, reconstruye el ZIP con ese mismo manifiesto y los packs actualizados, y sube ambos archivos. Conserva estable la URL de manifiesto. Los usuarios podrán buscar actualizaciones desde Foundry.
