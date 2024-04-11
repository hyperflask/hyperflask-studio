# Hyperflask Studio

**⚠️ This is a future project which has not been started yet.**

A web administration console to help you build and manage [Hyperflask](https://github.com/hyperflask/hyperflask) projects.

Goals:

 - Usable from development to production
 - Fully integrated development experience (editor for your app)
 - Act as CMS
 - Checklists to help you keep track of what needs to be done to launch
 - AI/LLM integration to help you develop / create content
 - Analytics for your running app
 - Minimal maintenance and ease of deployment
 - Limit reliance on third party services

Expected features:

 - Manage collections and database (CMS)
 - Page editor using [monaco](https://github.com/microsoft/monaco-editor) (going as far as using something like [grapesjs](https://grapesjs.com/) ?)
 - Components library to download from (using third party source)
 - AI based component creator (generate code)
 - Assets/media management with integrated AI based image generator (eg. for logos)
 - Configuration editor (similar to vscode preference editor ?)
 - Editable "launch" checklist with todos for tech stuff but also SEO and marketing
 - Integrated documentation
 - Error reporting (very simple system compared to something like sentry but avoid third party service)
 - Analytics dashboard (web stats and performance)

Tech notes:

 - Itself an Hyperflask app
 - Using sqlite
 - Use duckdb for product analytics ?
 - Launch checklist saved as TODO.md file in project root to be able to edit it via code editor also
 - Read web analytics from nginx
 - Possibility to disable the app & config editor in production