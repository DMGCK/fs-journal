# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
The app.js is the entry point to the application, shows all the components/routers.
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
A vue component is a piece of HTML with javascript functionality baked into it, able to taken and used in many different places.

```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for acts like a For In loop, for each thing x in Things, make a component or element.
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
HTML, Script, and Style. 
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
L represents design by contract, or the idea that any client who is acting on a server will meet the prerequisites to actually complete that action.
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
RouterView! I don't recommend deleting routerview if you don't know why it's there! 
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
The AppState is a global state, where information that needs to be passed to each component across pages can live. Local data can be massaged or displayed from individual components, and only those components need to see that.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
Services in our Vue projects tend to only handle the AppState and API calls, with no visual effect from the user's end.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
App.vue is the lowest level file.
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
Style tags - alter the styling of the entire project, the scoped attribute makes it so the styling will not collide with the rest of the vue project.
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
WatchEffect(), reactive, or computed create watchable objects, where reactive is the one able to watch the deepest change in objects.

```