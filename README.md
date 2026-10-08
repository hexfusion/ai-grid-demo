# AI Grid demo

An animated walkthrough of AI Grid: one endpoint in front of many llm-d sites.

View it at https://hexfusion.io/ai-grid-demo/

- Slide 1 is the AI Grid reference architecture.
- Slide 2 shows how a request is routed: the grid picks the site, llm-d picks the server.
- Slide 3 is an interactive walkthrough. Pick a flow from the dropdown: the grid's layers
  first, then demos of policy, geo fencing, routing by model, load, conversation
  affinity, and site failure.

The walkthrough is built with [FlowStory](https://github.com/noyitz/flowstory)
(Apache-2.0), whose engine is embedded in `flow.html`.
