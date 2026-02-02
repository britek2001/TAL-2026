# Démonstration de la réécriture OULIPO

## Texte Original
> Le chat noir traverse silencieusement le jardin à la recherche d'une souris.
> Le vieil homme lit son journal en buvant un café chaud.
> La forêt mystérieuse abrite des créatures anciennes et des secrets oubliés.
> Les enfants jouent gaiement dans le parc ensoleillé de cet après-midi d'été.

---

## Versions Transformées (Probabilité : 60%)

### Version 1 : 'Random' (Aléatoire)
**Stratégie :** Navigation bidirectionnelle (Hypernymes ou Hyponymes au hasard).

Le chat noir traverse silencieusement le jardin à la recherche d'une **[souris]**. Le vieil homme **[lit]** son journal en buvant un café chaud. La **[groupement]** mystérieuse abrite des créatures anciennes et des secrets oubliés. Les enfants jouent gaiement dans le parc ensoleillé de cet **[adieu]** d'été.

### Version 2 : 'Specific' (Précision)
**Stratégie :** Descente vers les Hyponymes (termes techniques ou précis).

Le chat noir traverse silencieusement le jardin à la **[sonde]** d'une souris. Le vieil homme lit son journal en buvant un café chaud. La **[sylva]** mystérieuse abrite des créatures anciennes et des secrets oubliés. Les enfants jouent gaiement dans le parc ensoleillé de cet après-midi d'été.

### Version 3 : 'General' (Abstraction)
**Stratégie :** Montée vers les Hypernymes (concepts globaux ou vagues).

Le chat noir traverse silencieusement le **[agrégation]** à la **[acte]** d'une **[souris]**. Le vieil **[juvénile]** **[lit]** son **[presse]** en buvant un café chaud. La forêt mystérieuse abrite des créatures anciennes et des secrets oubliés. Les enfants jouent gaiement dans le parc ensoleillé de cet **[reconnaissance]** d'été.

---

## Tableau des transformations observées

| Mot Original | Type (POS) | Version 1 (Random) | Version 2 (Specific) | Version 3 (General) | Logique de transformation |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Forêt | NOM | [groupement] | [sylva] | (non changé) | Terme technique vs catégorie de groupe |
| Après-midi | NOM | [adieu] | (non changé) | [reconnaissance] | Lien sémantique via l'acte social |
| Recherche | NOM | (non changé) | [sonde] | [acte] | Action précise vs concept global |
| Homme | NOM | [homme] | (non changé) | [juvénile] | Navigation dans la branche humaine |
| Jardin | NOM | (non changé) | (non changé) | [agrégation] | Vue comme une collection de plantes |
| Journal | NOM | (non changé) | (non changé) | [presse] | Substitution par le secteur d'activité |
| Souris | NOM | [souris] | (non changé) | [souris] | Sélectionné mais sans synonyme distant |
