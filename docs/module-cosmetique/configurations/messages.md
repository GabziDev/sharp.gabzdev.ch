---
sidebar_position: 1
---

# Messages
Pour personnaliser les messages de ce module, vous devez vous rendre dans le dossier **plugin** de votre serveur, puis dans le dossier de configuration de votre API, ensuite dans le dossier **languages**. 

Choisissez l’un de vos fichiers de langue, puis vous pourrez personnaliser les messages du module de cosmétique qui se trouvent sous la section `cosmetique`.

## Exemple
```yml
cosmetique:
  prefix: '&dCosmétique Module &8> &7'
  notavailable: '<prefix_cosmetique>Non disponible.'
  ui:
    no: Non
    cosmetique:
      equip: '&eClic pour équiper le cosmétique'
      unequip: '&eClic pour déséquiper le cosmétique'
      buy: '&eClic pour acheter le cosmétique'
      title: 'Cosmétique'
      compagnons:
        title: '&6Compagnons'
      tag:
        admin:
          title: 'Gestion des tags'
        title: '§aTags'
      mdc:
        title: '§dMessages de connexion'
...
```

## Variables
| Variable              | Description                                         |
|-----------------------|-----------------------------------------------------|
| `<prefix_cosmetique>` | Affiche le préfixe choisi dans le fichier de langues |
| `<tag_suffix_player>` | Affiche le suffixe du titre que le joueur a équipé  |