# Railroad
## An interactive autodeployer for your projects


### Goals:
- Make it as easy as possible for people to deploy their projects by providing a link to a GitHub repo
- Make it easy for users to provision new resources that their project might interact with (ex. a database)

### User Flow:
- User connects with their GitHub account through OAuth, granting access to view and clone their repositories
- User is brought to the main dashboard, where they can select to create new blocks
- User can select which architecture their project uses, what commands to build, and what commands to run
- For now, only Next.js frontend, Flask backend, and PostgreSQL databases will be supported as blocks

### Tech Stack
- Use React Flow Editor for the blocks
- Use a FastAPI backend server to deploy apps from
