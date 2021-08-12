# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
v-model - binds it to the state on that page.  v-bind or : binds a prop variable to a child of the parent component.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Less bandwith is being used when it calls to the server because the whole page doesn't have to reload again. Keeps the whole page organized into its components instead of many different pages.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
When something is onMounted, it runs as soon as the page is loaded.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
vmodel is two-way dating binding - says connect this input field with this element in the state
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
To handle events on the DOM - for example a click event
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if, v-else, v-show
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
Is is essentailly saying, count the keys, and for every key in the object, give me what I am asking for.  It can also stand-in as an alternative to id, if you are iterating over an array and the objects do not have ids.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
Don't quite understand it as we only saw it once in a fireside, but slot is a div you use in the html where you can put a modal that needs to be different looking for each instance of it.
```