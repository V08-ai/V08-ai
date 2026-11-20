# Victor Lavolé

Je construis [Temi](https://temiapp.com), un logiciel de marchés publics pour les acheteurs publics et les entreprises.

Mon sujet : les données ouvertes de l'achat public français, telles qu'elles sont publiées, et ce qu'on peut en tirer sans se tromper.

## Le code que je publie

Les règles de lecture appliquées dans Temi, avec leurs tests, sous licence Apache 2.0.

- **[notation-prix](https://github.com/V08-ai/notation-prix)** : les formules de notation du critère prix de la fiche DAJ de 2024, en Python et en JavaScript, avec une [calculatrice en ligne](https://v08-ai.github.io/notation-prix/).
- **[decp-lecture](https://github.com/V08-ai/decp-lecture)** : lire les données essentielles de la commande publique (DECP) consolidées sans se tromper, avec les montants fiables, les groupements et les personnes physiques. En SQL pour DuckDB.
- **[scdl-collectivites](https://github.com/V08-ai/scdl-collectivites)** : lire les délibérations et les budgets des collectivités au format SCDL sans compter deux fois un même budget, et le texte de leurs PDF, scans compris.

## Les données que je travaille

- **Les marchés attribués** : les données essentielles de la commande publique (DECP), dans la consolidation de decp.info.
- **Les avis de marché** : BOAMP et TED.
- **Ce qui précède l'avis** : les délibérations et les budgets des collectivités au format SCDL, les programmations d'achats publiées par les collectivités et par l'État.
- **Les organisations** : le répertoire Sirene, pour savoir qui achète et qui répond.

## Les standards

Temi range ses données selon les standards ouverts de l'Open Contracting Partnership : OCDS pour la passation des marchés, OC4IDS pour les projets d'infrastructure. Temi publie une [extension française d'OCDS](https://github.com/temiapp/ocds_fr_extension).
