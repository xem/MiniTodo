MiniTodo
===

Standalone TODO app in 155 chars of vanilla JS

```
<script>document.write(`<input id=i><a${o=" onclick="}'u.${H="innerHTML"}+="<li${o}${H}=${H}.strike()>"+i.value'>+<a${o}u.${H}="">X</a><ol id=u>`)</script>
```

Made during this contest: https://twitter.com/dumindaxsb/status/1340539549890404354

- Click + to add an item
- Click x to clear all items
- Click an item to mark it as done

Demo: https://xem.github.io/MiniTodo

<hr>

125b standalone HTML/JS version (same thing but without the "JS only" rule):

```
<input id=i><a onclick='u[H="innerHTML"]+="<li onclick=this[H]=this[H].strike()>"+i.value'>+<a onclick=u[H]="">X</a><ol id=u>
```