# execution-genesis-close

This agent is a base. Once you have done it your way, tell your squad "update the agent to do it like this."

Agent 3. It writes your sales script, `squad/sales.md`, and makes your 2 links on the way, so the
script ends with both. Everything you say or send for money comes out of this 1 file.

**What is in it.**

- **The message** that carries your demo and asks for 30 minutes. No price in it.
- **How much**, the line that moves the number to the call.
- **The call:** the open, 5 to 7 questions off your buyer's problem until he says what it costs him,
  the demo walk (3 things you say while the screen shows them), what he gets in 1 breath, and the 1
  price. Then you stop talking.
- **Objections:** the 5 things he says before he pays, each answered in 1 line off your offer page.
- **Too much**, the line for a smaller job, never a cheaper one.
- **The yes:** the start date and the payment link, sent while you are both still on the call.
- **Client 2:** the 1 question that finds the next buyer.
- **No-show** and **after the call:** 1 message when he does not turn up, and 3 when the yes never
  came, on day 1, 3 and 7. No price, no discount, no "just checking in".

**Install.** Installed with the one line on aichrislee.com/free. Then quit and reopen Claude Code once.

**2 connectors.** Both live in Claude, under Customize, then Connectors.

- Cal.com, for the booking link. Make a free account at the cal.com link in the roadmap. Then click +, Add custom connector, name it Cal.com, use the URL `https://mcp.cal.com/mcp`, and sign in.
- Stripe, for the payment link. Click +, Browse connectors, pick Stripe, and sign in.

If one is missing when you run it, the agent tells you the steps and stops. Then quit Claude Code, open it again in the same folder, and run it again.

**Run it.** Run /execution-genesis-offer first, because the script is built off `squad/business.md`,
and /execution-genesis-demo, because the demo walk and the Loom come off the demo. Then type
`/execution-genesis-close`, or `/execution-genesis-close <business>` to name the demo, or say "build my
sales script".

It never sends a message, books a call or charges anyone. You send, by hand.
