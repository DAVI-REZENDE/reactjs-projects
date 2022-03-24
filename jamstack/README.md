# Blog (JAMStack)

This is a JAMStack project that uses Next.js and GraphQL to consume the GraphCMS API, styled by the tailwind library. GraphQL queries were generated automatically by lib codegen

<p align="center">
  <img alt="Preview" src="../previews/blog-jamstack.png" />
</p>

Get Started: 

First you must create an account on GraphCMS and create the project from the ready-made template called blog, go to `settings>API Access`, and copy the 'Content API' and replace it in the code: `lid>urql.ts`

```bash
yarn install
yarn start
# or
npm install
npm start
```