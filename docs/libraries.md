# Libraries

## Feature libraries

Let’s create our first feature library: books.

```bash
nx g lib feature \
--directory books \ --appProject bookstore \
--tags type:feature,scope:books
```

## UI libraries

```bash
nx g lib ui \
--tags type:ui,scope:books \ --no-interactive
```
