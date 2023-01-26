# Utilisation de GANSynth
Pour utiliser GANSynth il faut d'abord installer Magenta :
`pip install magenta`    

Nous avons entraîné le réseau qui a généré un checkpoint. N'ayant pas pu mettre le fichier directement dans ce git car trop volumineux, nous l'avons séparé en différentes archives dans le dossier "entraînement". Après extraction, on a dans ce dossier le dossier stage_0000 et les fichiers experiment.json et meta.json .  

Pour générer un audio à partir du réseau entraîné, on effectue la commande `gansynth_generate --ckpt_dir=path\to\entrainement --output_dir=path\to\output --midi_file=path\to\midi`  
Le fichier midi est optionnel.


