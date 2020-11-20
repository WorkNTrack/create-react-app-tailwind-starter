# create-react-app + tailwindcss(purge enabled for production)
##### This is a boilerplate containing CRA integrated with tailwindcss.

<img src="https://i.ibb.co/MhgzZfR/Screenshot-2020-11-20-at-6-06-31-PM.png" alt="screenshot"/>

### Usage

```bash
git clone git@github.com:WorkNTrack/create-react-app-tailwind-starter.git && create-react-app-tailwind-starter
yarn install

yarn start   # for running in dev mode
 or
yarn build   # for generating production build
```


#### DOC
- `index.css` is for importing tailwind directives.
- `custom.css` is used for custom styling. It can be any file provided we import it.

### Dev mode
Use `yarn start` for running the app in development mode. The `prestart` script generates the tailwind styles and dumps it into the output.css. This output file can be configured as separate files for both `development` & `production` and based on that the script can be changed to use the new file.

### Production build
Use `yarn build` for generating an optimized production build. The `prebuild` script generates the tailwind styles that are used in the codebase(using purgecss).


### Bugs & Contributions:
- Report bugs by creating issues with labels as `bug`.
- Any/Every contribution is welcomed.
