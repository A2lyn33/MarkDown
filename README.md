# MarkDown
Bien sûr ! Voici un cours complet sur **Markdown**, un langage de balisage léger et intuitif utilisé pour créer du texte formaté.

---

# 📝 **Cours de Markdown**

Markdown est très utilisé pour écrire de la documentation, des blogs, des fichiers README (comme dans GitHub), etc.

---

## **1. Les Bases de Markdown**

### Texte en **gras**, *italique*, ~~barré~~
```markdown
**Texte en gras**
*Texte en italique*
~~Texte barré~~
```

**Résultat :**
- **Texte en gras**
- *Texte en italique*
- ~~Texte barré~~

### Titres
Les titres sont définis avec des `#`. Plus il y a de `#`, plus le titre est petit.

```markdown
# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
```

**Résultat :**
# Titre de niveau 1  
## Titre de niveau 2  
### Titre de niveau 3  

---

### Listes

#### Liste non ordonnée
Utilisez des `-`, `*`, ou `+` :
```markdown
- Élément 1
- Élément 2
  - Sous-élément
  - Sous-élément
```

**Résultat :**
- Élément 1
- Élément 2
  - Sous-élément
  - Sous-élément

#### Liste ordonnée
Utilisez des numéros :
```markdown
1. Élément 1
2. Élément 2
   1. Sous-élément
   2. Sous-élément
```

**Résultat :**
1. Élément 1
2. Élément 2
   1. Sous-élément
   2. Sous-élément

---

### Liens
Créer un lien cliquable :
```markdown
[Texte du lien](https://example.com)
```

**Résultat :** [Texte du lien](https://example.com)

---

### Images
Pour ajouter une image :
```markdown
![Texte alternatif](URL_de_l_image)
```

Exemple :
```markdown
![Chat mignon](https://placekitten.com/200/300)
```

**Résultat :**  
![Chat mignon](https://placekitten.com/200/300)

---

## **2. Code et Blocs de Code**

### Code en ligne
Encadrez le code avec des backticks :
```markdown
`mon_code()`
```

**Résultat :** `mon_code()`

---

### Blocs de code
Utilisez trois backticks pour créer un bloc de code :
```markdown
```python
def bonjour():
    print("Salut, Markdown !")
```
```

**Résultat :**
```python
def bonjour():
    print("Salut, Markdown !")
```

---

## **3. Citations et Séparateurs**

### Citations
Utilisez `>` pour ajouter une citation :
```markdown
> Ceci est une citation.
>> Ceci est une sous-citation.
```

**Résultat :**
> Ceci est une citation.
>> Ceci est une sous-citation.

---

### Séparateurs
Utilisez `---` ou `***` pour créer une ligne horizontale :
```markdown
---
```

**Résultat :**
---

---

## **4. Tables**

Créez des tables facilement :
```markdown
| Colonne 1 | Colonne 2 | Colonne 3 |
|-----------|-----------|-----------|
| Valeur 1  | Valeur 2  | Valeur 3  |
| Valeur 4  | Valeur 5  | Valeur 6  |
```

**Résultat :**
| Colonne 1 | Colonne 2 | Colonne 3 |
|-----------|-----------|-----------|
| Valeur 1  | Valeur 2  | Valeur 3  |
| Valeur 4  | Valeur 5  | Valeur 6  |

---

## **5. Checklists**

Ajoutez des cases à cocher :
```markdown
- [x] Tâche terminée
- [ ] Tâche en cours
```

**Résultat :**
- [x] Tâche terminée
- [ ] Tâche en cours

---

## **6. Extensions utiles**

### Notes de bas de page
```markdown
Voici une phrase avec une note de bas de page.[^1]

[^1]: Ceci est la note.
```

**Résultat :**  
Voici une phrase avec une note de bas de page.[^1]  
[^1]: Ceci est la note.

---

### Emojis
Utilisez des codes pour ajouter des emojis :
```markdown
:smile: :heart: :+1:
```

**Résultat :** 😄 ❤️ 👍

---

## **7. Pratique**

Voici un exemple complet :
```markdown
# Bienvenue dans Markdown

## Les bases
Markdown est **simple** et _rapide_ à apprendre.

### Une liste d'exemple :
- Élément 1
- Élément 2

## Une table
| Titre 1 | Titre 2 |
|---------|---------|
| Valeur 1 | Valeur 2 |

### Code
```python
def bonjour():
    print("Hello, Markdown!")
```

> Essayez-le !
