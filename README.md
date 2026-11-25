# AI Writing Review Prototype

**README prose word count: 414**

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

In A1, I asked when explanations help students decide whether to follow AI advice. I kept academic writing as the setting for A2. The example I wanted the prototype to show is simple: “will improve” reads smoothly, but it makes a stronger claim than “may improve”. I wanted the writer to see that difference and check the pilot-study sentence before deciding.

The first version showed a comparison and let the writer apply or decline an edit. I wanted more room to inspect the text and revisit decisions, so I asked for separate pages and a fuller review workflow. The final version includes planning notes, draft editing, revision history and a separate page for the finished draft. A scripted check of the earlier prototype confirmed that the evidence was highlighted, the original wording was kept, and both actions appeared in History. The instructions above were checked against the final HTML.

## AI assistance

I chose the question, set the scope and reviewed the interface as it developed. I used ChatGPT and Codex to help implement and debug the prototype, organise the documentation and run scripted checks. I asked for changes where the first versions did not give the writer enough control or made the workflow hard to follow.
