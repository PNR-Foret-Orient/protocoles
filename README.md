# Définition de protocoles de suivi

Protocoles pour le module de suivi générique de géonature : https://github.com/PnX-SI/gn_module_monitoring

## Installation d'un protocole

Ce dépôt doit être téléchargé dans le répertoire `/contrib` de votre l'installation du module.

Le chemin est probablement le suivant : `/home/geonatureadmin/gn_modules_monitoring/contrib`

Vous devez activer le `virtualenv` en tant que `geonatureadmin`, puis vous pouvez installer le protocole :

```
source ~/geonature/backend/venv/gn_modules_monitoring/contrib
flask monitorings install <mon_chemin_absolu_vers_l_archive>/<protocole> <protocole>
```
