




**2. Technique avec Go**


- Installez Go (si vous l'avez déjà passez cette étape):

```sudo apt install golang-go```

- Vérifiez que vous avez la dernière version ( actuellement 1.22 )

```go version```

- Si vous n'avez pas la dernière version, veuillez suivre ce tuto:

https://discord.com/channels/1203051285650210898/1216030537920286850/1216030537920286850

- Lancez votre node ( ici Bugna et synchronisez le )

```cd ~/go/bin && screen -dmS node_bugna ./bugnad```
    Vous pouvez voir le node avec la commande:

```screen -r node_bugna```

- Installation du Bridge ( ici le bridge Bugna )

```git clone https://github.com/K-i-k-k-o/bridge-bugna.git```

```cd bridge-bugna```

```cd cmd/kaspabridge/;go build .;./kaspabridge```

⚠️ Les paramètres actuel sont les paramètres pour un KS0 PRO, vous pouvez les modifiez avec la commande:

```nano config.yalm```

Dedans il y a l'ip du node + les paramètres

- Ouvrez le port 5555 pour faire la liaison entre votre ASIC ou GPUs et le Bridge:

```sudo ufw allow 5555```

- Vous pouvez dés maintenant mettre votre Asic ou vos GPUs, pour cela:

  Dans l'url veuillez entrer:

```stratum+tcp://ip_local_du_bridge:5555```


🎉  C'est bon vous avez réussi la technique avec Go! 🎉 


- Pour démarrer le Bridge pour les prochaines fois:
(soyez sur d'être dans le dossier cmd/kaspabridge)

```screen ./kaspabridge```
**2. Technique avec Go**


- Installez Go (si vous l'avez déjà passez cette étape):

```sudo apt install golang-go```

- Vérifiez que vous avez la dernière version ( actuellement 1.22 )

```go version```

- Si vous n'avez pas la dernière version, veuillez suivre ce tuto:

https://discord.com/channels/1203051285650210898/1216030537920286850/1216030537920286850

- Lancez votre node ( ici Bugna et synchronisez le )

```cd ~/go/bin && screen -dmS node_bugna ./bugnad```
    Vous pouvez voir le node avec la commande:

```screen -r node_bugna```

- Installation du Bridge ( ici le bridge Bugna )

```git clone https://github.com/K-i-k-k-o/bridge-bugna.git```

```cd bridge-bugna```

```cd cmd/kaspabridge/;go build .;./kaspabridge```

⚠️ Les paramètres actuel sont les paramètres pour un KS0 PRO, vous pouvez les modifiez avec la commande:

```nano config.yalm```

Dedans il y a l'ip du node + les paramètres

- Ouvrez le port 5555 pour faire la liaison entre votre ASIC ou GPUs et le Bridge:

```sudo ufw allow 5555```

- Vous pouvez dés maintenant mettre votre Asic ou vos GPUs, pour cela:

  Dans l'url veuillez entrer:

```stratum+tcp://ip_local_du_bridge:5555```


🎉  C'est bon vous avez réussi la technique avec Go! 🎉 


- Pour démarrer le Bridge pour les prochaines fois:
(soyez sur d'être dans le dossier cmd/kaspabridge)

```screen ./kaspabridge```
