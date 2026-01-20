# 📚 Libft – 42

La **Libft** est le premier projet de l’école 42.  
L’objectif est de créer une bibliothèque personnelle en C, regroupant des fonctions usuelles de la libc ainsi que des fonctions supplémentaires, réutilisables dans les projets futurs.

Cette version de la libft inclut également :
- **ft_printf**
- **get_next_line**

---

## 🛠️ Fonctions implémentées

### 🔹 Fonctions de la libc (Partie 1)

- `ft_isalpha`
- `ft_isdigit`
- `ft_isalnum`
- `ft_isascii`
- `ft_isprint`
- `ft_strlen`
- `ft_memset`
- `ft_bzero`
- `ft_memcpy`
- `ft_memmove`
- `ft_strlcpy`
- `ft_strlcat`
- `ft_toupper`
- `ft_tolower`
- `ft_strchr`
- `ft_strrchr`
- `ft_strncmp`
- `ft_memchr`
- `ft_memcmp`
- `ft_strnstr`
- `ft_atoi`
- `ft_calloc`
- `ft_strdup`

---

### 🔹 Fonctions supplémentaires (Partie 2)

- `ft_substr`
- `ft_strjoin`
- `ft_strtrim`
- `ft_split`
- `ft_itoa`
- `ft_strmapi`
- `ft_striteri`
- `ft_putchar_fd`
- `ft_putstr_fd`
- `ft_putendl_fd`
- `ft_putnbr_fd`

---

## 🖨️ ft_printf

Implémentation personnalisée de la fonction `printf`.

### Conversions supportées :
- `%c` caractère
- `%s` chaîne de caractères
- `%p` pointeur
- `%d` / `%i` entier signé
- `%u` entier non signé
- `%x` / `%X` hexadécimal
- `%%` caractère `%`

📌 Gestion correcte de la mémoire et du nombre de caractères affichés.

---

## 📄 get_next_line

Fonction permettant de lire un fichier **ligne par ligne**, à partir d’un descripteur de fichier.

### Caractéristiques :
- Support de **plusieurs fd** simultanément
- Gestion des buffers statiques
- Pas de fuites mémoire
- Fonctionne avec ou sans `\n`

Prototype :
```c
char *get_next_line(int fd);
```


## Author

mleineku – 42 School Student

## License

This project is open-source and reusable for personal or educational purposes.
  
