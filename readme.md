# Bootstrap for an Elm-style functional frontend in JS

This is a simple bootstrap for starting frontend projects faster. The architecture follows Elm-style functional frontend ideas with Messages, Models, Updates, Views and Commands (for side-effects).

---

### How to use this project?

1. Fork or clone this repo
2. [Install `parcel`][parcel] (recommended. You can also use other bundlers but `parcel` is good for this project)
3. Start cranking code.

---

### To run locally during development:

```
project> parcel index.html
```

(You should see an "Okay" on `localhost:1234` or wherever parcel serves)

---

### To build (for deploy)

```
project> parcel build index.html
```

---

### Things it comes packaged with:

- All necessary files required to start the project (Msgs, Updates, Commands, Views)
- [Tailwindcss][tailwindcss] for styling. The project uses SASS.
- `hyperscript-helpers` for writing Elm-style functional HTML tags.

---

### Resources:

- [Elm Architecture][elm-guide]
- [FP for Beginners with JS][fp-course]

[parcel]: https://parceljs.org
[elm-guide]: https://guide.elm-lang.org/architecture/
[fp-course]: https://www.udemy.com/course/functional-programming-for-beginners-with-javascript
[tailwindcss]: https://tailwindcss.com/
