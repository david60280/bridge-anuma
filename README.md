- Installez Go 

```sudo apt install golang-go```

- le node doit être lancé et synchro

- ./anumad --utxoindex --allow-submit-block-when-not-synced

- Installation du Bridge ( ici le bridge Bugna )

```git clone https://github.com/david60280/bridge-anuma.git```

```cd bridge-anuma```

```cd cmd/kaspabridge/;go build .;./kaspabridge```

 Les paramètres actuel sont les paramètres pour un KS0 , vous pouvez les modifiez avec la commande:

```nano config.yalm```

Dedans il y a l'ip du node + les paramètres

- Ouvrez le port 5555 pour faire la liaison entre votre ASIC ou GPUs et le Bridge:

```sudo ufw allow 5555```

- Vous pouvez dés maintenant mettre votre Asic ou vos GPUs, pour cela:

  Dans l'url veuillez entrer:

```stratum+tcp://ip_local_du_bridge:5555```

- Pour démarrer le Bridge pour les prochaines fois:
(soyez sur d'être dans le dossier cmd/kaspabridge)

```screen ./kaspabridge```
