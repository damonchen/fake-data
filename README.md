# [FakeDataHelper](https://fake-data-help.vercel.app/)

This project generates fake data for you using AI.

[![](./public/screenshot3.png)](https://fake-data-help.vercel.app/)

## Support

`JSON`

PR welcome

## How it works

Inspired by [EmailHelper](https://github.com/shengxinjing/email-helper) and [Reorx](https://twitter.com/novoreorx/status/1624080178539548673)

Powerd by [OpenAI](https://openai.com/), [Next.js](https://nextjs.org/), [Vercel](https://vercel.com/) and [Tailwind CSS](https://tailwindcss.com/).

This project uses the [OpenAI GPT-3 API](https://openai.com/api/) (specifically, text-davinci-003) and [Vercel Edge functions](https://vercel.com/features/edge-functions) with streaming. It constructs a prompt based on the form and user input, sends it to the GPT-3 API via a Vercel Edge function, then streams the response back to the application.

Video and blog post coming soon on how to build apps with OpenAI and Vercel Edge functions!

## Running Locally

After cloning the repo, go to [OpenAI](https://beta.openai.com/account/api-keys) to make an account and put your API key in a file called `.env`.

Then, run the application in the command line and it will be available at `http://localhost:3000`.

```bash
npm run dev
```

## One-Click Deploy

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=vercel-examples):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Nutlope/twitterbio&env=OPENAI_API_KEY&project-name=twitter-bio-generator&repo-name=twitterbio)

<!-- https://www.seotraininglondon.org/gpt3-business-email-generator/ -->
