# Exercise 2 - Relative paths

```
.
└── Home/
    ├── home.html
    ├── help.html
    ├── music/
    │   └── songs.html
    └── movies/
        ├── cinema.html
        └── action_movies/
            └── action.html

```

| Source page | Destination page | Hyperlink                                       |
| ----------- | ---------------- | ----------------------------------------------- |
| action.html | cinema.html      | `<a href="../cinema.html">`                     |
| home.html   | songs.html       | `<a href="./music/songs.html">`                 |
| help.html   | action.html      | `<a href="./movies/action_movies/action.html">` |
| cinema.html | help.html        | `<a href="./action_movies/action.html">`        |
| action.html | home.html        | `<a href="../../home.html">`                    |
| cinema.html | action.html      | `<a href="./actions_movies/action.html">`       |
| songs.html  | action.html      | `<a href="./movies/action_movies/action.html">` |
| action.html | songs.html       | `<a href="../../music/songs.html">`             |
