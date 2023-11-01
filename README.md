## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Chapters

**1. Getting Started** - Create a new Next.js application using the dashboard starter example and explore the project

- About creating a project
- About the project structure
- About Typescript
- About running the development server

**2. CSS Styling** - Style your Next.js application wth Tailwind and CSS modules

- How to add a global CSS file to your application
- Two different ways of styling: Tailwind and CSS modules
- How to conditionally add class names with the clsx utility package

**3. Optimizing Fonts and Images** - Optimize fonts and images with the Next.js built-in components

- How to add custom fonts with next/font
- How to add images with next/image
- How fonts and images are optimized in Next.js

**4. Creating Layouts and Pages** - Create the dashboard routes and a shared layout that can be shared between multiple pages

- Create the /login and dashboard pages using file-system routing
- Understand the role of folders and files when creating new route segments
- Create a layout that can be shared between multiple dashboard pages
- Understand what colocation, partial rendering, and root layout are

**5. Navigating Between Pages** - Learn how to use Link component to navigate between pages

- How to use use the next/link component
- How to show an active link with the usePathname() hook
- How to client-side navigation works on Next.js

**6. Setting up your Database** - Setup your database for your application and seed it with initial data.

- Push your project to GitHub
- Set up a Vercel account and link your GitHub repo for instant previews and deployments
- Create and link your project to a Postgres database
- Seed the database with inicial data

**7. Fetching Data** - Learn about the different ways to fetch data in Next.js, and fetch data for your dashboard page using Server Components

- Learn about some approaches to fetching data: APIs, ORMs, SQL, etc
- How Server Components help us access our back-end resources more securely
- What network waterfalls are
- How to implement parallel data fetching using a JavaScript Pattern

**8. Static and Dynamic Rendering** - Understand how rendering works in Next.js, and make your dashboard app dynamic

- What Static Rendering is and how it can improve your application's performance
- What Dynamic Rendering is and when to use it
- Different approaches to make your dashboard dynamic
- The limitation of fetching data at request time

**9. Streaming** - Improve your application's loading experience with streaming and loading skeletons

- What streaming is and when you might use it
- How to implement streaming with loading.js and Suspense
- What loading skeletons are
- What route groups are, and when you might use them
- Qhere to place Suspense boundaries in your application

**10. Partial Prerendering (Optional)** - An early look into Partial Prerendering and how it works

- What Partial Prerendering is
- How Partial Prerendering works

**11. Adding Search and Pagination** - Add search and pagination to your dashboard application using Next.js APIs

- Learn how to use the Next.js APIs: searchParams, usePathname, and useRouter
- Implement search and pagination using URL search params

**12. Mutating Data** - Mutate data using React Server Actions, and revalidate the Next.js cache

- What React Server Actions are and how to use them to mutate data
- How to work with forms and Server Components
- Best practices for working with the native formData object, including type validation
- How to revalidate the client cache using the revalidatePath API
- How to create dynamic route segments with specific IDs
- How to use the React's useFormStatus hook for optimistic updates

**13. Handling Errors** - Handle errors gracefully with error.tsx and notFound

- How to use the special error.tsx file to catch errors in your route segments, and show a fallback UI to the user
- How to use the notFound function and not-found file to handle 404 errors (for resources that don’t exist)
