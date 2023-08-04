# ComposeDB Delegate Statement Starter

This is a slimmed-down simple starter showing how to edit and query a DAO delegate statement.

## Getting Started

1. Install your dependencies:

```bash
npm install
```
2. Generate an admin seed and enter it into admin_seed.txt

3. Generate an admin did and enter it into composedb.config.json in the admin-dids array

4. In your terminal, run the following to start your Postgres instance:

```bash
docker-compose up
```
5. Finally, run your application in a new terminal (first ensure you are running node v16 in your terminal):

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result and create a statement with a minimum statement length of 25 characters.

Open [http://localhost:3000/get](http://localhost:3000/get) to query based on DAO contract address

## Learn More

To learn more about Ceramic please visit the following links

- [Ceramic Documentation](https://developers.ceramic.network/learn/welcome/) - Learn more about the Ceramic Ecosystem.
- [ComposeDB](https://composedb.js.org/) - Details on how to use and develop with ComposeDB!

You can check out [Create Ceramic App repo](https://github.com/ceramicstudio/create-ceramic-app) and provide us with your feedback or contributions! 
