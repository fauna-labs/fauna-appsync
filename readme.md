# AppSync + Fauna Integration GraphQL merge

This solution uses the following tech stack

- AppSync
- AWS Amplify CLI (10.x)
- FaunaDB

You can interact with FaunaDB via GraphQL API, REST or Drivers (JS, Java, Go, Python etc). This solution uses the GraphQL api to integrate Fauna with Amplify. 

## Setting up Fauna

- Create a new DB
- Upload the GraphQL schema (`fauna-schema.graphql` in the code)

## Setting up AppSync with Amplify

- Make sure you have AWS Amplify CLI installed.
- Clone the code and run `amplify configure` to setup you project.
- Make sure you have all the custom VTL resolvers in `amplify/backend/api/appsyncgateway/resolvers` directory.
- Run `amplify push` to create a new stack.