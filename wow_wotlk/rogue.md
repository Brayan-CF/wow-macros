### Macros para el rogue
---
#### PVE macros para el rogue combate

1. Macro para Subidón de adrenalina con modificador de objetivo:
```txt
#showtooltip Subidón de adrenalina
/cast Subidón de adrenalina
/cast Hoja de acero
/cast [mod:shift] Eviscerar
```

2. Macro para Preparación con modificador de objetivo:
```txt
#showtooltip Preparación
/cast Preparación
/cast [mod:shift] Desvanecerse
```

3. Macro para Sprint con CancelAura:
```txt
#showtooltip Sprint
/cancelaura Sigilo
/cast Sprint
```

4. Macro para Patada con enfoque:
```txt
#showtooltip Patada
/cast [target=focus, exists] Patada; Patada
```

5. Macro para Exponer armadura:
```txt
#showtooltip Exponer armadura
/cast Exponer armadura
/startattack
```

