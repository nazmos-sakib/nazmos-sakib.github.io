# Filling in a project template

Open `index.html` and search for `PROJECT TEMPLATE 1` (or 2–5). Each template is one `<section class="work-item">` block. The five templates appear on the page; replace their placeholder content before publishing them as real projects.

1. **Title:** Replace `Project template 1` inside the `item-title-toggle` button. Keep the button attributes.
2. **Date:** Replace `Month YYYY` inside `startDate`.
3. **Description:** Replace the first sentence inside `summary` with what the app does.
4. **Architecture and learning:** Edit the bullet points under the two subheadings. Add or remove `<li>...</li>` lines as needed.
5. **Screenshots:** Put images in a folder such as `assets/my-app/`. Replace each image's `src` inside `slider-track` and give it a meaningful `alt` description:

   ```html
   <img src="assets/my-app/home.png" alt="My App home screen">
   <img src="assets/my-app/editor.png" alt="My App editor">
   ```

   Add or remove complete `<img>` lines to change the number of screenshots. The existing slider automatically handles the count and responsive layout; no JavaScript changes are needed. Similar image dimensions work best.

6. **Optional website link:** Add this after the title button, inside `position`, replacing the URL and accessible label:

   ```html
   <a href="https://example.com/my-app" target="_blank" rel="noopener noreferrer" aria-label="Open My App website"><span class="fa fa-external-link" aria-hidden="true"></span></a>
   ```

7. **Count:** Update `(13 + 5 templates)` in the Projects heading as templates become real projects. After filling all five, use `(18)`.

## IDs and controls

You can leave `project-template-1` through `project-template-5` unchanged when filling in the existing templates. They already have unique identifiers.

When copying a block to add another project, use a new identifier everywhere in that block. For example:

- Checkbox `id`, label `for`, and button `data-toggle`: `project-my-app`
- Description `id` and button `aria-controls`: `project-my-app-details`

Keep the slider classes and arrow buttons. Titles and the original arrows toggle the details; project rows retain their existing title-only toggle behavior.

## Notiz content

Published App contains the brief user-facing overview and screenshots. Projects contains the architecture, development takeaways, and the same screenshots. Its technical description is based on the local Notiz source: Compose/ViewModels, repository interfaces, Hilt, Room/Flow, the synchronization outbox, and repository/migration tests. Edit the takeaways to reflect your own experience.
