---
name: spacesheep
description: "Publish a page (a report, plan, doc, design, dashboard or deck) to a private, shareable spacesheep.dev link, and read, update or share one. Use when asked to publish, deploy or share a page, to change a Spacesheep space, or when the ask carries a spacesheep.dev link."
---

# Spacesheep

Spacesheep turns an HTML page into a link people open on any device, with comments, versions and access control. Everything goes through the `spacesheep` MCP server, signed in as the person.

- **Publish:** write one self-contained HTML page (or a folder with an `index.html`) and call `create_space`. A new space is private to the person. Answer with its link.
- **Long build:** call `live_link` first and send its link before anything else. Show each step with `live_push`, then put the finished page on that space with `create_version`.
- **Update:** `create_version` on the space, with exact replacements or the whole file set.
- **Read a spacesheep.dev link:** `get_space`, then `list_files` and `get_file`.
- **Share:** `share_space` with emails or @handles. Ask the person first.
- **Check the look:** `screenshot`, at `width: 390` for a phone.
- **Designs, documents, spreadsheets:** `list_skills` shows Spacesheep's own skills (Design, Docs, Sheets). Read the one that fits with `get_skill` (`view: full`) and follow it.

How a page should look is in the server's instructions and its tools' descriptions.
