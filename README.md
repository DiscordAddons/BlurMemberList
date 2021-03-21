# Blur Member List
Blurs the member list and unblurs on hover.
```css
.members-1998pB, .members-1998pB>div {
   filter: blur(4px);
}
.members-1998pB, .members-1998pB>div:hover {
   filter: blur(0);
   transition: filter .25s ease-out;
}
```
