# Epic React — notes et exercices

Les sept ateliers de la formation [Epic React](https://www.epicreact.dev/) de **Kent C. Dodds**, regroupés dans un dépôt personnel.

| Module | Sujet |
| --- | --- |
| [react-fundamentals](react-fundamentals/) | Fondamentaux, JSX, composants et formulaires |
| [react-hooks](react-hooks/) | Hooks, état et effets |
| [advanced-react-apis](advanced-react-apis/) | Reducers, contexte, portails et APIs avancées |
| [react-suspense](react-suspense/) | Suspense et chargement des données |
| [advanced-react-patterns](advanced-react-patterns/) | Composition et patterns de composants |
| [react-performance](react-performance/) | Optimisation des performances |
| [react-server-components](react-server-components/) | Composants serveur et actions |

## Organisation et provenance

Chaque module conserve ses fichiers, ses exercices, son README et sa licence d’origine. Ce dépôt regroupe des copies des modules ; ce ne sont pas des sous-modules Git. Les dépendances sont propres à chaque atelier.

Le dépôt reprend l’historique du dépôt personnel `LignacAntony/react-suspense`, renommé en `epic-react`. Les six autres ateliers sont importés dans leur état local au moment du regroupement, sans importer leur historique Git. Les commits sources et les suppressions locales sont consignés dans [sources.json](sources.json).

## Travail personnel sauvegardé

Les dossiers `playground` étaient ignorés par Git dans les dépôts d’origine. Leur contenu au moment du regroupement est sauvegardé dans [saved-playgrounds](saved-playgrounds/), avec un sous-dossier par module. L’image personnalisée de l’atelier Suspense est conservée dans [saved-assets](saved-assets/).

Les `playground` de travail restent ignorés par Git. Pour sauvegarder une progression ultérieure, recopier les fichiers concernés dans `saved-playgrounds/<module>/` puis les committer. Les outils de setup des ateliers peuvent réinitialiser les playgrounds : les sauvegardes séparées permettent de conserver ce travail.

## Utilisation

Ouvrir le README du module souhaité. Chaque atelier dispose de son propre `package.json` et de ses commandes npm ; exécuter les commandes depuis le sous-dossier du module. Le regroupement n’a pas fait l’objet d’une validation du lancement des applications, et les fonctions du workshop qui dépendent de la structure du dépôt Git peuvent nécessiter une adaptation.

## Licence

Contenu pédagogique original de Kent C. Dodds / Epic Web. Les licences et attributions sont conservées dans chaque module. Voir également [LICENSE.md](LICENSE.md).
