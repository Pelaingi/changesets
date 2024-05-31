<p alother recommend integrating it with how your CI works.

To check that PRs contain a changeset, we recommend using [the changeset bot](https://github.com/apps/changeset-bot), or if you want to fail builds on a changesets failure, run `yarn changeset status` in CI.

To make releasing easier, you can use [this changesets github action](https://github.com/changesets/action) to automate creating versioning pull requests, and optionally publishing packages.

## Documentation

- [Intro to using changesets](./docs/intro-to-using-changesets.md)
- [Detailed explanation](./docs/detailed-explanation.md)
- [Common questions](./docs/common-questions.md)
- [Adding a changeset](./docs/adding-a-changeset.md)
- [Automating changesets](./docs/automating-changesets.md)
- [Checking for changesets](./docs/checking-for-changesets.md)
- [Command line options](./docs/command-line-options.md)
- [Config file options](./docs/config-file-options.md)
- [Decisions](./docs/decisions.md)
- [Dictionary](./docs/dictionary.md)
- [Fixed packages](./docs/fixed-packages.md)
- [Linked packages](./docs/linked-packages.md)
- [Modifying changelog format](./docs/modifying-changelog-format.md)
- [Prereleases](./docs/prereleases.md)
- [Problems publishing in monorepos](./docs/problems-publishing-in-monorepos.md)
- [Snapshot releases](./docs/snapshot-releases.md)
- [Versioning applications and other non-npm packages](./docs/versioning-apps.md)
- [Experimental Options](./docs/experimental-options.md)

## Cool Projects already using Changesets for versioning and changelogs

- [atlaskit](https://atlaskit.atlassian.com/)
- [emotion](https://emotion.sh/docs/introduction)
- [keystone](https://v5.keystonejs.com/)
- [react-select](https://react-select.com/home)
- [XState](https://xstate.js.org/)
- [pnpm](https://pnpm.js.org/)
- [filbert-js](https://github.com/kuldeepkeshwar/filbert-js)
- [tinyhttp](https://github.com/talentlessguy/tinyhttp)
- [Firebase Javascript SDK](https://github.com/firebase/firebase-js-sdk)
- [Formik](https://github.com/formium/formik)
- [MobX](https://github.com/mobxjs/mobx)
- [Nhost](https://github.com/nhost/nhost)
- [verdaccio](https://verdaccio.org/)
- [Chakra UI](https://chakra-ui.com/)
- [Astro](https://astro.build)
- [SvelteKit](https://kit.svelte.dev/)
- [Hydrogen](https://hydrogen.shopify.dev)
- [react-pdf](https://github.com/diegomura/react-pdf)
- [GraphQL Code Generator](https://github.com/dotansimha/graphql-code-generator)
- [GraphQL Yoga](https://github.com/dotansimha/graphql-yoga)
- [GraphQL-Mesh](https://github.com/Urigo/graphql-mesh)
- [GraphiQL](https://github.com/graphql/graphiql)
- [wagmi](https://github.com/wagmi-dev/wagmi)
- [refine](https://github.com/pankod/refine)

# Thanks/Inspiration

- [bolt](https://github.com/boltpkg/bolt) - Brought us a strong concept of how packages in a mono-repo should be able to interconnect, and provided the initial infrastructure to get inter-package information.
- [Atlassian](https://www.atlassian.com/) - The original idea/sponsor of the changesets code, and where many of the ideas and processes were fermented. It was originally implemented by the team behind [atlaskit](https://atlaskit.atlassian.com).
- [lerna-semantic-release](https://github.com/atlassian/lerna-semantic-release) - put down many of the initial patterns around updating packages within a multi-package-repository, and started us thinking about how to manage dependent packages.
- [Thinkmill](https://www.thinkmill.com.au) - For sponsoring the focused open sourcing of this project, and the version two rearchitecture.
