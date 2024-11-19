# Projet Principal : SCHOOLY/SCHOLARIS

## Services Techniques
- **Gateway**
    - Spring Cloud Gateway
- **Discovery Service (Registration Service)**
    - Eureka Server
- **Configuration Service**

## Modules
### Inscription (Étudiant/Élève/Écolier)
- **Entités**
    - Personne
    - Programme (Développement avancé, Journée continue, etc.)
    - Niveau Étude (CI, Cp, CM2, Terminale, etc.)
    - Cycle (Maternelle, Préscolaire, Lycée, etc.)
    - Inscription
- **Enum**
    - Type Niveau Étude
    - Type Inscription (Nouvelle, redoublement, élève, etc.)
    - Type Cycle

### Facturation
- Gestion de la facturation et suivi financier.

### Comptabilité
- Suivi et gestion des comptes financiers.

### Professeur
- Gestion des informations et des emplois du temps des professeurs.

### Emploi du Temps
- Planification et organisation des horaires des cours.

### Cours
- Gestion des matières et des contenus pédagogiques.

### Devoir
- Suivi et gestion des devoirs assignés aux élèves.

### Examen
- Organisation et gestion des examens.

### Notes
- Enregistrement et suivi des performances académiques des élèves.


## Representation sous forme de tableau 
| Module           | Description                                                                                      |
|------------------|--------------------------------------------------------------------------------------------------|
| Inscription      | Gère les inscriptions des étudiants/élèves/écoliers, incluant les informations personnelles, les programmes, les niveaux d'études, et les cycles. |
| Facturation      | Responsable de la gestion de la facturation et du suivi financier.                               |
| Comptabilité     | Suivi et gestion des comptes financiers.                                                         |
| Professeur       | Gestion des informations et des emplois du temps des professeurs.                                |
| Emploi du Temps  | Planification et organisation des horaires des cours.                                            |
| Cours            | Gestion des matières et des contenus pédagogiques.                                               |
| Devoir           | Suivi et gestion des devoirs assignés aux élèves.                                                |
| Examen           | Organisation et gestion des examens.                                                             |
| Notes            | Enregistrement et suivi des performances académiques des élèves.                                 |
