<h1 style="font-family: Pacifico; color: #1890FF;">Trollo</h1>

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
<img class="logo" src="assets/logos/typescript.svg">
<h3 style="color: #007ACC">TypeScript</h3>
|||
<img class="logo" src="assets/logos/nodejs.svg">
<h3 style="color: #539E43">Node.js</h3>
|||
<img class="logo" src="assets/logos/react.svg">
<h3 style="color: #61DAFB">React</h3>
|||
<img class="logo" src="assets/logos/nextjs.svg">
<h3 style="color: #000000">Next.js</h3>
|||
<img class="logo" src="assets/logos/graphql.svg">
<h3 style="color: #E535AB">GraphQL</h3>
|||
<img class="logo" src="assets/logos/apollo.svg">
<h3 style="color: #000000">Apollo</h3>
|||
<img class="logo" src="assets/logos/postgresql.svg">
<h3 style="color: #336791">PostgreSQL</h3>

---

<img class="logo" src="assets/logos/typescript.svg">
<h2 style="color: #007ACC">TypeScript</h3>
|||
<img src="assets/logos/microsoft.svg" width="250px;">
|||
Striktně typovaný
|||
Úroveň kontroly typů je konfigurovatelná pomocí souboru tsconfig

---

<img class="logo" src="assets/logos/react.svg">
<h2 style="color: #61DAFB">React</h3>
|||
JSX
|||
Komponenty
|||
<pre><code data-trim>
const Logo = () => <h1>Trollo</h1>
</code></pre>
|||
Props
|||
<pre><code data-trim data-line-numbers="1|3"><script type="text/template">
const Logo = ({text}: {text: string}) => <h1>{text}</h1>

<Logo text="Trollo" />
</script></code></pre>

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

### Prezentace:
- Markdown
- reveal.js

---

<h2 style="font-family: Pacifico; color: #1890FF;">Děkuji za pozornost</h2>
