<p align="center">
  <img src="src/assets/logo-comment.svg" width="200"/>
</p>

<h1 align="center"> tiptap-comment-extension </h1>

[Tiptap Extension](https://tiptap.dev/guide/custom-extensions) for having Google-Docs like pro-commenting in Tiptap.

A ⭐️ to the repo if you 👍 / ❤️  what I'm doing would be much appreciated.

> **Note**: This is __VUE 3 version__. [**REACT** peeps, here's your ride!](https://github.com/sereneinserenade/tiptap-comment-extension-react)

## Demo (truly detailed)

- You can try it out at https://sereneinserenade.github.io/tiptap-comment-extension/

https://user-images.githubusercontent.com/45892659/160260884-34b77b9f-3fb3-4ddf-af1d-066659b12774.mp4

## How to use

I wrote [a blog about](https://dev.to/sereneinserenade/how-i-implemented-google-docs-like-commenting-in-tiptap-k2k) how I implemented this.

TLDR; here's a short description. Copy the [comment.ts](src/components/extension/comment.ts) file in your extensions folder. You might have to change extension depending on whether you're using TypeScript or not. Enough of English, let's talk code.

I jest of course, I don't think you need documentation for this. Just take look at [Tiptap.vue](src/components/Tiptap.vue) for an example implementation and come up with an implementation of your own(or just copy paste pretending this is some solution you found on StackOverflow). If there's any question or issues, I'll be [at the Bar](https://github.com/sereneinserenade/tiptap-comment-extension/issues)(ref to [Burn Butcher Burn](https://www.youtube.com/watch?v=qSxBVHqA-RU) from "The Witcher - Season 2").

## Contributing

Show your ❤️ by ⭐️ing this repository. Your support means a lot.

Clone the repo, do something, make a PR(or not). You know what's the drill. Looking forward to your PRs, you amazing devs.

## Stargazers
[![Stargazers repo roster for @sereneinserenade/tiptap-comment-extension](https://reporoster.com/stars/dark/sereneinserenade/tiptap-comment-extension)](https://github.com/sereneinserenade/tiptap-comment-extension/stargazers)

<details>
  <summary>Stuff that nobody really cares about (cause mostly, they already know it) </summary>

# Vue 3 + Typescript + Vite

This template should help get you started developing with Vue 3 and Typescript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar)

## Type Support For `.vue` Imports in TS

Since TypeScript cannot handle type information for `.vue` imports, they are shimmed to be a generic Vue component type by default. In most cases this is fine if you don't really care about component prop types outside of templates. However, if you wish to get actual prop types in `.vue` imports (for example to get props validation when using manual `h(...)` calls), you can enable Volar's Take Over mode by following these steps:

1. Run `Extensions: Show Built-in Extensions` from VSCode's command palette, look for `TypeScript and JavaScript Language Features`, then right click and select `Disable (Workspace)`. By default, Take Over mode will enable itself if the default TypeScript extension is disabled.
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

You can learn more about Take Over mode [here](https://github.com/johnsoncodehk/volar/discussions/471).
</details>
