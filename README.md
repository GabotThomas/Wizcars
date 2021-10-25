# Lien du site 
[https://gabotthomas.github.io/Wizcars/](https://gabotthomas.github.io/Wizcars/)

# Installation du repository

```bash
git clone https://github.com/GabotThomas/Wizcars.git
```

## Creer une branche 

```bash
git checkout -b nom_de_la_branche
```

# Ajouter les modification a la branche master

```bash
git pull origin master
//Regler les conflicts si il y'en a, Si conflit:
git add fichier modifié
git commit -m "nom du commit"
git push origin nom_de_la_branche

git checkout master
git merge nom_de_la_branche
```



# HTML SCSS Starter

## Initialization

```bash
npm install
```

## Run

### To compile scss to css

```bash
npm run scss
```

#### In watch mode

```bash
npm run scss-watch
```

## Preview

Open `index.html` in your browser and enjoy!
