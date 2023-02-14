# ChatGPT Clone #
## Wrap all conversational AIs under one roof. ##
  This project was originally created as a Minimum Viable Product (or MVP) for the [@HackReactor](https://github.com/hackreactor/) Bootcamp. It was built with OpenAI response streaming and most of the UI completed in under 20 hours. If you're curious what it looked like 20 hours in, you can find the [original MVP project here](https://github.com/danny-avila/rpp2210-mvp). This was created without using any boilerplates or templates, including create-react-app and other toolchains. The purpose of the exercise was to learn setting up a full stack project from scratch. Please feel free to give feedback, suggestions, or fork the project for your own use.

## Summary ##
  Conversational/Utility AIs are the future and OpenAI revolutionized this movement with ChatGPT. While numerous methods exist to integrate conversational AIs, this app commemorates the original styling of ChatGPT, with the ability to integrate any current/future conversational AI models through user-provided APIs, while also having in mind improved client features, such as conversation search, and prompt templates. This project was also built with the anticipation of the official ChatGPT API from OpenAI, though it uses unofficial packages. Through this clone, you can avoid subscription-based models in favor of either free or pay-per-call APIs. I will most likely not deploy this app, as it's mainly a learning experience, but feel free to clone or fork to create your own custom wrapper.

<!-- ![hero](apps/www/public/og.jpg) -->

## Updates
<details open>
<summary><strong>2023-02-14</strong></summary>

Official ChatGPT use is no longer possible though I recently used it with waylaidwanderer's [reverse proxy method](https://github.com/waylaidwanderer/node-chatgpt-api/blob/main/README.md#using-a-reverse-proxy), and before that, through leaked models he also discovered.

Currently, this project is only functional with the `text-davinci-003` model.
</details>

## Roadmap

> **Warning**
>  This is a work in progress. I'm building this in public. You can follow the progress here or on my [Linkedin]().
> Here are my planned/recently finished features.

- [x] AI Model Selection
- [ ] Highlight.js for code blocks
- [ ] Prompt Templates
- [ ] Conversation/Prompt Search
- [ ] Bing AI integration (still on the waitlist myself)
- [ ] Config file for easy startup
- [ ] Semantic Search Option (requires more tokens)

### Features

- Response streaming identical to ChatGPT
- UI from original ChatGPT, including Dark mode
- AI model selection

### Technologies used

- Utilizes waylaidwanderer's [node-chatgpt-api package](https://github.com/waylaidwanderer/node-chatgpt-api) for current conversational AIs
- Response streaming identical to ChatGPT through server-sent events
- Use of Tailwind CSS (just like the official site) and [shadcn/ui](https://github.com/shadcn/ui) components
- Redux Toolkit, and React-Redux for state management
- Backend: Node.js, Express, MongoDB

## Use Cases ##

  ![use case example](./use_case.png "GPT is down! Plus is too expensive!")
  - ChatGPT is down ( and don't want to pay for ChatGPT Plus).
  - ChatGPT/Google Bard/Bing AI conversations are lost in space or
  cannot be searched past a certain timeframe.


## Solution ##
  Serves and searches all conversations reliably. All AI convos under one house.
  Pay per call and not per month (cents compared to dollars).

## How to Get Started ##
- Originally built with the [chatgpt-api](https://github.com/transitive-bullshit/chatgpt-api) package.

## How to Get Started ##
> **Warning**
>  Working on easy startup/config code. Still in development.

  <!-- ## License

Licensed under the [insert license here](). -->