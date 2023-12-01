# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'état (_state_) pour contrôler l'affichage d'un composant  ✔️
- les composants enfants et les _props_ qu'on leur passe  ✔️
- le déclenchement d'instructions en fonction des actions de l'utilisateur ✔️
- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props  ✔️
- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant
- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext` ✔️

## 💻 J'utilise

### Un exemple personnel commenté ✔️

export default function Header() {
  const router = useRouter();
  return (
    <Box
      sx={{
        bgcolor: 'primary.main',
        height: '15vh',
        display: 'flex',
        alignItems: 'center',
        justifyContent: 'center',
      }}
    >
      <Button onClick={() => router.replace('/')}>
        <Typography sx={{ color: 'primary.contrastText' }} variant="h1">
          Chara'Pocket
        </Typography>
      </Button>
    </Box>
  );
}
### Utilisation dans un projet ✔️

https://github.com/Roblin-Blondeel-Josue/character-in-pocket/tree/main

Description : Voici le front end d'un projet de gestions de fiches de jdr

### Utilisation en production si applicable❌ 

[lien du projet](...)

Description :

### Utilisation en environement professionnel  ✔️

Description : Le frontEnd de mon entreprise repose sur du react/Next

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
