# 1

Your AI email assistant can read one message
and hand your passwords to a stranger
no click

It happened, 
it's called a jailbreak. 

Are you a SEEKER?
Hold that thought … i want to tell you more about 

AI agent jailbreaks and vulnerabilities:
what it is, 
how attackers invent it, 
and how to defend against it. 

hi everyone 
สวัสดีครับ
dr.kb here
grab a bowl and let’s dive into this rabbit-hole

# 2

First stop — what exactly is an AI agent jailbreak? 

A jailbreak is any trick that makes an aligned model do things it's not supposed to do. 
The term "Aligned" is the rules the model was trained with. 

# 3

input goes in, the bot thinks, calls tools, output comes back. 

And the bot also reads context — files, skills, memories, emails, web pages, databases, and more. 

# 4

Here is the crack
two ways the poison can enter
one sends direct message
or the other indirectly hides inside a file it reads
or, one can even tamper with the model's weights, if you have access 

impact and blast radius
scales with
internal capabilities
and external reaches

This is why more cracks to be expected

here on
scope is
context manipulation 
jailbreak of a blackbox

# 5

Two examples, 
documented CVEs. 
EchoLeak and the Mermaid

EchoLeak 
CVE-2025-32711 
email agent read hidden instruction, and leaked credentials
it's zero-click, happened with Microsoft 365 Copilot. 

and another one, Cursor IDE 
coding agent while rendering the infamous 'Mermaid diagram'
leaked credentials via HTTP fetch.
official record ... CVE-2025-54132 
with the nickname ... Mermaid Agent SSRF

These two got caught and got a CVE number. 
How many do you think didn't? 
Have you met one? 
Share your story. I’d love to hear.

# 6

a jailbreak isn't magic — it's a search problem. 

# 7

input probes, iteratively change
hunting the moment
"I’m sorry I cannot" 
to "Yes I can"

here example: 
first, baseline testing
direct safe 
and harm requests. 

then, mutate 
find a crack, a state drift
like this example, 
the hyphen trick

you see the drift
ye? 
a good sign ... an opening template … 
the ... pwn

next we escalate
enchantment, traps, and distractions
or grandma cooking recipe ...
more inspirations, check taxonomies

this red-team methodology
recon, pwn, escalate
OG 3-steps to break a vault
works here with AI 

recon ...
map the invisible
like boundary testing, discovering tools and APIs, mapping logic and constraints,
and eventually, reconstructing system prompt.

pwn … 
find the crack, its weakness
response state drift is the signal
short refuse to long; or partial comply; even hallucinations

lastly, escalate ...
expand from the pwn template
be creative
and move closer to your goal

# 8

the waltz we had
the three steps: recon, pwn, escalate
know that you going in loaded
here is your toolkit: templates, taxonomies, and search policy

template is the mechanics.
the dish ready-to-serve
the direct and indirect poisons.

find in Github, Reddit, community forums
publicly shared templates, typically, they are not functioning
patches kill them
or the harm trigger was scrubbed.

next, taxonomies. 
the cookbook, the inspirations 
the catalog of failure modes
like grandma roleplay to hypothetical world-building

last, the search policy. 
the engine
how to mutate prompt, and observe drift
learn more in advanced literature; or watch automated scanners like PyRIT and Garak run the loops.

# 9

and the final question ...
how to defend the core?

there are undeniable constraints:
- first, cannot protect everything. 
more guards chips away latency, utility, and creative reasoning. 
it's the Security-Service Tradeoffs.

- second, AI jailbreak is an innate-nofix problem
flaw is built-in
LLMs process unstructured human language as both data and instructions

- and also, the Minimum Jailbreak Time
taking only days to weeks after a release
faster than defender loop

- attack will get more sophisticated
and the blast radius will expand
this scales with internal Capabilities, and external Reach

This why,
recommend
shift left, defense in depth,
and human in the loop

# 10

this visual, marks the defense-in-depth
3 shields
input, output
and intent guard at the internal process

importantly
each guard follows also
human in the loop, 
zero trust, and stage isolation or sandbox practice

# 11

last, bonus page
defender toolkit

input guard
zero-trust from externals. 
isolate, and sanitize
Tool examples ... Google DeepMind CaMeL and AGENTWARD

output guard
outside reasoning loop,
guard unauthorized tool calls, APIs, and leaks
use deterministic gates, least-privilege API bounds, and kernel-level runtime monitoring

and the intent guard
Auditing steps planning and context
like memory and skills
catch context poisoning, and persistent corrupted states. 

# 12

Alright, 
that brought us here
the final checklist. 
a few tips for better AI hygiene:

Verify before trust
Audit tool calls
Limit permissions
Apply deterministic gates
and Keep human-in-the-loop

SEEKER, 
stay curious, stay safe
Until next rabbit-hole
dr.kb out
Peace!
