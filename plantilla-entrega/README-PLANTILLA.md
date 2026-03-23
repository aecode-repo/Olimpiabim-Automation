# Plantilla de Entrega - BIM AUTOMATION + IA

Usa esta plantilla como referencia para organizar tus archivos de entrega.

## Estructura de carpeta por ejercicio (Fase 1 - Ronda 1)

```
BIMAUTO_TuEquipo##_Codigo/
  ├── script_principal.py        (o .cs, .dyn)
  ├── funciones_auxiliares.py     (si aplica)
  └── config.json                (si aplica)

BIMAUTO_TuEquipo##_README.pdf
  - Descripcion breve del reto y tu solucion
  - Instrucciones de ejecucion (1 parrafo minimo)
  - Supuestos y limitaciones

BIMAUTO_TuEquipo##_Outputs.zip
  - Capturas de pantalla del resultado
  - Archivos CSV/JSON de salida
  - Evidencias de funcionamiento

BIMAUTO_TuEquipo##_Dependencias.txt (si aplica)
  - Lista de librerias externas usadas
  - Versiones de cada libreria
```

## Estructura para caso grande (Fase 1 - Ronda 2)

Igual que arriba, pero el README debe incluir adicionalmente:
- Pasos de instalacion completos
- Descripcion de inputs/outputs
- Manejo de errores implementado
- Bitacora de uso de IA (si se uso)

## Estructura para Fase 2

```
BIMAUTO_TuEquipo##_VersionFinal/
  └── (codigo actualizado con el cambio puntual)

BIMAUTO_TuEquipo##_Logs_Reportes.pdf
  - Logs de ejecucion
  - Reportes de validacion

BIMAUTO_TuEquipo##_PresentacionFinal.pdf
  - Material de sustentacion tecnica
  - Maximo 10-15 slides recomendado
```

## Ejemplo de nomenclatura

Si tu equipo se llama "BIM Masters" y es el equipo 03:
```
BIMAUTO_BIMMasters03_Codigo/
BIMAUTO_BIMMasters03_README.pdf
BIMAUTO_BIMMasters03_Outputs.zip
BIMAUTO_BIMMasters03_Dependencias.txt
```

## Checklist antes de entregar

- [ ] Mis archivos siguen la nomenclatura obligatoria
- [ ] Mi codigo ejecuta sin errores
- [ ] Incluyo instrucciones de ejecucion en el README
- [ ] Mis outputs estan comprimidos en .zip
- [ ] No incluyo archivos .rvt ni ejecutables sin codigo fuente
- [ ] Ningun archivo supera los 100 MB
- [ ] Si use IA, incluyo la bitacora de uso
- [ ] Mis archivos estan en la carpeta correcta del ejercicio
