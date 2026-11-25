# AI Writing Review Prototype

**README prose word count: 677**

## Status and stack

The prototype is a standalone HTML file with embedded CSS and JavaScript. The sample research summary uses scripted AI suggestions and replies. For your own draft, JavaScript rules flag selected spacing, punctuation and wording patterns. No API key, installation or server is required.

## Run and inspect

Open `IIS-A2-web-prototype.html` in a browser with JavaScript enabled.

1. In **Plan**, enter your audience and purpose, main claim, and evidence and limits. Set revision goals and select **Go to writing**. Your notes appear beside the editor in **Write**.
2. In **Write**, enter an English draft and select **Check my draft**, or choose **Use sample instead** to explore scripted suggestions.
3. In **Review**, select **Grammar** or **Claim strength** in the sample and open **Check grammar rule**. Grammar compares plural “The results show” and singular “The result shows”. Claim strength compares “may improve” and “will improve” using the same sentence. Opening the rule leaves the draft and suggestion status unchanged. The explanations and examples are embedded in the HTML.
4. Apply the **Grammar** suggestion to use “The results show”. For **Claim strength**, choose **Apply suggestion → Check source evidence** to highlight the sentence about a small pilot, then **Keep original** if you want to retain “may improve”.
5. In **History**, look for the evidence check and the decision. Select **Export review log** to save the activity as text.
6. In **Finish**, select **Download .txt** or **Copy final draft**. Select **Continue writing from this version** to transfer the revision to **Write**.

Planning notes, revision goals and text in **Write** are saved in that browser when storage is available. Reloading resets review decisions and history. Export anything you want to retain before reloading.

## Development record

In A1, I asked when explanations help students decide whether to follow AI advice. I kept academic writing as the setting for A2. The example I wanted the prototype to show is simple: “will improve” reads smoothly, but it makes a stronger claim than “may improve”. I wanted the writer to see that difference and check the pilot-study sentence before deciding.

The first version showed a comparison and let the writer apply or decline an edit. I wanted more room to inspect the text and revisit decisions, so I asked for separate pages and a fuller review workflow. The final version includes planning notes, draft editing, revision history and a separate page for the finished draft. A scripted check of the final HTML exercised Plan, both sample decisions, History, and continuing to write from Finish. It checked that Plan notes were saved and displayed, the grammar correction was applied, the warning left the draft intact, and keeping the original claim preserved “may improve” and logged both actions. This check used a simulated DOM. The public history begins with the final prototype snapshot.

- [Final prototype snapshot](https://github.com/Rowneya0521/iis-a2-writing-review/commit/9f9d6cb846d559e0bbc0c3265962e5a439be6c0d)
- [Documented the five-page workflow](https://github.com/Rowneya0521/iis-a2-writing-review/commit/7e7e8c91aa289abd2d9a90e01406d915b49cf9d7)
- [Clarified the design contribution and AI assistance](https://github.com/Rowneya0521/iis-a2-writing-review/commit/045e087604141d7fd49894ebc626d946f42ef006)

## Grammar reference verification

Codex opened the updated standalone HTML in Chrome and exercised the built-in sample through the browser interface.

| Check | Observed result |
| --- | --- |
| Open **Check grammar rule** on **Grammar** and **Claim strength** | Both cards displayed their explanations and two examples. Opening each rule left its original sentence in the draft and its status at **Pending**. |
| Apply the **Grammar** suggestion | The draft changed to “The results show”. History recorded **Grammar · Applied AI suggestion**. |
| Check the evidence for **Claim strength**, then keep the original | The interface reported the source highlight for “small pilot”. History recorded **Opened source evidence** and **Kept original** for **Claim strength**. The final draft retained “may improve” alongside the applied grammar correction. |

This run exercised the sample workflows in Chrome and did not involve human participants. The simulated DOM check described in the development record was performed on the earlier prototype.

## AI assistance

I chose the question, set the scope and reviewed the interface as it developed. I used ChatGPT and Codex to help implement and debug the prototype, organise the documentation and run scripted checks. For example, I asked for separate pages after the single-screen version felt incomplete. I also kept the option to preserve the original wording. This matters when a fluent rewrite could overstate the evidence. The sample text and storyboard were prepared for this project.
