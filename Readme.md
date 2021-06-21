1. Next is React Frontend development web framework created by Vercel that enables functionality such as server-side rendering and static-site generation

2. What is Server Side Rendering
Unlike a traditional React app where the entire application is loaded and rendered on the client, Next.js allows the first page load to be rendered by the server, which is great for SEO and performance

3. Other Benefits
    a. Easy Page routing
    b. API Routes
    c. Out of the Box TypeScript & Sass
    d. Static Site generation (next export)
    e. Easy deployment

4. Sequence:
    i) Command for new project: npx create-next-app next-crash-course --use-npm
    ii) Command to run the project: npm run dev

    Directory Structure:
        i) public: anything you put in here, will reflect in the browser.
        For example https://localhost:3000/favicon.ico
        ii) styles: Contains Moduler style sheets
        iii) pages: 
            a. index.js is the HomePage
            b. files in this directory needs no navigation, they directly show up on the web-browser 
            c. _app.js wraps all of page Components
    
