# Starter - A NextJs starter workspace for the enterprise

✨ **This workspace has been generated by [Nx, a Smart, fast and extensible build system.](https://nx.dev)** ✨

## Getting Started

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/drkstr101/prism-next)

### Start the app

To start the development server run `yarn nx serve home`. Open your browser and navigate to <http://localhost:4200/>.

### Generate code

If you happen to use Nx plugins, you can leverage code generators that might come with it.

Run `yarn nx list` to get a list of available plugins and whether they have generators. Then run `yarn nx list <plugin-name>` to see what generators are available.

Learn more about [Nx generators on the docs](https://nx.dev/plugin-features/use-code-generators).

### Running tasks

To execute tasks with Nx use the following syntax:

```shell
yarn nx <target> <project> <...options>
```

You can also run multiple targets:

```shell
yarn nx run-many -t <target1> <target2>
```

..or add `-p` to filter specific projects

```shell
yarn nx run-many -t <target1> <target2> -p <proj1> <proj2>
```

Targets can be defined in the `package.json` or `projects.json`. Learn more [in the docs](https://nx.dev/core-features/run-tasks).

### Want better Editor Integration?

Have a look at the [Nx Console extensions](https://nx.dev/nx-console). It provides autocomplete support, a UI for exploring and running tasks & generators, and more! Available for VSCode, IntelliJ and comes with a LSP for Vim users.

### Ready to deploy?

Just run `yarn build` to build the application. The build artifacts will be stored in the `dist/` directory, ready to be deployed.

### Set up CI

Nx comes with local caching already built-in (check your `nx.json`). On CI you might want to go a step further.

- [Set up remote caching](https://nx.dev/core-features/share-your-cache)
- [Set up task distribution across multiple machines](https://nx.dev/core-features/distribute-task-execution)
- [Learn more how to setup CI](https://nx.dev/recipes/ci)
