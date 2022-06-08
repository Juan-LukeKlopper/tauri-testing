# Tauri + SvelteKit + Typescript Template

## Prerequisites

Be sure you have installed all of the prerequisites for running a Tauri project. You can find them [here](https://tauri.studio/v1/guides/getting-started/prerequisites).

If you're using `npm` to run scripts, be sure to change the values of the `beforeBuildCommand` and `beforeDevCommand` fields in [`tauri.conf.json`](/src-tauri/tauri.conf.json) to `npm run build` and `npm run dev`, respectively.

## Developing

Once you've cloned the template and installed dependencies with `yarn` or `npm install`, start a development server:

```bash
yarn tauri dev

# or with npm
npm run tauri dev
```

## Building

To create a production version of your app:

```bash
yarn tauri build

# or with npm
npm run tauri build
```
