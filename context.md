# Matthew Bis - Content Context

## Brand & Positioning
- **Name / handle:** Matthew Bis, LinkedIn personal brand under his own name
- **LinkedIn:** https://www.linkedin.com/in/matthewjbis/
- **Personal site:** https://mattbis.com/
- **Leverage:** https://leverage.mattbis.com/
- **Blog:** https://blog.mattbis.com/ (Hashnode, RSS synced)
- **Positioning:** Practitioner over trend-chaser. Production honesty ("what broke"), senior deterministic judgment in an agent-saturated market, RevOps/outbound GTM infrastructure built with real systems.
- **Core philosophical stance:** Deterministic pipelines are preferable to premature agentic architecture. Autonomy is added only where task shape forces it, and earned over time - a temporal argument, not a spatial one.

## Content Pillars
1. Multi-agent architecture
2. Outbound/email and cold outreach
3. AI in production
4. GTM infrastructure/RevOps
5. Career/positioning

## Hard Content Rules
- No em-dashes
- No hashtags
- No company names (employers, clients, etc.)
- No raw dollar figures - ratios and percentages only
- ~1,150 character target for feed posts
- Plain text for opinion/philosophy posts; carousels for frameworks/technical content
- No engagement-bait mechanics
- No specific revenue figures or campaign dollar amounts
- Strip anything that could be pointed to as protected/proprietary work info

## Voice Principles
- Consistent register, natural rhythm - reads as typed while annoyed, not optimized
- Over-polished is wrong; fix with targeted removal, not full rewrite
- Concrete production failure details > abstract claims
- Ratios over raw numbers
- "Wrong way - right way" contrarian structure used consistently
- First-comment strategy: preempt the strongest objection in the thread

---

## PUBLISHED CONTENT (chronological where known)

### 1. "The carpenter who refused to use a nail gun" - Career/Positioning
*Posted: Thursday, April 9th*

The carpenter who refused to use a nail gun didn't become a better carpenter. He became slower, more expensive, and eventually irrelevant.

I keep hearing the same arguments:
- AI is replacing thinking
- It's making us dumber
- It's hollowing out real skill.

That's not a position. That's fear dressed up as principle.

The people saying this are telling on themselves. They're admitting that what they know is their only advantage. Not how they think. Not their judgment. Not their ability to navigate complexity. Just the static knowledge they've accumulated.

That's a brittle advantage. And they know it.

Here's what I've learned building with AI every day:

It doesn't think for you. It literally can't.

What it does is compress the distance between your idea and your output.
You still need the idea. You still need to know when the output is wrong. You still need taste.

AI is the whetstone. You're the blade. A dull blade on a good whetstone gets sharper. A sharp blade without one still cuts. But refusing to sharpen because you're proud of your edge? That's how you end up in a drawer.

The doomer narrative isn't deep. It's not even cautious. It's the path of least resistance disguised as critical thinking.

Here's what's actually happening: the era of the rigid specialist is compressing. The people pulling ahead are generalists. Polymaths. People who chase curiosity across domains and use AI to close the skill gaps between what they know and what they need to build.

You don't need a decade of experience in every field anymore. You need taste, judgment, and the willingness to learn in public by building real things.

That's not a threat but rather the most optimistic shift in how work has functioned in our lifetime.

The tools are not going away. They're accelerating. The people who figure out how to think with them will build things the holdouts can't even conceptualize.

Adapt or become the cautionary tale you keep warning everyone about.

---

### 2. "Stop saving prompts" - GTM Infrastructure / Context Ops seed
*Posted: June 9th, 2026*

Stop saving prompts.

There's a name for what a prompt library really is: the Collector's Fallacy. The belief that saving something is the same as knowing it. You bookmark the clever prompt, feel a hit of progress, and learn nothing. A stack of answers to a test you never studied for.

A prompt isn't a shortcut around thinking. It's the output of thinking. The best one you'll ever write is the one you build in the moment, because you understand the problem in front of you.

You know what to make explicit and what the model can infer. That judgment doesn't live in a document. It comes from reps.

Here's the part most people miss: hallucination is usually a context problem, not a prompt problem. The model fills gaps with plausible fiction because you never gave it the ground truth. No clever wording fixes that. Better context does.

Which is where the real shift happens.

Prompts are ephemeral and task-specific. Context is structural and durable: a reliable source of truth about the business, the ICP, the voice, the constraints. The model reasons better because it knows more, not because it was asked more cleverly.

Prompt engineering is a skill. Context architecture is a system. One scales with you. The other scales with your whole org.

---

### 3. "Linguistic precision is the real AI skill gap" - Career/Positioning
*Post #3*

Most people can't get AI to work.

It's not a tech problem. It's a language problem.

I've watched engineers with decades of experience produce mediocre AI outputs. Then watched people with zero technical background build remarkable things with the same tools.

The difference isn't intelligence. It's linguistic precision.

Large language models are exactly what the name says. Language models. They respond to the quality, structure, and intentionality of your input.

Vague input produces vague output. Precise input produces precise output. Every single time.

The people winning with AI right now share a specific profile:

They understand that context is load-bearing. They know how to constrain a problem linguistically before throwing it at a model. They recognize when output is drifting and can correct it through language, not frustration.

None of that is in a prompting tutorial. It's pattern recognition. It's the ability to model how your words will be interpreted before you hit send.

Here's what that looks like in practice:

Two people write the same prompt. One gets generic slop. The other gets production-ready output.

The difference isn't a secret framework. It's one person framing the task with precision... role, constraints, structure, intent, and the other just describing what they want.

Describing is not instructing. Most people never learn the difference.

The actual skill gap in the AI era isn't coding. It's knowing how to communicate with a system that thinks in language - precisely, intentionally, and with enough structural awareness to get what you actually need.

That's linguistics. And it's been undervalued for a long time.

I came to AI through language, not through code.

Turns out that was the advantage.

---

### 4. "I stopped using the n8n UI. I build workflows from my terminal." - AI in Production
*Caption + carousel (7 slides, Gamma, Mystique dark theme)*

**Caption:**

I stopped using the n8n UI.

I build and deploy workflows from my terminal now. Plain English in, production workflow out.

The tool is the n8n MCP server. It indexes 1,396 n8n nodes, 2,600+ real configuration examples, and 2,709 workflow templates. Then it exposes all of it as tools Claude Code can call.

Here's the workflow:
Describe what you want automated. Claude Code searches the node library, finds the right components, validates the config against real examples (not guesswork) and deploys the workflow to your live instance.

No drag-and-drop. No digging through docs. No guessing at node parameters.

Add a new workflow to n8n, the agent can use it immediately.

But n8n is one use case. MCP servers exist for Postgres, GitHub, Salesforce, Sentry, Google Drive, Puppeteer... over 10,000 active servers and counting.

The protocol is adopted by Anthropic, OpenAI, and Google DeepMind. It's not experimental.

But MCP isn't magic. It's plumbing. And good plumbing is what separates demos from production systems.

Stop name-dropping it. Build with it.

**Carousel slide content:**
- Slide 1 (Hook): "AI IN PRODUCTION - I stopped using the n8n UI. I build workflows from my terminal. Claude Code + the n8n MCP server. Here's what this actually looks like in production."
- Slide 2 (Concept): MCP in 30 seconds - protocol for connecting AI to external tools (databases, CRMs, workflow engines, APIs). "Think USB for AI." Stats: 10K+ active servers, 97M+ monthly SDK downloads.
- Slide 3 (Tool): What n8n-MCP gives Claude Code - 1,396 nodes indexed (812 core + 584 community), 2,600+ config examples, 20 tools exposed (7 core + 13 management), 2,709 workflow templates.
- Slide 4 (Workflow): Describe -> Build -> Deploy. Plain English in, node search + config validation, tested/activated on live instance.
- Slide 5 (In Practice): Example input/output - RSS monitoring -> insight extraction -> daily Slack summary, deployed and running at 8am.
- Slide 6 (Ecosystem): MCP servers beyond n8n - Postgres, GitHub, Salesforce, Sentry, Google Drive, Puppeteer. Adopted by Anthropic, OpenAI, Google DeepMind.
- Slide 7 (Takeaway): "MCP isn't magic. It's plumbing." Pick one integration, ship it, build with it or stop talking about it.

---

### 5. "Everyone wants the agent that runs the whole job end to end" - Flagship: Deterministic vs. Agentic
*Posted: July 21*

Everyone wants the agent that runs the whole job end to end. Push a button, walk away, the work does itself.

I build these systems for a living. That fantasy is how most of them die.

Bolt an agent onto a process you never mapped, and it improvises. Every step you didn't define gets filled in at full model price, guessing through work a plain rule could have handled. 10x the tokens for a worse answer. The demo looks like magic. The invoice does not.

Start with the boring version.

A deterministic pipeline is a flowchart that runs. It forces you to define every step. Then it breaks, and where it breaks is a map: here it needs judgment, there it just needs an if-statement. So you add context where the judgment gaps are, rebuild, and run it again. Each pass makes the map more complete.

The best node in my production stack is still deterministic. It cuts 85% noise down to 6% signal before a model ever touches a record.

Now look at what you actually built. You wrote your business down.

The old moat was how good your people were. The new moat is how well your company is documented, because the business an agent can run is the business that wins. Legible beats big.

Autonomy isn't a starting point you buy. It's a graduation you earn.

---

### 6. "Why one mega-prompt fails / decompose into specialized AI nodes" - Multi-agent Architecture
*Carousel + caption*

Stop asking one prompt to do five jobs.

Research the company. Write the email. Score the lead. Check quality. Format the output. One prompt, one pass.

Works in a demo. Falls apart in production.

The model hallucinates details it wasn't given. You can't debug it because the whole thing is one black box. And your token costs are 10x what they should be.

The fix is architectural, not prompt engineering.

Decompose into specialized nodes. One agent researches. One writes. One QAs. One scores. Pick the right model per node - cheap and fast for filtering, heavy for reasoning.

Something breaks? You know exactly where. Fix that node. Everything else keeps running.

I've run this pattern in production: hundreds of CRM records daily through a four-agent chain. v1 was one mega-prompt. It hallucinated confidently and invented things that didn't exist. Decomposition fixed it.

If your AI works in testing but fails in production, it's not a prompt problem. It's an architecture problem.

**Carousel visual:** Side-by-side comparison - "The mega-prompt" (single prompt doing research/write/score/check/format, all competing for context -> hallucinations, undebuggable black box, 10x token cost) vs. "Decomposed agents" (Research agent -> Copywriter agent -> QA/evaluator -> Scoring agent -> no more hallucinations, transparent and debuggable, reduced token cost).

---

## UNPUBLISHED / BACKLOG (for reference - not yet live)
- "Every SOP is becoming a product you can sell"
- "AI rollout done poorly is a company culture killer, augment not replace"
- "Context Ops" concept post (branding decision open - term seeded but unlabeled in posts #2 and #3 above)
- Orchestration layers vs. marketing automation (drafted, pending publish)
- Hallucination war story (high priority)
- Positive reply rate post
- AI-personalized cold email framework
- Ambiguity-as-a-tool spinoff
- "Giving away three production workflows" build-in-public post
- Research -> copywriter -> QA -> scoring agent chain build walkthrough
- Model selection per node (Haiku vs Sonnet vs Opus)
- Bouncer node build (85% noise -> 6% signal)
- Deliverability fundamentals / tiered outreach
- MVP-first AI systems / batch vs event-driven / feedback loops / "fix the most embarrassing failure first"
- RSS-to-LinkedIn content pipeline / RAG for internal docs / ROI measurement on long sales cycles
- "Battle-tested in production" defined / self-taught path into GTM AI engineering / rebuilding the intelligence layer vs. bolting on AI
