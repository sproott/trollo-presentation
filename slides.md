# Trollo

---

## Nápad
|||
## Trello
|||
Organizační nástroj pro týmy
|||
Zdarma
|||
Spousta integrací s jinými aplikacemi

---

## Technologie
|||
<img class="logo" src="assets/logos/postgresql.svg">
<h3 style="color: #336791">PostgreSQL</h3>
|||
<img class="logo" src="assets/logos/nodejs.svg">
<h3 style="color: #539E43">Node.js</h3>
|||
<img class="logo" src="assets/logos/typescript.svg">
<h3 style="color: #007ACC">TypeScript</h3>
|||
<img class="logo" src="assets/logos/graphql.svg">
<h3 style="color: #E535AB">GraphQL</h3>
|||
<img class="logo" src="assets/logos/nextjs.svg">
<h3 style="color: #000000">Next.js</h3>
|||
<img class="logo" src="assets/logos/react.svg">
<h3 style="color: #61DAFB">React</h3>

---

## TypeScript
|||
Od Microsoftu
|||
Striktně typovaný
|||
Úroveň kontroly typů je konfigurovatelná pomocí souboru tsconfig

---

## REST
|||
Způsob komunikace BE a FE
|||
Je definován tzv. endpointy
|||
Jeden endpoint je vlastně URL adresa
|||
Typy operací se rozlišují pomocí HTTP metod

---

## GraphQL
|||
Alternativa RESTu
|||
Vše je na jednom endpointu
|||
Queries
|||
Mutations
|||
Subscriptions

---

/board/:id
|||
Nevíme, co nám z BE přijde

---

<pre><code data-trim data-noescape class="graphql">
board(id: $boardId) {
  id
  name
  lists {
    id
    name
    index
    cards {
      id
      name
      description
    }
  }
}
</code></pre>
|||
Dostaneme z BE přesně to, o co si řekneme





---

### Tato prezentace byla napsána jazykem Markdown pomocí JS frameworku reveal.js
