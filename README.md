# Typescript multi package starter
Starter for typescript monorepo.

## Get started
  - Clone repository:
    - with degit (clone without git history):
      ```
      npx degit https://github.com/binier/typescript-multi-package-starter.git YOURFOLDERNAME
      ```
    - with git:
      ```
      git clone https://github.com/binier/typescript-multi-package-starter.git YOURFOLDERNAME
      ```
  - Install dependecies:
    ```
    yarn install
    ```
  - Edit `name` and `respository.url` in **package.json**  to your package
    name and it's repository url.
  - Edit `compilerOptions.paths` key from `@typescript-multi-package-starter/*`
    to `@nameOfYourPackage/*`.

    Note: `nameOfYourPackage` should match `name` in **package.json**.

  ---

## Add package
  Add new package to monorepo using:
  ```
  yarn package:add foo
  ```
  Command creates new package under directory **packages/foo**
