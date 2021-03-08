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
<h3 style="color: #1b91ff">PostgreSQL</h3>
|||
<h3 style="color: #17ff2e">Node.js</h3>
|||
<h3 style="color: #268bd2">TypeScript</h3>
|||
<h3 style="color: deeppink">GraphQL</h3>
|||
<h3>Next.js</h3>
|||
<h3 style="color: #2a76dd">React</h3>

---

## TypeScript
|||
Od Microsoftu
|||
Striktně typovaný
|||
Úroveň kontroly typů je konfigurovatelná

---

## REST
|||
Způsob komunikace BE a FE
|||
Je definován tzv. endpointy
|||
Jeden endpoint je vlastně URL adresa
|||
Operace se rozlišují pomocí HTTP metod

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

<section>
  <pre>
    <code data-trim data-noescape class="graphql">
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
    </code>
</pre>
</section>
|||
Dostaneme z BE přesně to, o co si řekneme
