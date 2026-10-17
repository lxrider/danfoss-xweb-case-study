# Danfoss / XWEB : qui peut agir sur une installation frigorifique ?

Étude de cas indépendante d'Offensive Security Assessment sur les incidents de supervision frigorifique d'octobre 2026 dans le contexte des **grandes et moyennes surfaces (GMS) alimentaires** : surface observable, chemins d'administration, droits de modification des réglages frigorifiques et conditions de reprise.

**État : prépublication v0.5, en revue privée. La diffusion publique attend l'accord explicite de l'auteur.**

Lire [l'étude](ETUDE.md). Elle examine trois questions complémentaires :

- **Autorité numérique et protections :** droits de modification des consignes, limites applicatives et alarmes ; indépendance des protections.
- **Délégation des accès et responsabilités :** enquêtes auprès des frigoristes, chaîne de maintenance, révocation et continuité opérationnelle.
- **Investigation offensive et raisonnement tactique :** OSINT/EASM, frontières de confiance, six chemins candidats, hypothèses concurrentes et conditions de récupération.

Le manuscrit distingue observations, déclarations, documentation produit, hypothèses et inconnues. Les questionnaires sont volontaires et déclaratifs, recueillis auprès de professionnels du froid ; **les enseignes, DSI de la distribution et exploitants de magasins n'ont pas fait l'objet d'entretiens directs documentés**. La photographie XWEB n'a pas fait l'objet d'une authentification forensique. Le vecteur initial, l'autorité multisite effectivement utilisée et l'origine de la première écriture anormale acceptée demeurent indéterminés.

L'annexe A relie les résultats de l'investigation à des vérifications opérationnelles, avec leurs niveaux de preuve, les responsabilités à établir et les résultats attendus. Elle s'appuie sur IEC 62443, les recommandations ANSSI, MITRE ATT&CK for ICS et INL CCE ; elle ne constitue pas une évaluation de conformité.

Le dossier contient uniquement le manuscrit assaini, ses références publiques, les [modalités de correction](CORRECTIONS.md) et la [licence CC BY 4.0](LICENSE.md) applicable aux textes originaux. Les photographies, données de questionnaires et informations d'installations tierces restent hors du dépôt.

| Fichier | Rôle |
|---|---|
| [ETUDE.md](ETUDE.md) | Manuscrit v0.5 et annexe A de correspondance opérationnelle. |
| [README.md](README.md) | Présentation, état éditorial et conditions de diffusion. |
| [CORRECTIONS.md](CORRECTIONS.md) | Modalités de retour et journal des corrections. |
| [LICENSE.md](LICENSE.md) | Licence CC BY 4.0 adoptée pour les textes originaux et périmètre des droits. |
| `.gitignore` | Réduction des ajouts accidentels aux cinq fichiers prévus. |

Les fichiers déjà suivis, les ajouts forcés et l'historique Git exigent un contrôle distinct du contenu. Le `.gitignore` apporte une précaution complémentaire.

Les corrections techniques sourcées sont les bienvenues. Pour signaler un incident ou une vulnérabilité, utiliser les canaux officiels du fabricant ou du CERT compétent.

**Auteur (pseudonyme) : lxrider.** Les textes originaux sont placés sous **CC BY 4.0**. La diffusion publique reste soumise à une décision explicite distincte ; le dépôt demeure privé pendant la revue.

