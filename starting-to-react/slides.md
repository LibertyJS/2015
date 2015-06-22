React.js

---

[![how React fits into the JS landscape. It only cares about user interaction and rendering.](http://f.cl.ly/items/0S0i0g0x1a3J2m1E0x47/embularactymerbone%20graph.png)](https://github.com/ryanflorence/jsconf2014/blob/master/slides.pdf)

---

# JSX

[See it live](http://output.jsbin.com/nuqebi/2)

---

# *Virtual DOM*

Lets you code like the 90s. Re-render everything all the time. 

---

![React builds a new Virtual DOM subtree, diffs it with the old one, computes a minimal set of DOM mutations and puts them in a queue, and batch executes all updates](https://draftin.com:443/images/29890?token=2dcUgXWBIrptX8P8B83vW6u3P9mgoNWAr95LwwnH-vjODmHROVcncm_iBUYxFNCkBz-Tr8A7S3OsBgsMzLIFOpc) 

---

![two sets of ul elements with three child li elements, representing the "before" and "after" states of a buddy list. The first li value changes from "Alice" to "Steve", and the third ones class changes from "web active" to "mobile idle"](https://draftin.com:443/images/29891?token=FRuw0e_D0gQYd65SiouaTnRVFsvmLlkIO5g39luUEK3L1mZqkxEn7XMTFPIkEBkvn0ijhivOzzyiumMIXPXF4BI) 

---

![javascript code that updates the minimum amount of content in the first and third nodes of the list](https://draftin.com:443/images/29892?token=pErTaC7jD0VQ7rWeHbIYM0MBX0FHdYxY3oGyCsVmDHlPbrTKbDPyEjFUUhaiaOES6RbYCMA5OdCCuBJEwCc6m8U) 

---

One-way data flow

---

[Flux](https://facebook.github.io/flux/)

---

### Try it out!

`npm install -g learnyoureact`