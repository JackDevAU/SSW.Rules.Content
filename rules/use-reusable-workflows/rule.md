---
type: rule
title: Do you use reusable workflows?
uri: use-reusable-workflows
authors:
  - title: Jack Pettit
created: 2022-10-21T03:07:43.957Z
guid: 9f5fff8c-6e6b-48a3-bfb3-36fa13a47f9c
---
Ever worked on a project that had many different repositories, but all needed to build and deploy the same way. i.e. build a docker file and push it. You’d have to copy and paste it all around and create a bunch of duplicated code. 

Copying and pasting the same code sucks, as a wise programmer once said, don't repeat yourself. Let's see how you can do this with GitHub's reusable workflows

<!--endintro-->



| Reusable workflows                                 | Composite actions                                                |
|:----------------------------------------------------:|:------------------------------------------------------------------:|
| Cannot call another reusable workflow              | Can be nested to have up to 10 composite actions in one workflow |
| Can use secrets                                    | Cannot use secrets                                               |
| Can use if: conditionals                           | Cannot use if: conditionals                                      |
| Can be stored as normal YAML files in your project | Requires individual folders for each composite action            |
| Can use multiple jobs                              | Cannot use multiple jobs                                         |
| Each step is logged in real-time                   | Logged as one step even if it contains multiple steps            |

**Figure: Reusable workflows vs Composite actions**

View the limitations of reusable workflows [GitHub Docs](https://docs.github.com/en/actions/using-workflows/reusing-workflows#limitations)


::: bad
Figure: Bad example - Copy and pasting the same code 
:::

::: good 
Figure: Using GitHub's reusable workflows 
:::

TODO: Link to an example repo -> Checkout the documentation and example code here: https://todo-this.github.com 
