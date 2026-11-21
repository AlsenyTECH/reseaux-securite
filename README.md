# Parcours Réseau & Sécurité — semestre 2

Les **quatorze sujets d'exposé** du semestre 2 (Master 1 MCS / TDSI), remis dans l'ordre
du trajet qu'ils décrivent : un utilisateur qui atteint une application, et tout ce qui
se dresse entre les deux.

Chaque étape : le mécanisme, ce qu'il faut connaître par cœur, la paire à ne pas
confondre, un QCM qui corrige et explique, un TP à monter sur ses machines, une fiche
de révision, et le modèle de réponse attendu sur la copie.

- `index.html` : le parcours (19 étapes)
- `videos/` : les vidéos explicatives
- `assets/fonts/` : les polices, pour que le site fonctionne sans connexion

## État

| Étape | Sujet | État |
|---|---|---|
| 1 | Le fil conducteur | écrite |
| 2 | Le laboratoire | écrite |
| 3 | NAC, PacketFence, 802.1X | écrite · vidéo |
| 4 | Micro-segmentation et Zero Trust | écrite |
| 5 | Active Directory et Azure AD | à venir |
| 6 | PKI | à venir |
| 7 | IAM et PAM | à venir |
| 8 | SSO : SAML, OAuth, OpenID Connect | à venir |
| 9 | TP Active Directory | à venir |
| 10 | WAF et proxy | à venir |
| 11 | Sécurité du cloud | à venir |
| 12 | IDS et IPS | à venir |
| 13 | Snort | à venir |
| 14 | Wazuh | à venir |
| 15 | SIEM, EDR, XDR | à venir |
| 16 | CTI et SOAR | à venir |
| 17 | Ce que l'examen attend | écrite |
| 18 | Évaluation chronométrée | écrite |
| 19 | Évaluation finale | à venir |

## Utilisation hors ligne

Télécharger le dépôt (ou le zip), puis ouvrir `index.html` dans un navigateur.
Aucune connexion n'est nécessaire : les polices sont servies localement et il n'y a
aucune dépendance externe.

## Ajouter une étape

Une étape est une `<section class="lesson">` avec `id`, `data-bloc`, `data-part`,
`data-title`. Le sommaire, la numérotation et la progression se construisent tout seuls
à partir de ces attributs. Les composants disponibles :

`objectif` · `retenir` · `prof` · `confusion` · `copie` · `term` · `qcm` · `exo` ·
`fiche` · `chrono` · `seq` (séquence animée, définie dans l'objet `SEQ` du script).

## Licences des fichiers tiers

Polices Caveat, Kalam et Source Sans 3 : SIL Open Font License 1.1
(`assets/fonts/LICENSE-*.txt`).
