# First Look at React 19

- <https://www.youtube.com/watch?v=EPaLg4U_K1o>

* React Compiler
  - React 19 will include a compiler much like Svelte. This will not only make React faster, but will automate certain tedious tasks and amek less work for the developer.
  - A lot of the features we will cover are a direect result of the compiler.
* Automatic Memoization
  - Memoization is the process of optimizing components to prevent unnecessary re-renders.
  - Traditionally, we used hooks like useMmeo and useCallback to do this. These hooks will now be a thing of the past.
* use() Hook
  - The use hook lets you read and asynchronously load a resource such as a promise or a context. It can also be used in loops and conditionals unlike other hooks.
  - It can be used to fetch data in some cases replacing useEffect.
  - use(context) will replace the useContext hook.
* use client and use server directives
  - React now has built in support for these directives.
  - Components can be rendered on the server, which makes for better SEO, faster page load times and easy data fetching.
* Actions
  - Support for <form action={formAction}>
  - Actions can now be used for both client and server components.
  - New hooks for form handling such asn useFormStatus() and useFormState().
* useOptimistic() Hook
  - Apply temporary updates to the UI while waiting for things like the server to respond.
  - This makes for a faster and more responsive experience.
* Document Metadata
  - Built in support for metadata like title, description and keywords.
  - You can place the tags anywhere within your component JSX and it will work for both client and server components.
* Other Changes
  - ref passed as a regular prop (No more forwardRef)
  - Web Components
  - No more React.lazy
  - Asset loading
  - <Context.Provider> replaced with <Context>
