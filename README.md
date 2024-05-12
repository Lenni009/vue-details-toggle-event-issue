# vue-details-toggle-event-issue

Minimal repro for an issue in vue-tsc

## Reproduction

Run these commands:

```sh
npm install
```

```sh
npm run build
```

The build throws an error that the toggle event cannot have a function assigned to it.

Works on 1.x versions:

1. Go to `package.json`
2. Change `vue-tsc` to `1.8.0`

Run `npm i` and `npm run build` again -> no error, build succeeds.

## Expected Behaviour

`toggle` is a standard event that is fired on the `details` element, and therefore we should also be able to attach an event handler to it
