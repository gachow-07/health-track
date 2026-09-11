# TARGET: today's build

Choose the idea, person, interaction, and visual direction. The agent can help phrase and save your decisions after you approve them. The provided scope and review safeguards stay in place.

- **Thing:** A one-page recovery planner where a person enters recent running, lifting, sleep, and calorie information to see a recovery score, a suggested next workout, and the full list of possible workout and recovery options.
- **Audience:** People who train with runs and lifts and want a simple, understandable plan for what to do next while protecting recovery.
- **Requirements:** One working primary interaction: enter manual workout, sleep, and calorie inputs and receive a clear recovery score plus a highlighted next-step recommendation. Show the full workout menu: complete rest, mobility/recovery, easy walk, Zone 2 run, intervals/tempo run, easy lift, and heavy lift. Selected states and results are understandable; honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, tracker-app connections, or private data. Inputs are entered manually; label all sample content and workout recommendations as illustrative, not medical advice. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** A sharp, clean training-focused dashboard with the recovery score as the focal point, a clear highlighted “what’s next” workout card, a visible training-menu list, and a cool workout-themed landing animation that respects reduced-motion preferences and never obscures the main action.
- **Test:** I can enter sample sleep, calories, running, and lifting information; see a recovery score, next-workout plan, and full workout list; verify that a score below 70 does not recommend a heavy lift; and point to the standing rule’s effect in the actual preview. After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
