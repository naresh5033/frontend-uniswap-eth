This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## uniswap Dapp

This is uniswap clone dapp, where the user has to connect the wallet to access the dapp, once he logged in the user can ve option to swap the coins (in the Pool) for the test eth once he swapped the coins he ve an option to swap back to eth .\

contract Dex.sol is an ERC20 contract, Hardhat was used to deploy the contract in goerli Testnet.

For the frontend i used React, Tailwind for styling and Wagmi.

## Deployed contracts

CustomDex - 0xd2206731ca7Eaa4277Ac13f6ddCc67D2ffE63B34
Customtoken - 0x12Cad7A787de63439cc31E55D0cDf6262185Ee34

## Deployment

The Dapp is deployed in Heroku and the deployed Url is - https://uniswap-3-eth.herokuapp.com/

- the app was redeployed in the netlify and the [deployed url is](https://main--incandescent-sprite-07b6f1.netlify.app/)
