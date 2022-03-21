# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
Double Curly brackets or the v-bind directive are both ways to bind data
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Traditional web servers will draw and load new pages, whereas SPA will just rewrite the current page to decrease load times, and lower server cache
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
onMounted essentially just means: "On page load, do this thing"
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
v-model works perfectly to data bind on form elements
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
The v-on can be used to listen to the DOM and run some amount of javascript when it is triggured
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
Many Vue Directives (v-if, v-show, etc) are perfect to use for this, combined with computed attributes and onMounted, and the like
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The :key essentially gives a hint to the DOM to help compare old and new lists
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
The slot is basically a placeholder in elements drawn on html. They basically allow you to pass properties from child components into the parent
```