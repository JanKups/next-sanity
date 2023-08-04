<!-- markdownlint-disable --><!-- textlint-disable -->

# 📓 Changelog

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [5.1.4](https://github.com/sanity-io/next-sanity/compare/v5.1.3...v5.1.4) (2023-08-04)

### Bug Fixes

- **deps:** Update dependency @sanity/preview-kit to v2.4.2 ([#500](https://github.com/sanity-io/next-sanity/issues/500)) ([fb5e538](https://github.com/sanity-io/next-sanity/commit/fb5e5383ee3262564c63bb0603b7ff6959a124d9))

## [5.1.3](https://github.com/sanity-io/next-sanity/compare/v5.1.2...v5.1.3) (2023-08-02)

### Bug Fixes

- **deps:** update non-major ([#491](https://github.com/sanity-io/next-sanity/issues/491)) ([dd0293c](https://github.com/sanity-io/next-sanity/commit/dd0293c8485e2d5f253fc36b027c8ef17791fd07))

## [5.1.2](https://github.com/sanity-io/next-sanity/compare/v5.1.1...v5.1.2) (2023-07-13)

### Bug Fixes

- **deps:** update dependency @sanity/preview-kit to v2.3.3 ([#489](https://github.com/sanity-io/next-sanity/issues/489)) ([d2336c8](https://github.com/sanity-io/next-sanity/commit/d2336c87437fdf4316ff1deefcfcc54efc179fb2))
- **deps:** update non-major ([#485](https://github.com/sanity-io/next-sanity/issues/485)) ([3c35fe3](https://github.com/sanity-io/next-sanity/commit/3c35fe3726f6487fea58ef6924fc9b8d3a2eb0b0))

## [5.1.1](https://github.com/sanity-io/next-sanity/compare/v5.1.0...v5.1.1) (2023-07-07)

### Bug Fixes

- **deps:** update non-major ([#479](https://github.com/sanity-io/next-sanity/issues/479)) ([3a575fd](https://github.com/sanity-io/next-sanity/commit/3a575fd41dffa23c796e32db887b3a86d5e018aa))

## [5.1.0](https://github.com/sanity-io/next-sanity/compare/v5.0.2...v5.1.0) (2023-06-29)

### Features

- use perspective features ([#465](https://github.com/sanity-io/next-sanity/issues/465)) ([76db810](https://github.com/sanity-io/next-sanity/commit/76db810105376386086d47df6c97dbb987270ff8))

### Bug Fixes

- **deps:** update non-major ([#473](https://github.com/sanity-io/next-sanity/issues/473)) ([a9eb461](https://github.com/sanity-io/next-sanity/commit/a9eb461ae7a30cb07d1213700fe3c37bcd9766e9))
- **webhook:** revert `app-router` support from ([#460](https://github.com/sanity-io/next-sanity/issues/460)) ([2a5bfbb](https://github.com/sanity-io/next-sanity/commit/2a5bfbb88f97bc6a27c396c83586381a709fea2f))

## [5.0.2](https://github.com/sanity-io/next-sanity/compare/v5.0.1...v5.0.2) (2023-06-21)

### Bug Fixes

- **deps:** update dependency @sanity/preview-kit to v2.2.2 ([#464](https://github.com/sanity-io/next-sanity/issues/464)) ([288f543](https://github.com/sanity-io/next-sanity/commit/288f543cb7eb8b623641589b2c09e53e840510a0))

## [5.0.1](https://github.com/sanity-io/next-sanity/compare/v5.0.0...v5.0.1) (2023-06-21)

### Bug Fixes

- **webhook:** add `app-router` support ([#460](https://github.com/sanity-io/next-sanity/issues/460)) ([c2f6155](https://github.com/sanity-io/next-sanity/commit/c2f6155bdfc26feace614fd7b1cb1887c84d14c5))

## [5.0.0](https://github.com/sanity-io/next-sanity/compare/v4.3.3...v5.0.0) (2023-06-21)

### ⚠ BREAKING CHANGES

- `definePreview` and `<PreviewSuspense>` are replaced by `<LiveQueryProvider>`.
- `usePreview` is replaced by `useLiveQuery`.
- `@sanity/client` is now a peer dependency.

[The migration guide outlines every breaking change and how to migrate your code](https://github.com/sanity-io/next-sanity/#migration-guides)

### Bug Fixes

- Preview hooks no longer perform queries while the initial dataset export is streaming, as this could lead to incomplete query results and unexpected cases of `null`.

## [4.3.3](https://github.com/sanity-io/next-sanity/compare/v4.3.2...v4.3.3) (2023-05-24)

### Bug Fixes

- **deps:** upgrade `@sanity/preview-kit` to v1.5.4 ([7c7ec79](https://github.com/sanity-io/next-sanity/commit/7c7ec79e4aff6937ee4581bc7381e9457fc1b005))

## [4.3.2](https://github.com/sanity-io/next-sanity/compare/v4.3.1...v4.3.2) (2023-05-03)

### Bug Fixes

- add back `SanityClient` export ([86ee531](https://github.com/sanity-io/next-sanity/commit/86ee531bb894a41a7e6db0d02651d3b73af03cac))

## [4.3.1](https://github.com/sanity-io/next-sanity/compare/v4.3.0...v4.3.1) (2023-05-03)

### Bug Fixes

- add release notes ([9e9d4e0](https://github.com/sanity-io/next-sanity/commit/9e9d4e081c161db84a5e1d59890f05508be1b504))

## [4.3.0](https://github.com/sanity-io/next-sanity/compare/v4.2.1...v4.3.0) (2023-05-03)

### Introducing Visual Editing

> **Note**
>
> Visual Editing is available for select [Sanity enterprise customers](https://www.sanity.io/enterprise?utm_source=github.com&utm_medium=referral&utm_campaign=may-vercel-launch). If you would like to use Visual Editing with Vercel, you will also need to contact Vercel to enable this feature for your Vercel team. [You may contact our sales team for more information.](https://www.sanity.io/contact/sales?utm_source=github.com&utm_medium=referral&utm_campaign=may-vercel-launch)

![](https://i.imgur.com/wt95U5Q.jpg)

This release includes support for Visual Editing and Content Source Maps. This feature enables you to make deep edit links from components in a front end that takes you to respective fields in the Studio. This enables a new workflow that substantially reduces the time it takes to make changes by bringing you directly to the relevant field where you can make edits reliably in its appropriate context. For more information on Visual Editing, [check out the documentation here](https://www.sanity.io/docs/vercel-visual-editing?utm_source=github.com&utm_medium=referral&utm_campaign=may-vercel-launch).

Existing Sanity enterprise customers can contact their dedicated customer success manager to enable this feature. [Customers interested in upgrading to an enterprise plan can contact our sales team for more information](https://www.sanity.io/contact/sales?utm_source=github.com&utm_medium=referral&utm_campaign=may-vercel-launch). You will also need to [contact Vercel sales](https://vercel.com/contact/sales) to enable this feature for your Vercel team.

Sanity enterprise customers can also use the Content Source Maps with GROQ to build custom Visual Editing capabilities. For more information, [check out the Content Source Maps documentation here](https://www.sanity.io/docs/content-source-maps?utm_source=github.com&utm_medium=referral&utm_campaign=may-vercel-launch).

---

This release is also available on:

- [npm package (@latest dist-tag)](https://www.npmjs.com/package/next-sanity/v/4.3.0)

## [4.2.1](https://github.com/sanity-io/next-sanity/compare/v4.2.0...v4.2.1) (2023-05-03)

### Bug Fixes

- **docs:** update the `pages` metadata example ([7b30ea7](https://github.com/sanity-io/next-sanity/commit/7b30ea7fe638f10c049667f47ca7a4fbf6375f7e))

## [4.2.0](https://github.com/sanity-io/next-sanity/compare/v4.1.8...v4.2.0) (2023-04-28)

### Features

- add `unstable__fastRender` experiment ([60ef49e](https://github.com/sanity-io/next-sanity/commit/60ef49e0f0f48461a3bc481bc6c4389aaf717380))
- add support for metadata API ([#405](https://github.com/sanity-io/next-sanity/issues/405)) ([5ed8609](https://github.com/sanity-io/next-sanity/commit/5ed8609fd83835d18a1b32e3f56a5838c6901e94))

### Bug Fixes

- deprecate `next-sanity/studio/loading` ([8e1c1bb](https://github.com/sanity-io/next-sanity/commit/8e1c1bb0c48f78a7c13de39eed449c4b4873dd4d))
- **metadata:** use `next-sanity/studio/metadata` entrypoint ([8da05a1](https://github.com/sanity-io/next-sanity/commit/8da05a1cfb26b92631b721661e3903e78421e283))
- support the `scheme="system"` studio prop ([17ab29c](https://github.com/sanity-io/next-sanity/commit/17ab29c1e4109b6797fe932618fb5c3140d8feff))

## [4.1.8](https://github.com/sanity-io/next-sanity/compare/v4.1.7...v4.1.8) (2023-04-27)

### Bug Fixes

- **deps:** add `@types/styled-components` to peers ([3634dac](https://github.com/sanity-io/next-sanity/commit/3634dac6ae43b2f619d47bdfa1fa72124e55be82))

## [4.1.7](https://github.com/sanity-io/next-sanity/compare/v4.1.6...v4.1.7) (2023-04-12)

### Bug Fixes

- **deps:** update dependency @sanity/preview-kit to v1.4.0 ([#391](https://github.com/sanity-io/next-sanity/issues/391)) ([ad92dd1](https://github.com/sanity-io/next-sanity/commit/ad92dd12a8da984938f3b70f7311794e771e0c4d))

## [4.1.6](https://github.com/sanity-io/next-sanity/compare/v4.1.5...v4.1.6) (2023-03-27)

### Bug Fixes

- **deps:** update dependency @sanity/preview-kit to v1.3.7 ([#367](https://github.com/sanity-io/next-sanity/issues/367)) ([8a63231](https://github.com/sanity-io/next-sanity/commit/8a6323134b7e66b581ddf28b8eb1a9f9da11ec5e))
- **deps:** update dependency @sanity/preview-kit to v1.3.8 ([#384](https://github.com/sanity-io/next-sanity/issues/384)) ([75ca575](https://github.com/sanity-io/next-sanity/commit/75ca57599147321f963053c2758f492c4059d4aa))

## [4.1.5](https://github.com/sanity-io/next-sanity/compare/v4.1.4...v4.1.5) (2023-02-15)

### Bug Fixes

- **client:** use named `createClient` export ([5c5f1a3](https://github.com/sanity-io/next-sanity/commit/5c5f1a37f8a101fff7403828514b213dcb7b0519))

## [4.1.4](https://github.com/sanity-io/next-sanity/compare/v4.1.3...v4.1.4) (2023-02-15)

### Bug Fixes

- **deps:** update dependency @sanity/client to v5 ([#340](https://github.com/sanity-io/next-sanity/issues/340)) ([8b5af88](https://github.com/sanity-io/next-sanity/commit/8b5af88c62a412633896fd84b2ec0adffc2a2f63))

## [4.1.3](https://github.com/sanity-io/next-sanity/compare/v4.1.2...v4.1.3) (2023-02-14)

### Bug Fixes

- bumping `@sanity/preview-kit` to `1.3.4` ([f8621be](https://github.com/sanity-io/next-sanity/commit/f8621befb2832816f52586b03c46184a46b0e995))

## [4.1.2](https://github.com/sanity-io/next-sanity/compare/v4.1.1...v4.1.2) (2023-01-26)

### Bug Fixes

- **deps:** update devdependencies (non-major) ([#316](https://github.com/sanity-io/next-sanity/issues/316)) ([e5c17f6](https://github.com/sanity-io/next-sanity/commit/e5c17f67a3f8866eab6dada23dbf956b150d7327))

## [4.1.1](https://github.com/sanity-io/next-sanity/compare/v4.1.0...v4.1.1) (2023-01-19)

### Bug Fixes

- **deps:** update dependency @sanity/preview-kit to ^1.3 ([#301](https://github.com/sanity-io/next-sanity/issues/301)) ([f8cd8d2](https://github.com/sanity-io/next-sanity/commit/f8cd8d2f574c0f244cf0b9e37802f98c24fef506))

## [4.1.0](https://github.com/sanity-io/next-sanity/compare/v4.0.6...v4.1.0) (2023-01-17)

### Features

- support modern npm peer deps ([b06546a](https://github.com/sanity-io/next-sanity/commit/b06546a84d0a505f3ed8522735f682d6ce529360))

### Bug Fixes

- improve npm deduping of shared deps ([5fb74ef](https://github.com/sanity-io/next-sanity/commit/5fb74ef08886f45b00eb83b03901d7c9db7562a3))

## [4.0.6](https://github.com/sanity-io/next-sanity/compare/v4.0.5...v4.0.6) (2023-01-14)

### Bug Fixes

- **deps:** update dependency @sanity/preview-kit to ^1.2.23 ([#297](https://github.com/sanity-io/next-sanity/issues/297)) ([7a3242e](https://github.com/sanity-io/next-sanity/commit/7a3242e773d93ab68a0fe7d3e98d463bc3572a50))

## [4.0.5](https://github.com/sanity-io/next-sanity/compare/v4.0.4...v4.0.5) (2023-01-14)

### Bug Fixes

- **deps:** update dependency groq to ^3.2.3 ([#291](https://github.com/sanity-io/next-sanity/issues/291)) ([d551334](https://github.com/sanity-io/next-sanity/commit/d551334986f4cd6e28a024c71aeed073d1aab89f))

## [4.0.4](https://github.com/sanity-io/next-sanity/compare/v4.0.3...v4.0.4) (2023-01-12)

### Bug Fixes

- **deps:** update dependency @sanity/preview-kit to ^1.2.22 ([#289](https://github.com/sanity-io/next-sanity/issues/289)) ([fee62dc](https://github.com/sanity-io/next-sanity/commit/fee62dc949d411343228fd79658dac272c712748))

## [4.0.3](https://github.com/sanity-io/next-sanity/compare/v4.0.2...v4.0.3) (2023-01-12)

### Bug Fixes

- **deps:** update dependency @sanity/preview-kit to ^1.2.21 ([#286](https://github.com/sanity-io/next-sanity/issues/286)) ([09013a8](https://github.com/sanity-io/next-sanity/commit/09013a8601c696ee76d3d2cef3575e553f2ecd58))

## [4.0.2](https://github.com/sanity-io/next-sanity/compare/v4.0.1...v4.0.2) (2023-01-12)

### Bug Fixes

- **deps:** update dependency @sanity/preview-kit to ^1.2.20 ([#283](https://github.com/sanity-io/next-sanity/issues/283)) ([6a6dbe6](https://github.com/sanity-io/next-sanity/commit/6a6dbe60e97da95db719ba2647a6b6e0d67aca69))

## [4.0.1](https://github.com/sanity-io/next-sanity/compare/v4.0.0...v4.0.1) (2023-01-12)

### Bug Fixes

- **deps:** update dependency groq to v3 ([#280](https://github.com/sanity-io/next-sanity/issues/280)) ([a67ea30](https://github.com/sanity-io/next-sanity/commit/a67ea301b9f6cf9c3b92effa9a141fef4deb7274))

## [4.0.0](https://github.com/sanity-io/next-sanity/compare/v3.1.9...v4.0.0) (2023-01-08)

### ⚠ BREAKING CHANGES

- change `import NextStudioLoading from 'next-sanity/studio/loading'` to `import {NextStudioLoading} from 'next-sanity/studio/loading'`

### Bug Fixes

- add full Node.js ESM runtime support ([ad3ceb7](https://github.com/sanity-io/next-sanity/commit/ad3ceb7262765a89e4138ec61f5ed49fbf7fd7e2))
- **deps:** update dependency @sanity/client to ^4.0.1 ([#267](https://github.com/sanity-io/next-sanity/issues/267)) ([b489987](https://github.com/sanity-io/next-sanity/commit/b48998735045b1723b2da7b0297870d9bf3457f3))
- **deps:** update dependency @sanity/client to v4 ([#262](https://github.com/sanity-io/next-sanity/issues/262)) ([a6ea4f3](https://github.com/sanity-io/next-sanity/commit/a6ea4f3ce35c28796f3ba3ec34dd549ac84220cd))
- **deps:** update dependency @sanity/preview-kit to ^1.2.17 ([#264](https://github.com/sanity-io/next-sanity/issues/264)) ([006fac3](https://github.com/sanity-io/next-sanity/commit/006fac349b4bd7a7d3b725927bc7cb364c4f00ee))
- **deps:** update dependency @sanity/preview-kit to ^1.2.18 ([#270](https://github.com/sanity-io/next-sanity/issues/270)) ([3d15213](https://github.com/sanity-io/next-sanity/commit/3d152138013da5553295b36c71670e4eb0b4bd3e))
- **deps:** update dependency @sanity/preview-kit to ^1.2.19 ([#274](https://github.com/sanity-io/next-sanity/issues/274)) ([ca28e5b](https://github.com/sanity-io/next-sanity/commit/ca28e5b47ae6ca1987516c5814fc03a721c698c5))

### Code Refactoring

- make `NextStudioLoading` a named export ([086de6f](https://github.com/sanity-io/next-sanity/commit/086de6f44b8b5db15fe0470267a2f90ff4c62770))

## [3.1.9](https://github.com/sanity-io/next-sanity/compare/v3.1.8...v3.1.9) (2022-12-30)

### Bug Fixes

- **deps:** update dependency @sanity/preview-kit to ^1.2.14 ([#250](https://github.com/sanity-io/next-sanity/issues/250)) ([a02246c](https://github.com/sanity-io/next-sanity/commit/a02246c8d8bf93ee0c9635d6b4de0201bc30ae92))
- **deps:** update dependency @sanity/preview-kit to ^1.2.15 ([#259](https://github.com/sanity-io/next-sanity/issues/259)) ([79e375f](https://github.com/sanity-io/next-sanity/commit/79e375f860ff7bdb3b69facd14c267b11881226d))

## [3.1.8](https://github.com/sanity-io/next-sanity/compare/v3.1.7...v3.1.8) (2022-12-23)

### Bug Fixes

- **deps:** update dependency @sanity/preview-kit to ^1.2.13 ([#247](https://github.com/sanity-io/next-sanity/issues/247)) ([ebdc514](https://github.com/sanity-io/next-sanity/commit/ebdc514e2d2565ed2cfda4f1f76ff9bbb6b1fec6))

## [3.1.7](https://github.com/sanity-io/next-sanity/compare/v3.1.6...v3.1.7) (2022-12-23)

### Bug Fixes

- **deps:** update dependency @sanity/pkg-utils to ^2.0.1 ([#246](https://github.com/sanity-io/next-sanity/issues/246)) ([14b5635](https://github.com/sanity-io/next-sanity/commit/14b563565ec9eacd87663af347078ea6d923f2a3))

## [3.1.6](https://github.com/sanity-io/next-sanity/compare/v3.1.5...v3.1.6) (2022-12-23)

### Bug Fixes

- **deps:** correct peer dependency versions ([#236](https://github.com/sanity-io/next-sanity/issues/236)) ([b24d18c](https://github.com/sanity-io/next-sanity/commit/b24d18cd277019a0cfeb6c90705032137cdec24d))
- **deps:** update dependency @sanity/preview-kit to ^1.2.12 ([#245](https://github.com/sanity-io/next-sanity/issues/245)) ([4482c18](https://github.com/sanity-io/next-sanity/commit/4482c181b913ccbb9f855a93cce66c2b5410c7f0))

## [3.1.5](https://github.com/sanity-io/next-sanity/compare/v3.1.4...v3.1.5) (2022-12-20)

### Bug Fixes

- remove tailwind SVG workaround ([#232](https://github.com/sanity-io/next-sanity/issues/232)) ([b8a2210](https://github.com/sanity-io/next-sanity/commit/b8a2210c7ec8fe46acf96c5025a91897d7654a57))

## [3.1.4](https://github.com/sanity-io/next-sanity/compare/v3.1.3...v3.1.4) (2022-12-18)

### Bug Fixes

- **deps:** update dependency @sanity/preview-kit to ^1.2.11 ([#228](https://github.com/sanity-io/next-sanity/issues/228)) ([50dd890](https://github.com/sanity-io/next-sanity/commit/50dd8908bebb4bd5c244dbc9875c6f0103651896))

## [3.1.3](https://github.com/sanity-io/next-sanity/compare/v3.1.2...v3.1.3) (2022-12-06)

### Bug Fixes

- **deps:** update dependency @sanity/pkg-utils to ^1.20.1 ([#202](https://github.com/sanity-io/next-sanity/issues/202)) ([532ffd7](https://github.com/sanity-io/next-sanity/commit/532ffd72c7ee32a5f5db767fc6f445c451dcbc19))
- **deps:** update dependency @sanity/preview-kit to ^1.2.10 ([#210](https://github.com/sanity-io/next-sanity/issues/210)) ([18b6093](https://github.com/sanity-io/next-sanity/commit/18b6093ff76f202131d7ae13e25f9617cccd0234))

## [3.1.2](https://github.com/sanity-io/next-sanity/compare/v3.1.1...v3.1.2) (2022-11-26)

### Bug Fixes

- make `config` optional in `NextStudioLoading` ([0af6f6c](https://github.com/sanity-io/next-sanity/commit/0af6f6c9be6fdf5094de49a78c66344ad255e3a9))
- make `config` optional in `useTheme` ([6e35ebc](https://github.com/sanity-io/next-sanity/commit/6e35ebcee0659d0dc45e05db945119ed0232ba01))

## [3.1.1](https://github.com/sanity-io/next-sanity/compare/v3.1.0...v3.1.1) (2022-11-25)

### Bug Fixes

- show "Loading..." text over spinner ([6082652](https://github.com/sanity-io/next-sanity/commit/60826520db924046b4889f1df69f02a3a921cf02))

## [3.1.0](https://github.com/sanity-io/next-sanity/compare/v3.0.5...v3.1.0) (2022-11-25)

### Features

- add `next-sanity/studio/loading` ([#196](https://github.com/sanity-io/next-sanity/issues/196)) ([575964d](https://github.com/sanity-io/next-sanity/commit/575964df5e5e1c6247ee06bc6d0cf271e4bc64a5))

## [3.0.5](https://github.com/sanity-io/next-sanity/compare/v3.0.4...v3.0.5) (2022-11-25)

### Bug Fixes

- add temp workaround for RSC compat ([1166b61](https://github.com/sanity-io/next-sanity/commit/1166b61331b96bb5470351f9f8c55d649b94d500))
- call `store.close` on `beforeunload` ([#195](https://github.com/sanity-io/next-sanity/issues/195)) ([e7b9bf6](https://github.com/sanity-io/next-sanity/commit/e7b9bf60f9751abbe05c6cd86d4d33cb3147e219))
- **docs:** Next 13 RSC auto code split client components ([80c2918](https://github.com/sanity-io/next-sanity/commit/80c29182fb3e723261cdcf929b44206661d85444))

## [3.0.4](https://github.com/sanity-io/next-sanity/compare/v3.0.3...v3.0.4) (2022-11-24)

### Bug Fixes

- set the webhooks runtime to `nodejs` by default ([1cf0a72](https://github.com/sanity-io/next-sanity/commit/1cf0a7295c5e5b4526d0e010936069e9787bca63))

## [3.0.3](https://github.com/sanity-io/next-sanity/compare/v3.0.2...v3.0.3) (2022-11-24)

### Bug Fixes

- set `key` prop on favicon links ([edde50a](https://github.com/sanity-io/next-sanity/commit/edde50a28ec57f6463d67d028922dbd8dca56953))

## [3.0.2](https://github.com/sanity-io/next-sanity/compare/v3.0.1...v3.0.2) (2022-11-22)

### Bug Fixes

- wait for eventual consistency by default ([d76f111](https://github.com/sanity-io/next-sanity/commit/d76f111b4dc11a2337dd177f206641ffb4add7cd))

## [3.0.1](https://github.com/sanity-io/next-sanity/compare/v3.0.0...v3.0.1) (2022-11-22)

### Bug Fixes

- add `<meta charset="utf-8">` in Next 13 ([a4e9e1a](https://github.com/sanity-io/next-sanity/commit/a4e9e1aa3e8fcb9495767f7360cea612f0cc6b68))
- don't negate `unstable__tailwindSvgFix` ([c6c540b](https://github.com/sanity-io/next-sanity/commit/c6c540bd51d88a72afc1d69e071a848d8498118e))

## [3.0.0](https://github.com/sanity-io/next-sanity/compare/v2.1.0...v3.0.0) (2022-11-22)

### ⚠ BREAKING CHANGES

- See the [Migration section in the README](https://github.com/sanity-io/next-sanity/tree/main#from-v2) for details.

### Features

- add support for Next 13 `appDir` ([#184](https://github.com/sanity-io/next-sanity/issues/184)) ([0c80876](https://github.com/sanity-io/next-sanity/commit/0c80876ae1496cfb7f8cc6e27ef3537a82fcea15)), closes [/github.com/sanity-io/next-sanity/tree/main#from-v2](https://github.com/sanity-io//github.com/sanity-io/next-sanity/tree/main/issues/from-v2)

## [2.1.0](https://github.com/sanity-io/next-sanity/compare/v2.0.2...v2.1.0) (2022-11-21)

### Features

- add `next-sanity/webhook` ([#180](https://github.com/sanity-io/next-sanity/issues/180)) ([5a94a9f](https://github.com/sanity-io/next-sanity/commit/5a94a9f47a5dd98d435bf6ee7b718b627c0b7ffa))

## [2.0.2](https://github.com/sanity-io/next-sanity/compare/v2.0.1...v2.0.2) (2022-11-18)

### Bug Fixes

- support `swcMinify` in NextJS 13 ([8e4ad34](https://github.com/sanity-io/next-sanity/commit/8e4ad34aef0defca0e36179d6d29ee46febd9083))

## [2.0.1](https://github.com/sanity-io/next-sanity/compare/v2.0.0...v2.0.1) (2022-11-16)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to ^1.1.3 ([#172](https://github.com/sanity-io/next-sanity/issues/172)) ([77d4a98](https://github.com/sanity-io/next-sanity/commit/77d4a98b413737ffc0d20cf2064999a42891291a))
- **deps:** update dependency @sanity/preview-kit to ^1.2.7 ([#173](https://github.com/sanity-io/next-sanity/issues/173)) ([7d580d7](https://github.com/sanity-io/next-sanity/commit/7d580d7567819a0dc519aa1249c41a94aa123627))

## [2.0.0](https://github.com/sanity-io/next-sanity/compare/v1.1.0...v2.0.0) (2022-11-16)

### ⚠ BREAKING CHANGES

[Check the full migration guide for details.](https://github.com/sanity-io/next-sanity#from-v1)

- Requires Node `v16`, like `Next 13`.
- `createPreviewSubscriptionHook` is replaced with `definePreview`.
- `createCurrentUserHook` is removed

### Features

- add new preview mode for Next 13 ([#152](https://github.com/sanity-io/next-sanity/issues/152)) ([9eae92a](https://github.com/sanity-io/next-sanity/commit/9eae92a5c7f080e5c34c04f555135623be182a0a)), closes [#next-12](https://github.com/sanity-io/next-sanity/issues/next-12) [#65](https://github.com/sanity-io/next-sanity/issues/65) [#4](https://github.com/sanity-io/next-sanity/issues/4) [#8](https://github.com/sanity-io/next-sanity/issues/8) [#16](https://github.com/sanity-io/next-sanity/issues/16) [#53](https://github.com/sanity-io/next-sanity/issues/53) [#46](https://github.com/sanity-io/next-sanity/issues/46) [#35](https://github.com/sanity-io/next-sanity/issues/35) [#22](https://github.com/sanity-io/next-sanity/issues/22) [#154](https://github.com/sanity-io/next-sanity/issues/154)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to ^1.1.1 (main) ([#159](https://github.com/sanity-io/next-sanity/issues/159)) ([13c6d93](https://github.com/sanity-io/next-sanity/commit/13c6d9385eb8b443be6a7ca71cbe20f636627e50))
- **deps:** update dependency @sanity/groq-store to ^1.1.2 (main) ([#165](https://github.com/sanity-io/next-sanity/issues/165)) ([4305d75](https://github.com/sanity-io/next-sanity/commit/4305d75a990f291442b74f79ce5686acf1d0cd09))
- support TS `v4.9.x` ([#162](https://github.com/sanity-io/next-sanity/issues/162)) ([0afc823](https://github.com/sanity-io/next-sanity/commit/0afc823dd93023199356195d8aca182e91a93a5f))

## [1.1.0](https://github.com/sanity-io/next-sanity/compare/v1.0.9...v1.1.0) (2022-11-15)

### Features

- add support for fetching subset of dataset by type ([#157](https://github.com/sanity-io/next-sanity/issues/157)) ([33b42d2](https://github.com/sanity-io/next-sanity/commit/33b42d2e63dd8ddc274c508ebedb927bdb8ecaef))

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to ^1.0.4 (main) ([#146](https://github.com/sanity-io/next-sanity/issues/146)) ([5043b01](https://github.com/sanity-io/next-sanity/commit/5043b011b0e0b290f01f763842b5ffae725271ce))

## [1.1.0-add-type-allowlist.1](https://github.com/sanity-io/next-sanity/compare/v1.0.9...v1.1.0-add-type-allowlist.1) (2022-11-14)

### Features

- add support for fetching subset of dataset by type ([8416e74](https://github.com/sanity-io/next-sanity/commit/8416e74a47bc4cd9a0ef8420228941a178c198ea))

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to ^1.0.4 (main) ([#146](https://github.com/sanity-io/next-sanity/issues/146)) ([5043b01](https://github.com/sanity-io/next-sanity/commit/5043b011b0e0b290f01f763842b5ffae725271ce))

## [1.0.9](https://github.com/sanity-io/next-sanity/compare/v1.0.8...v1.0.9) (2022-11-07)

### Bug Fixes

- add `package.json` to exports ([6abbcb1](https://github.com/sanity-io/next-sanity/commit/6abbcb13d9250d41c7e2302b77f071a1270a4c25))

## [1.0.8](https://github.com/sanity-io/next-sanity/compare/v1.0.7...v1.0.8) (2022-11-04)

### Bug Fixes

- mark internals ([5b714a9](https://github.com/sanity-io/next-sanity/commit/5b714a9a21ee3f7274ab683380e9430fb3148f27))

## [1.0.7](https://github.com/sanity-io/next-sanity/compare/v1.0.6...v1.0.7) (2022-11-04)

### Bug Fixes

- ESM + CJS interop bugs with `next-sanity/studio` ([b272225](https://github.com/sanity-io/next-sanity/commit/b27222538b435cbad00daf3600b28cede85472f6))

## [1.0.6](https://github.com/sanity-io/next-sanity/compare/v1.0.5...v1.0.6) (2022-11-03)

### Bug Fixes

- ESM bug in `next` + `studio v3` ([935be44](https://github.com/sanity-io/next-sanity/commit/935be44f00c0e2a262120758066a3a4996607ccf))

## [1.0.5](https://github.com/sanity-io/next-sanity/compare/v1.0.4...v1.0.5) (2022-11-03)

### Bug Fixes

- enable node native ESM ([#133](https://github.com/sanity-io/next-sanity/issues/133)) ([a47c3a1](https://github.com/sanity-io/next-sanity/commit/a47c3a1a8e73da7671db20444e35b249832a3bc1))

## [1.0.4](https://github.com/sanity-io/next-sanity/compare/v1.0.3...v1.0.4) (2022-11-03)

### Bug Fixes

- add TS release tags ([15d8c06](https://github.com/sanity-io/next-sanity/commit/15d8c0614722a070cf7734b4a2a5acef6a7ffa01))

## [1.0.3](https://github.com/sanity-io/next-sanity/compare/v1.0.2...v1.0.3) (2022-10-28)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to ^1.0.3 ([afd27f5](https://github.com/sanity-io/next-sanity/commit/afd27f5d84f1439212f585345f2ef43e3b946507))

## [1.0.2](https://github.com/sanity-io/next-sanity/compare/v1.0.1...v1.0.2) (2022-10-27)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to v1 ([22f7b5a](https://github.com/sanity-io/next-sanity/commit/22f7b5a07ce38cb1df6efd1fd797e114543d979b))
- export the subscription options to avoid ts errors ([#104](https://github.com/sanity-io/next-sanity/issues/104)) ([2fca80f](https://github.com/sanity-io/next-sanity/commit/2fca80fee7cb47bde119f6c9acf4fb57fcafc2d2))

## [1.0.1](https://github.com/sanity-io/next-sanity/compare/v1.0.0...v1.0.1) (2022-10-25)

### Bug Fixes

- expand supported next version range to allow v13 ([5573e6d](https://github.com/sanity-io/next-sanity/commit/5573e6d23361f0b0b7370003aec6346cb9168d35))

## [1.0.0](https://github.com/sanity-io/next-sanity/compare/v0.8.5...v1.0.0) (2022-10-13)

### ⚠ BREAKING CHANGES

- upgrade to node v14 or later.

### Bug Fixes

- drop support for node v12 ([b831ef4](https://github.com/sanity-io/next-sanity/commit/b831ef4040687fe6f96323fa8ef141a0ce603343))
- use `@sanity/pkg-utils` for bundling ([6929f98](https://github.com/sanity-io/next-sanity/commit/6929f984891866e272f9bd344950661bb895c15d))

## [0.8.5](https://github.com/sanity-io/next-sanity/compare/v0.8.4...v0.8.5) (2022-10-10)

### Bug Fixes

- **deps:** update dependencies (non-major) ([#76](https://github.com/sanity-io/next-sanity/issues/76)) ([34b357c](https://github.com/sanity-io/next-sanity/commit/34b357c20c7db026374708cf2f2d4fe6e6cb83c2))
- set dev-preview peer dep to tag ([b06996e](https://github.com/sanity-io/next-sanity/commit/b06996edc5aa66b7cff19d9e1f1bf7ede604bfc9))
- **studio:** set default font-family ([706c17f](https://github.com/sanity-io/next-sanity/commit/706c17fbcb46eac563f21c5cbb125c78d0c1f3a3))

## [0.8.4](https://github.com/sanity-io/next-sanity/compare/v0.8.3...v0.8.4) (2022-08-28)

### Bug Fixes

- support `sanity@dev-preview.15` ([98d50e2](https://github.com/sanity-io/next-sanity/commit/98d50e2c9f372bf7381725760f34a85dbcfbd183))

## [0.8.3](https://github.com/sanity-io/next-sanity/compare/v0.8.2...v0.8.3) (2022-08-28)

### Bug Fixes

- **deps:** update dependency @sanity/client to ^3.3.5 ([#73](https://github.com/sanity-io/next-sanity/issues/73)) ([a52ea74](https://github.com/sanity-io/next-sanity/commit/a52ea74b752e94986995e54e810db2bcc7b1a5e8))

## [0.8.2](https://github.com/sanity-io/next-sanity/compare/v0.8.1...v0.8.2) (2022-08-20)

### Bug Fixes

- **deps:** update dependency @sanity/groq-store to ^0.4.1 ([#71](https://github.com/sanity-io/next-sanity/issues/71)) ([467e110](https://github.com/sanity-io/next-sanity/commit/467e1103c4a3fe87124db6af50f1ad0cf6e8f068))

## [0.8.1](https://github.com/sanity-io/next-sanity/compare/v0.8.0...v0.8.1) (2022-08-17)

### Bug Fixes

- use `@sanity/semantic-release-preset` ([8dec077](https://github.com/sanity-io/next-sanity/commit/8dec077247d2d037f04e5e0fedbdd30c13e96f30))

## 0.5.2 - 2022-04-05

### Fixes

- Exports the `Aborter` interface used in `AbortController` to support stricter TypeScript setups.
- Allows stricter TypeScript setups by re-exporting `SanityClient` and `ClientConfig` from `@sanity/client`
- Bumps `@sanity/client` to `v3.3.0`, `@sanity/groq-store` to `v0.3.1` and `groq` to `v2.29.3`
- Typo in readme (#44)

## 0.5.1 - 2022-03-04

### Fixes

- Export the `SubscriptionOptions` interface in `useSubscription`

## 0.5.0 - 2022-02-16

### Features

- Upgraded `@sanity/groq-store` to `v0.3.0` which includes a new beta of `groq-js` that improves performance, especially when using projections.

### BREAKING

- Upgraded `@sanity/client` to `v3`, see its [CHANGELOG](https://github.com/sanity-io/client/blob/main/CHANGELOG.md#300) for details.
- `createPortableTextComponent` is removed.
- `createImageUrlBuilder` is removed.

See the [README](https://github.com/sanity-io/next-sanity#from-v04) for migration instructions.

## 0.4.0 - 2021-08-11

### BREAKING

- **Portable Text:** When encountering unknown block types, the serializer will no longer throw by default - instead if will render a hidden `div` with a message noting that a serializer is missing. A message will also be logged to the console. To use the old behavior of throwing on unknown types, pass `ignoreUnknownTypes: false` as a property to the `createPortableTextComponent()` function.
- **Portable Text:** The `markFallback` serializer has been renamed to `unknownMark` to align with the new `unknownType` serializer for blocks.
