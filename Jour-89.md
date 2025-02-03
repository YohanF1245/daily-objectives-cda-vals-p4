# Objectifs journaliers

## Lundi 03/02/2025 :

### Introduction aux Tests Logiciels

- [ ] Comprendre les fondamentaux des tests
  - [ ] Découverte du vocabulaire des tests
    - [ ] Test Fixture
      - ensemble de données permettant d'établir un contexte utilisable pour
    - [ ] Test Suite
    - [ ] Test Case
    - [ ] System Under Test (SUT)
    - [ ] Test Runner
    - [ ] Assertions
      - assertion est une instruction dans un test qui vérifie si une condition est vraie ou fausse. Elle permet de comparer le résultat attendu à celui obtenu lors de l'exécution du code testé, et si la condition n'est pas remplie, le test échoue, indiquant une anomalie dans le comportement du code.
    - [ ] Mocks, Stubs, Spies
    mock : ocks, c’est à dire un objet simulé qui imite le comportement d'une dépendance réelle d'un système. Il permet de remplacer des composants externes (comme des bases de données ou des API) afin de contrôler et prédéfinir leurs réponses, facilitant ainsi l'observation du comportement du code sans les interférences des dépendances réelles.<br>

- [ ] Les différents types de tests
  - [ ] Tests Unitaires
    - [ ] Définition et objectifs
    - [ ] Principes FIRST (Fast, Isolated, Repeatable, Self-validating, Timely)
      - F - Fast (Rapide): Un TU doit être rapide à exécuter (quelques millisecondes),
      - I - Isolated (Isolé) : TUs doivent être indépendants les uns des autres,
      - R - Repeatable : Un TU doit pouvoir être exécuté plusieurs fois avec les mêmes résultats,
      - S - Self-validating (Auto-validant) : Le TU doit avoir un résultat clair et automatique. Les assertions qui valident le comportement du code doivent être explicites,
      - T - Timely (Opportun) : Les TUs doivent être écrits au moment où le code est développé ou peu de temps après. Attendre trop longtemps pour écrire des tests peut mener à des erreurs non détectées et à des retards dans le processus de développement.
    - [ ] Cas d'usage
  - [ ] Tests d'Intégration
    - [ ] Définition et objectifs
    - [ ] Différence avec les tests unitaires
    - [ ] Cas d'usage
  - [ ] Tests End-to-End (E2E)
    - [ ] Définition et objectifs
    - [ ] Pyramide des tests
    - [ ] Cas d'usage

- [ ] Bonnes pratiques des tests
  - [ ] Convention de nommage
  - [ ] Structure des tests (Arrange-Act-Assert / Given-When-Then)
  - [ ] Tests isolés et indépendants
  - [ ] Couverture de code
  - [ ] Documentation des tests 