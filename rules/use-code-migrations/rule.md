---
type: rule
title: Do you know to use code migrations
uri: use-code-migrations
authors:
  - title: Bryden Oliver
    url: https://www.ssw.com.au/people/bryden-oliver
related: []
created: 2021-12-13T17:27:38.786Z
guid: 8284cedd-8eea-4e3b-b04b-451896a615c0
---
Do you still apply .sql scripts by hand? Do you sometimes run them in the wrong order? No longer, with EF code first migrations, all those manual tasks become a simple bundle that can be added to your release pipeline. 

Let's see how its done:
            
<!--endintro-->

Jason shows some stategies and work around to common problems when getting started with code migrations. Check out his video:

`youtube https://www.youtube.com/watch?v=vzXCyzH33b8
`
**Figure: You can also view Jasons blog: <https://jasontaylor.dev/ef-core-database-initialisation-strategies/>**

::: todo
TODO: Bryden
:::

::: bad
Bad example - Don't modify database directly
:::

::: good
Good example - modify entities and generate a migration 
:::