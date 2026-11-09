# Clear-writing examples

These examples illustrate editorial choices, not stock phrases to insert into every document. Most are constructed; the SheetFrame example adapts a research explanation to show how the principles work together.

## Make an action easy to picture

Context: instructions for a person reviewing a route before departure.

Dense:

> The interface supports the assessment and modification of route segments in relation to limited sunlight before departure.

Clearer:

> Check your route before departure. Revise any sections with limited sunlight.

The revision names the reader's actions and when to take them. It removes abstract phrasing without inventing extra interface features.

## Explain the interaction before its label

An explanation can start with:

> You set the goal. The assistant proposes a route, and you decide what to keep. This shared planning process is called mixed-initiative planning.

If the surrounding writing calls for a compact introduction, the label could instead follow the explanation in parentheses. For an expert audience already discussing mixed-initiative systems, using the term directly may be more efficient.

## Keep the limits of a research finding

Dense:

> Preliminary observations from the pilot study suggest the possibility that the revised instructions may facilitate improved task completion for some participants.

Clearer:

> The pilot observations suggest that the revised instructions may help some participants complete the task.

The revision keeps the study's preliminary nature, the uncertainty, and the limited participant scope. It does not turn the observation into a demonstrated improvement or invent a numerical effect.

## Add detail when a shorter version creates work

Too compressed:

> Export failed. Retry.

If the system actually knows the cause and recovery step, a more useful message could be:

> The destination folder is read-only. Choose a writable folder, then export again.

The longer version helps the reader act. Use it only when those facts are known; clarity does not justify guessing the cause or promising a recovery that has not been established.


## Connect context, rationale, and the developing argument

This illustrative explanation is adapted from SheetFrame, an AI-assisted spreadsheet authoring system. It shows how a technical choice can follow from an interaction need.

A feature inventory leaves readers to infer the connections:

> SheetFrame has an editable workbook representation, a preview, direct editing, and version history.

A connected explanation provides those relationships:

> AI assistants can create workbooks, but users still need to check formulas and correct the results. A user's correction also needs to remain available when the AI makes a later change. SheetFrame therefore keeps workbook contents in an editable source that users and AI can both update. The preview shows the workbook produced from that source, and later requests use the latest saved version. Users can correct a cell and continue asking the AI for changes without restating the correction.

The additional context explains why the shared source matters and how the parts work together. An implementation section can then explain how the source produces the preview and export. An evaluation can return to whether users complete revisions and retain correct content, and a discussion can explain what the findings support or leave unresolved.

The paper can follow the same corrected cell through later requests and version review, giving readers a familiar example as the explanation develops. This is an option for continuity, not a requirement to use one example throughout every document. The example does not establish an empirical benefit or prescribe SheetFrame's design for other systems.

## Choose a visual that carries the explanation

For an explanation of which route sections receive limited sunlight, an annotated route image could show the relevant locations alongside a short caption. If the important idea is how those conditions change during the day, a short animation or video could make the sequence easier to follow.

Choose the visual according to the information being explained. Keep important labels and timing understandable, and provide a text description or suitable static view where useful. Use real data when making factual claims, or clearly label a constructed illustration. These are proposed examples; no image, video, or animation is included in this reference.
