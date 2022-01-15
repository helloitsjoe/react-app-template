# React App Template

A basic template for a React App, customized with a few tools and workflows I
use in most of my projects.

## Tools

- [`styled-components`](https://styled-components.com/)
- [`styled-system`](https://styled-system.com/)
- [Jest](https://jestjs.io)
- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
- [`eslint`](https://eslint.org/)

## Automated GitHub Pages Deploys

It also has a script that will set up CI pipelines to run tests and deploy to
GitHub pages. To do this:

1. Run `node scripts/setup-deploy.js`
2. Push your changes to the `main` branch
3. Enable GitHub Pages at
   `https://github.com/<your-username>/<your-repo>/settings/pages`, selecting
   the `gh-pages` branch under `Source`

Once the pipeline finishes (under the `Actions` tab), your app will be deployed!
Go to `<your-username>.github.io/<your-repo>` to see it live. Any commits pushed
to the `main` branch will trigger a new deploy.

In addition, whenever you push changes to a branch you can see the branch deploy
at `<your-username>.github.io/<your-repo>/branch-<your-branch>`. This allows you
to preview changes before deploying them to the main site.
