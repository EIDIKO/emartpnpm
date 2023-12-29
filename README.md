# Nx Workspace: emartpnpm

This repository contains an Nx workspace named "emartnx" with Node.js projects.


## STEP-1: Install Nx with pnpm

```bash
npm install -g pnpm

pnpx create-nx-workspace OR

pnpm create-nx-workspace

```

## STEP-2: Install Dependencies

```bash
cd emartpnpm


pnpm install

```


## STEP-3: Run Nx Commands with pnpm

You can now use pnpm to run Nx commands. For example, to generate a new Node.js application:

```bash

pnpx nx generate @nrwl/node:application first


pnpx nx test first


```


## STEP-4.1: Update Nx Version with pnpm

```bash

pnpm add -D @nrwl/cli@latest


```


## STEP-5: Skipping Tests in adding new project

The command you provided:

```bash

"npx nx generate @nrwl/node:application emartnx-one --project=emartnx"

```

is used to generate a new Node.js application named "emartnx-one" within the Nx workspace named "emartnx."

The two folders you mentioned, "emartnx-one" and "emartnx-one-e2e," are typical when generating a new application using Nx. The additional "e2e" folder is for end-to-end (e2e) testing, which is a common practice in software development to ensure that different parts of an application work together correctly.

If you want to skip the generation of e2e tests when generating a new application, you can use the --skipTests option:

```bash

"npx nx generate @nrwl/node:application emartnx-one --project=emartnx --skipTests"

```

This will generate only the main application without the corresponding end-to-end tests. Adjust the command according to your preferences and project requirements.




## STEP-5: git init

## STEP-6: git add .


## STEP-7: git commit -m "Initial commit"


## STEP-8: git remote add origin <repository-url>


## STEP-9: git push -u origin master



## STEP-10: npx nx test emartnx-first

```bash

npx nx test emartnx-first

```





