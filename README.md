Pour chaque API, lister au 5 à 8 demandes de service possible pour une application cliente:

GitHub :
Pull
Push 
Check
Create repository

Openweathermap :
Recuperer la méteo par :
Le nom de la ville (api.openweathermap.org/data/2.5/forecast?q={city name},{country code})
Les coordonnées de la ville (api.openweathermap.org/data/2.5/forecast?lat={lat}&lon={lon})
L'id de la ville (api.openweathermap.org/data/2.5/forecast?id={city ID})
Trouver les témpératures minimum et maximum d'une ville

Lister des requêtes POST :

Crée un Gist : POST /gists
Fork un Gist : POST /gists/:id/forks
Creer un repos : POST /user/repos


Lister des requêtes GET :

Recuperer les contributeurs d'un repo : GET /repos/:owner/:repo/contributors
Recuperer les tags d'un repo : GET /repos/:owner/:repo/tags
Lister les repos : GET /user/repos
Lister les repos d'un utilisateur spécifique : GET /users/:username/repos
Recuperer un repos : GET /repos/:owner/:repo


Accès avec token :
GET https://api.github.com/user?access_token=f0bf1de639593cf35ee053da539f40196c4224a6

{
  "login": "Enzo-bianchi",
  "id": 9719937,
  "avatar_url": "https://avatars.githubusercontent.com/u/9719937?v=3",
  "gravatar_id": "",
  "url": "https://api.github.com/users/Enzo-bianchi",
  "html_url": "https://github.com/Enzo-bianchi",
  "followers_url": "https://api.github.com/users/Enzo-bianchi/followers",
  "following_url": "https://api.github.com/users/Enzo-bianchi/following{/other_user}",
  "gists_url": "https://api.github.com/users/Enzo-bianchi/gists{/gist_id}",
  "starred_url": "https://api.github.com/users/Enzo-bianchi/starred{/owner}{/repo}",
  "subscriptions_url": "https://api.github.com/users/Enzo-bianchi/subscriptions",
  "organizations_url": "https://api.github.com/users/Enzo-bianchi/orgs",
  "repos_url": "https://api.github.com/users/Enzo-bianchi/repos",
  "events_url": "https://api.github.com/users/Enzo-bianchi/events{/privacy}",
  "received_events_url": "https://api.github.com/users/Enzo-bianchi/received_events",
  "type": "User",
  "site_admin": false,
  "name": "Enzo BIANCHI",
  "company": null,
  "blog": null,
  "location": "France",
  "email": null,
  "hireable": null,
  "bio": null,
  "public_repos": 2,
  "public_gists": 0,
  "followers": 3,
  "following": 1,
  "created_at": "2014-11-13T13:34:07Z",
  "updated_at": "2015-11-17T12:02:05Z",
  "private_gists": 0,
  "total_private_repos": 5,
  "owned_private_repos": 5,
  "disk_usage": 9435,
  "collaborators": 3,
  "plan": {
    "name": "micro",
    "space": 976562499,
    "collaborators": 0,
    "private_repos": 5
  }
}
