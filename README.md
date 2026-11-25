# AI Writing Review Prototype

**README prose word count: 393**

## Status and stack

The prototype is a standalone HTML file with embedded CSS and JavaScript. The sample research summary uses scripted AI suggestions and replies. For your own draft, JavaScript rules flag selected spacing, punctuation and wording patterns. No API key, installation or server is required.

## Run and inspect

Open `IIS-A2-web-prototype.html` in a browser with JavaScript enabled.

1. In **Plan**, enter your audience and purpose, main claim, and evidence and limits. Set revision goals and select **Go to writing**. Your notes appear beside the editor in **Write**.
2. In **Write**, enter an English draft and select **Check my draft**, or choose **Use sample instead** to explore scripted suggestions.
3. In **Review**, inspect suggested wording and decide what to apply, keep or defer. To try the evidence checkpoint in the sample, select **Claim strength → Apply suggestion → Check source evidence**, then **Keep original**.
4. In **History**, look for the evidence check and the decision. Select **Export review log** to save the activity as text.
5. In **Finish**, select **Download .txt** or **Copy final draft**. Select **Continue writing from this version** to transfer the revision to **Write**.

Planning notes, revision goals and text in **Write** are saved in that browser when storage is available. Reloading resets review decisions and history. Export anything you want to retain before reloading.

## Development record

I carried my A1 question into A2: when can explanations help students judge whether to rely on AI advice? I chose academic writing as the setting and developed the interaction around checking a proposed edit against its evidence before accepting, keeping or rewriting it. During development I asked for a more complete workflow and separate pages, and provided the final HTML from my VS Code workspace.

The initial prototype compared wording and supported individual decisions and undo. Later revisions added alternatives, editable suggestions, selective formatting batches, an evidence checkpoint, decision notes and log export. The latest version adds planning notes, a draft editor with browser storage, and a separate final-draft view. A scripted check of the earlier prototype verified the evidence highlight, preservation of the original wording, and history entries. This README was checked against the current HTML source.

## AI assistance

I set the research question and directed the design and revisions. I used ChatGPT and Codex for assistance with implementation, code fixes, documentation and scripted checks. I reviewed the prototype and requested revisions when its workflow and presentation did not yet fit the project.
