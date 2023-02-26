# ReproNxAngularSsr

https://github.com/nrwl/nx/issues/15273

1. `npx create-nx-workspace --name repro-nx-angular-ssr --preset empty --skipGit --nxCloud false`
2. `cd repro-nx-angular-ssr`
3. `npm install @nrwl/angular`
4. `npx nx g @nrwl/angular:application test --routing --standalone --minimal --setParserOptionsProject --skipTests --strict --style css`

**This fails:**

`npx nx generate setup-ssr --project test --verbose`
