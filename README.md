#Jenny Example Project

- Install jenny-cli globally
    - `npm install -g jenny-cli`
- Clone repo
    - `git clone https://github.com/angry-yard/jenny-cli-example.git -n`
- Get NPM packages, included the templates to use
    - `npm install`
- You'll need a database to use along with SQL Server
    - Sorry, I can't help you out with that one
- Modify the `jenny.config.json` file so that the connection information points to your
database and the tables to include are correct
- Open a prompt in the root of the project and `jenny generate`
    - You should see the generated items in C:\Templates