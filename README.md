# L5A 4ª edición — Compendios de Kalagar

Creados por Kalagar y recopilados y adaptados para Foundry VTT por Panakin.

## Requisitos

Foundry VTT 14 y L5R Unofficial (`l5r4`). La instalación manual previa ha sido probada por Panakin en Foundry 14.368, con l5r4 3.3.1.

## Instalación

En la configuración inicial de Foundry: Módulos → Instalar módulo.
Pega esta URL en el campo URL del manifiesto:

```text
https://raw.githubusercontent.com/fcerezo/l5a-4e-compendios-kalagar/main/module.json
```

Pulsa Instalar, entra en tu mundo y activa **L5A 4ª edición — Compendios de Kalagar** en Administrar módulos.
Abre la pestaña Compendios para consultar el contenido.

## Contenido

44 packs: 36 de Items, 5 de macros, 2 de escenas y 1 de diarios.

## Instalaciones anteriores

Se mantiene el identificador técnico `panakin-no-densetsu` para que la instalación anterior siga siendo el mismo módulo y conserve sus UUID de compendio. El nombre visible y la autoría cambian. Si ya instalaste la copia manual, haz una copia de seguridad de la carpeta del módulo antes de sustituirla por la versión de este repositorio. La versión manual carece de URL de manifiesto: esta versión incorpora las URLs para próximas actualizaciones.

## Recursos y enlaces

Las bases LevelDB se conservan sin modificar. Algunos recursos apuntan a `worlds/heroes-de-rokugan-iii/` y no vienen en el paquete. Algunos enlaces remiten a compendios del mundo original o a `L5R-4e-Compendium`. Imágenes, enlaces y algunas funciones de las escenas pueden requerir esos recursos en el destino. Las macros no se ejecutan automáticamente.

## Publicar una actualización

Incrementa `version` en `module.json`, reconstruye el ZIP con ese mismo manifiesto y los packs actualizados, y sube ambos archivos. Conserva estable la URL de manifiesto. Los usuarios podrán buscar actualizaciones desde Foundry.
