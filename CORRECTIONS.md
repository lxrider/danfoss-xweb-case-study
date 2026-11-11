# Corrections et contributions / Corrections and contributions

## Français

Les retours prioritaires portent sur trois questions : ce que journalise exactement une écriture XWEB, les limites réelles d'autorité sur les régulateurs et les protections qui préservent le procédé lorsque la supervision est compromise.

Pour une correction non sensible, proposer une issue ou une pull request avec :

1. La version, la langue et le passage concernés.
2. La contradiction ou correction proposée et son effet sur le raisonnement.
3. La source publique exacte, avec produit, version et section ; ou les conditions d'un essai autorisé décrit sous forme assainie.
4. Le niveau de preuve, les limites et les explications concurrentes.
5. Le passage correspondant dans l'autre langue, si connu.

Distinguer documentation produit, expérience de terrain, essai de faisabilité et observation d'incident. Un essai autorisé ne démontre pas l'utilisation du mécanisme pendant les incidents. Une relecture interne ne constitue pas une validation indépendante extérieure.

Aucune adresse d'installation, aucun compte, identifiant de client, questionnaire individuel, photographie, journal brut ou configuration sensible ne doit être déposé dans les issues, pull requests ou pièces jointes, y compris en revue privée. Les vulnérabilités inédites et les informations permettant de cibler un tiers doivent être signalées par les canaux officiels du fabricant ou du CERT compétent. Les contributions doivent respecter la disponibilité des professionnels en remédiation.

Le mainteneur examine chaque objection et son effet sur les classifications et conclusions, puis intègre les corrections acceptées dans les deux langues par un commit daté. Le motif est conservé dans le journal. Toute donnée sensible découverte demande de traiter aussi l'historique Git et les copies éventuelles ; le `.gitignore` ne suffit pas à la retirer.

## English

Priority feedback concerns three questions: what an XWEB write entry actually records, the real limits of authority over controllers, and the protections that preserve the process when supervision is compromised.

For a non-sensitive correction, propose an issue or pull request containing:

1. The version, language and passage concerned.
2. The challenge or proposed correction and its effect on the reasoning.
3. The exact public source, including product, version and section; or the conditions of an authorised test described in sanitised form.
4. The evidence level, limitations and competing explanations.
5. The corresponding passage in the other language, if known.

Distinguish product documentation, field experience, feasibility testing and incident observation. An authorised test does not demonstrate use of that mechanism during the incidents. Internal review is not independent external validation.

Do not place installation addresses, accounts, client identifiers, individual questionnaire responses, photographs, raw logs or sensitive configurations in issues, pull requests or attachments, including during private review. Report previously undisclosed vulnerabilities and information that could enable targeting of a third party through the manufacturer's or relevant CERT's official channels. Contributions must respect the availability of professionals engaged in remediation.

The maintainer examines each objection and its effect on classifications and conclusions, then incorporates accepted corrections into both languages through a dated commit. The reason is retained in the log. Any sensitive data discovered also requires attention to Git history and possible copies; `.gitignore` does not remove it.

## Journal / Change log

Les entrées historiques v0.5 sont conservées dans leur langue d'origine. / Historical v0.5 entries are preserved in their original language.


| Date | Version | Modification |
|---|---|---|
| 11 novembre / November 2026 | **v1.2-RC2 — candidate GitHub, revue requise / GitHub candidate, review required** | Ajout CTI restreint : rapport OpenAI 2024 (précédent IA qualifié, pas preuve pour 2026), dissociation MITRE G1027/C0066, revendications pro-russes antérieures selon Forescout avec provenance indirecte ; aucun nouveau vecteur, acteur pour novembre ni donnée de victime. Parité FR/EN ; dossier privé exclu. / Targeted CTI addition: qualified historical OpenAI account activity, MITRE group/campaign attribution distinction, earlier pro-Russian claims with secondary sourcing. No new access path, November attribution or victim data; bilingual parity. |
| 10 novembre / November 2026 | **v1.2-RC1 — relecture contradictoire, non publiée / unpublished** | Correctifs RC-10–16 appliqués aux **deux langues** : chronologie et séparation des périmètres, tentative Sekoia bloquée et seconde étape non observée, biais AK-SM 800A/800/AK-SC, cas Ransom-ISAC (31 équipements, 743 événements, un `Alarm Mute` échoué, preuve des identifiants par défaut hors journal), portée de l’avis CISA et du bulletin Copeland, appréciation ANSSI du 21/10 non rétroactivement réfutée, distinction des précédents Danfoss 2022 ; déplacement de l’addendum après les résultats originaux, courte note CTI d’ouverture. H1–H5 et COA inchangés ; **aucun accès initial démontré, aucune publication distante**. / Bilingual adversarial-review corrections; evidence boundaries clarified and original findings restored to the opening; no change to attack-path verdict or remote publication. |
| 10 novembre / November 2026 | **v1.2 candidate — non publiée / unpublished** | Addendum CTI bilingue : attribution C4 **limitée au 11–12 octobre** ; séparation des épisodes d’octobre/novembre ; nouvelles études Sekoia (leurres et partenaire), Ransom-ISAC (cas XWEB PRO du 2/11), Censys, ONYPHE et ACDS ; **contre-lecture DOJ CARR/Z-Pentest et enquête Reuters sur les bases américaines**, sans extension d’attribution ; limites d’EASM, de journalisation et de causation physique préservées. Aucun nouveau vecteur initial démontré, H1–H5 **INDETERMINATE**, COA-A/B/C ouverts. Aucun dépôt distant modifié. / Dated bilingual CTI addendum; C4 attribution scoped to 11–12 October; new research incorporated without claiming shared perpetrators or technical access paths; previous evidence limits and competing hypotheses preserved. No remote publication. |
| 22 octobre / October 2026 | v1.1 — Mise à jour / Update | Reformulation bilingue des quatre constats et de la limite `SEt`/`US` ; remplacement du tableau initial pour faciliter la lecture mobile ; ajout de la déclaration ANSSI du 21/10 (**REPORTED**) et d'une note prudente sur les recommandations XWEB rapportées (PDF courant non vérifié directement) ; précision GTC. Analyse historique préservée : H1–H5 **INDETERMINATE**, COA-A/B/C ouverts. / Bilingual revision of the findings and the `SEt`/`US` bound; mobile-friendly opening; dated ANSSI statement (**REPORTED**) and qualified account of XWEB recovery guidance (current PDF not directly verified); GTC terminology. Historic analysis preserved: H1–H5 **INDETERMINATE**, COA-A/B/C open. |
| 17 octobre 2026 | v0.5, revue privée | Révision éditoriale de la v0.4.2 ; réserves regroupées, provenance précisée, droits XWEB et voie Modbus clarifiés, références corrigées et limites de vérification explicitées. H1–H5 et COA-A/B/C inchangés. |
| 17 octobre 2026 | v0.5, finalisation privée | Ajout de l'annexe A de correspondance opérationnelle ; contrôle des recommandations ANSSI et des domaines IEC 62443 ; mise à jour des accès documentaires et des dates bibliographiques ; renvois explicites pour maintenir la bibliographie avant l'annexe dans GitHub. Corps principal, niveaux de preuve et conclusions conservés. |
| 17 octobre 2026 | v0.5, corrections finales | Vocabulaire adapté au contexte frigorifique, titre précisé et terme « procédé » conservé dans ses emplois techniques. A1 reformulée à partir des écritures apparentes ; R196/C2 et R198/C2 vérifiées dans le guide ANSSI, pp. 94–95, avec transposition aux régulateurs à examiner. Portée technique, fonctions affectables et conséquences métier distinguées ; référence Alsense alignée sur la révision consultée. Niveaux de preuve et conclusions inchangés. |
| 17 octobre 2026 | v0.5, validation documentaire | Chronologie CERT-FR confirmée par la page officielle et son JSON : 12 octobre, 13 octobre et mise à jour des recommandations le 16. Nature des révisions précisée ; README et modalités de contribution complétés. Analyse scientifique conservée. |
| 17 octobre 2026 | v0.5, préparation de la revue privée | Attribution lxrider confirmée ; licence CC BY 4.0 adoptée pour les textes originaux ; mentions et liens harmonisés. Aucune modification du raisonnement scientifique et aucune diffusion publique. |
| 18 octobre 2026 | v1.0 candidate FR + EN | Ouverture centrée sur le problème et quatre constats ; comparaison statique de sept bibliothèques XM679K et frontières de générations ; préparation, émission, acceptation, état actif et effet physique séparés ; propagation locale, protections, gouvernance 25 réponses et comparaisons affecté/épargné précisées ; statut d'ACH, IPOE/AJP-5 et CCE rectifié. Traduction intégrale et parité factuelle contrôlées. H1–H5 INDETERMINATE, COA-A/B/C ouverts. Préparation locale, sans publication. / Problem-led opening and four findings; seven-library static comparison and generation boundaries; preparation, transmission, acceptance, active state and physical effect separated; local propagation, protections, 25-response governance snapshot and affected/spared comparison clarified; actual methodological roles corrected. Full translation and factual parity checked. H1–H5 INDETERMINATE, COA-A/B/C open. Local preparation; no publication. |
| 18 octobre / October 2026 | v1.0 — Publication initiale / Initial publication | Finalisation du statut éditorial au 18 octobre 2026 : retrait des mentions provisoires dans l'accueil, les deux études et la licence. Historique conservé ; contenu scientifique et conclusions inchangés. Intégration au dépôt privé uniquement, sans diffusion publique. / Editorial status finalised on 18 October 2026: provisional wording removed from the README, both studies and the licence. History retained; scientific content and conclusions unchanged. Private-repository integration only; no public dissemination. |
