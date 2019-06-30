# sbFour

Render in any browser with this:
https://keno1se.github.io/sbFour/

But it'll not work in Edge, see below.

Changes needed to do in harmonica-layout.component.ts  to make edge working rendering classlist, classname

       // const scaleSelection = event.target.innerText;  // innerText NOT working in edge
     const scaleSelection = event.target.textContent;  // this works in edge

