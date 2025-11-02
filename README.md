# ntodo
a nested list todo app


Design rules

No CSS.
Use only HTML structure and <br> for spacing.

Mobile-friendly.
Must include <meta name="viewport" content="width=device-width, initial-scale=1">.

Two pages only.
index.html (list view) and edit.html (task editor).

Use links, not buttons.
All actions are <a> elements separated by pipe (|).

Flat simplicity.
No external libraries, no frameworks, no styling.

Show due dates only if present.
Hide “no due date” text completely.

Tasks are links.
Clicking a title navigates to edit.html#<task_id>.

Unlimited nesting.
Subtasks render recursively using <ul>.

Whitespace via <br>.
Use <br> between items and after lists for readability.

Persist data locally.
Use localStorage key todolist_v3.

Prompt-based editing for subtasks.
Subtasks added via prompt() calls.

Confirm destructive actions.
Deletion requires confirmation dialog.

Plain text inputs only.
No dropdowns, rich text, or formatting.

Self-contained.
Each HTML file runs independently without imports or shared scripts.
