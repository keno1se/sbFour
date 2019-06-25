# sbFour

Changes needed to do in harmonica-layout.component.ts  to make edge working rendering classlist, classname

       // const scaleSelection = event.target.innerText;  // innerText NOT working in edge
     const scaleSelection = event.target.textContent;  // this works in edge

