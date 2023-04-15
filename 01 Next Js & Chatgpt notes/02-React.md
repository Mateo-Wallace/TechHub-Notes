## What is react

Changes from reloading entire page to specifically the component

In order for react to load it has to load the server, the js, react, and then load the page

## What is next.js

Dynamic Routing - routing built into next js

Route pre fetching - allows user to load pages before clicking a link

### Rendering

All the pages turn into html and css at the end of the day. 

They are using rust instead of babel webpack which is 70 times faster.
And we still write REACT code!

React is client side rendering

Next.js is pre rendered. 
There are 2 techniques to accomplish this
- Static-side generation = ssg
- server side rendering = ssr

#### Server side rendering

- Cons
    - Cannot deploy to a static cdn
    - make api call on every page
- Pros
    - Always rendered
    - not good for large applications
