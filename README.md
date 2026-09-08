Hi, I'm Michael, a full-stack software engineer based in Richmond, Virginia. I work primarily across .NET and the modern web, but I'm much more interested in solving problems than being defined by a particular stack. I enjoy moving between languages, ecosystems, and paradigms, absorbing the best ideas from each along the way.

I'm also an active member of Richmond's software community. I co-organized and presented at Richmond JavaScript Conference 2025 and regularly attend and speak at local meetups. I've given talks on topics including .NET for JavaScript Developers, Astro, RedwoodJS, Tauri, Playwright, test isolation, and learning in public.

Pinned below are a few projects that show off the breadth of what I like to build.

### 🃏 `every-deck-of-cards`

A fun technological challenge: **how do you virtualize and browse a list containing 80 unvigintillion elements?**

The site maps arbitrary-precision integers to unique permutations of a 52-card deck and back again. Since rendering performance is the entire game, the frontend uses Solid, virtualization, and a Web Worker to keep the heavy math off the main thread while maintaining a smooth, effectively infinite scrolling experience.

Try it at [everydeckof.cards](https://everydeckof.cards).

### 🎨 `RazorScopedStyleElements`

A good example of one of my favorite kinds of engineering: **finding a great idea in one ecosystem and bringing it to another.**

`RazorScopedStyleElements` brings component-scoped `<style>` elements—familiar from frameworks like Astro, Svelte, and Vue—to .NET's Blazor. It's distributed as a NuGet package and transforms components at build time, doing just enough work to hand the result off to the .NET SDK's existing MSBuild scoped-CSS pipeline rather than reinventing it.

[View RazorScopedStyleElements on NuGet.org](https://www.nuget.org/packages/RazorScopedStyleElements).

### 🤖 `AgentPlayground`

My agentic digital garden: part playground, part useful personal software, and an excuse to keep experimenting with what modern AI systems can actually do.

It started as a chat interface and has grown to include file uploads, speaker-aware voice transcription, web search, semantic-search RAG, real-time and scheduled tasks, push notifications through a mobile companion app, and role-based access control around tool execution.

Underneath, it's a distributed .NET application composed of three services on a private network, with asynchronous messaging, relational data, and vector search consolidated into PostgreSQL with automated backups.

No public deployment for this one—unless you ask really nicely. 😉

### 🔔 `bzzr`

A simple idea: **a free, frictionless buzzer system for Jeopardy-style games.**

`bzzr` supports real-time rooms of up to 60 players and is built with React, RedwoodSDK, Tailwind CSS, and Storybook. It's deployed on Cloudflare, with Durable Objects coordinating real-time multiplayer state.

Buzz in at [bzzr.app](https://bzzr.app).
