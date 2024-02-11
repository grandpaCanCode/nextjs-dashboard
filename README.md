![image](https://github.com/stringsArraysObjects/nextjs-dashboard/assets/128002915/5376f185-e90a-4405-b9b2-b88513776228)
You've done a few things to optimize data fetching in your application, you've:
Fetched data on the server with React Server Components. This allows you to keep expensive data fetches and logic on the server, reduces the client-side JavaScript bundle, and prevents your database secrets from being exposed to the client.
Used SQL to only fetch the data you needed, reducing the amount of data transferred for each request and the amount of JavaScript needed to transform the data in-memory.
Implemented Streaming to prevent slow data requests from blocking your whole page, and to allow the user to start interacting with the UI without waiting for everything to load.