# archetype-pandoc

Archetype maven to generate a runnable pandoc skeleton.

## Installation de l'archetype dans le repository maven local

```
>> git clone https://github.com/DSI-Ville-Noumea/archetype-pandoc.git
>> cd archetype-pandoc
>> mvn install
```

## Créer un nouveau projet à partir de l'archetype

```
>> cd ..
>> mvn archetype:generate -DarchetypeArtifactId=archetype-pandoc -DarchetypeGroupId=nc.noumea.mairie -DarchetypeVersion=1.00.00 -DappName=myApp
```



