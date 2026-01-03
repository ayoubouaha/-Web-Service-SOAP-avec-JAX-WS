## Opérations disponibles

| Opération | Description | Paramètres | Retour |
|-----------|-------------|-----------|---------|
| **getComptes** | Récupère tous les comptes | Aucun | Liste de Compte |
| **getCompteById** | Récupère un compte par ID | `id: Long` | Compte ou null |
| **createCompte** | Crée un nouveau compte | `solde: double`, `type: TypeCompte` | Compte créé |
| **deleteCompte** | Supprime un compte | `id: Long` | `true` ou `false` |

### Types disponibles

**TypeCompte (Enum) :**
- `COURANT` - Compte courant
- `EPARGNE` - Compte épargne

<img width="1522" height="664" alt="img_1" src="https://github.com/user-attachments/assets/4061be34-00da-48b1-ad94-38b0e35a06e5" />
