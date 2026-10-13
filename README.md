# GPT-3 landing page exercise

This is a GPT-3 landing page exercise. It is practice for laying out a React page, not a product that was shipped.

## What is on the page

The app is a single page. These sections render from top to bottom:

- **Navbar.** Logo, links for Home, What is GPT3?, Open AI, Case Studies, and Library, plus Sign in and Sign up. A smaller viewport collapses those links into a menu.
- **Header.** Headline “Let’s Build Something amazing with GPT-3 OpenAI”, a short paragraph, an email field with a Get Started button, a line that 1,600 people requested access, and an illustration.
- **Brand.** A row of logos: Google, Slack, Atlassian, Dropbox, and Shopify.
- **What is GPT-3.** A short explanation, the heading “The possibilities are beyond your imagination”, and three items: Chatbots, Knowledgebase, and Education.
- **Features.** The heading “The Future is Now and You Just Need to Realize It. Step into Future Today. & Make it Happen.”, a prompt to request early access, and four feature blurbs.
- **Possibility.** An image beside copy that says the possibilities are beyond your imagination, with early-access lines above and below the paragraph.
- **Call to action.** “Register Today & start exploring the endless possibilities.” and a Get Started button.
- **Blog.** Heading “A lot is happening, We are blogging about it.” and five article cards, each dated Sep 26, 2021, with the text “GPT-3 and Open AI is the future. Let us exlore how it is?”
- **Footer.** A heading asking if you want to step into the future before others, a Request Early Access button, columns for Links, Company, and Get in touch, and a copyright line.

## Run it

```bash
git clone https://github.com/LifeAyush/gpt3-landing.git
cd gpt3-landing
npm install
```

Scripts from `package.json`:

- `npm start` runs `react-scripts start` and serves the page locally.
- `npm run build` runs `react-scripts build` and writes a production build.
- `npm test` runs `react-scripts test`.
