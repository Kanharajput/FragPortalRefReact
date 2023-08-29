## Check the commits   
This project is all to learn about fragments so all code here is not for fragments.
It is an project code on which we are making changes and learning fragments.
<strong>Go with commits<strong>

### Why we need fragments
- So in react js components we are bounded to return single element from the and wrap all content inside it.
    Solution : Fragments -> fragments let us wrap all the html which we want to render inside one element and that element
        is fragment.
        ```j
        <>
            <h1>Kanha</h1>
            <h1>Tomar</h1>
        </>
        ```
        OR
        ```
        <React.Fragment>
            <h1>Kanha</h1>
            <h1>Tomar</h1>
        </React.Fragment>

        ```

### Portals     
- Portals let us opt a location in html structure where we can put our component.
- index.js putting App component at block which having id = root
- But to create a portal we have to use react dom library and create our component as portal via statement 
    ```{ReactDOM.createPortal(<Alert title={props.title}> , document.getElementbyId('alert-root'))}```
- Also create a block with id alert-root in index.html file.
- Basically we are selecting a block and putting what we want.