Please fill in this template.

- [X] Make your PR against the `master` branch.
- [X] Use a meaningful title for the pull request. Include the name of the package modified.
- [X] Test the change in your own code. (Compile and run.)
- [X] Follow the advice from the [readme](https://github.com/DefinitelyTyped/DefinitelyTyped#make-a-pull-request).
- [X] Avoid [common mistakes](https://github.com/DefinitelyTyped/DefinitelyTyped#common-mistakes).
- [ ] Run `tsc` without errors.
- [ ] Run `npm run lint package-name` if a `tslint.json` is present.

Select one of these and delete the others:

If adding a new definition:
- [X] The package does not provide its own types, and you can not add them.
- [X] If this is for an NPM package, match the name. If not, do not conflict with the name of an NPM package.
- [X] Create it with `npm run new-package package-name`, not by basing it on an existing project.
- [X] `tslint.json` should be present, and `tsconfig.json` should have `noImplicitAny`, `noImplicitThis`, and `strictNullChecks` set to `true`.
