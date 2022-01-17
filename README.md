# Dell-screen-luminosity
Commandes bat permettant de controler la luminosité de l'écran Dell


### Pour descendre la lum par incréments de 10 (le premier 10 est le code qui correspond à la luminosité, 12 pour le contraste)
```bash
"C:\Program Files (x86)\Dell\Dell Display Manager\ddm.exe" /DecControl 10 10
```

### Régler la luminosité par incréments de 10
```bash
::"C:\Program Files (x86)\Dell\Dell Display Manager\ddm.exe" /IncControl 10 10
```

### Pour régler la luminosité à un niveau précis
```bash
"C:\Program Files (x86)\Dell\Dell Display Manager\ddm.exe" /SetBrightnessLevel 100
```