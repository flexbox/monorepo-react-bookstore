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

```bash
nx g component GlobalStyles --project ui --export --tags type:ui,scope:books
nx g component Button --project ui --export --tags type:ui,scope:books
nx g component Header --project ui --export --tags type:ui,scope:books
nx g component Main --project ui --export --tags type:ui,scope:books
nx g component NavigationList --project ui --export --tags type:ui,scope:books
nx g component NavigationItem --project ui --export --tags type:ui,scope:books
```
