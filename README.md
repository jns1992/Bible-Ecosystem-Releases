# Bible Ecosystem

A free suite of desktop study tools designed to help you read, discover, construct, and express your understanding of Scripture.

Everything runs locally on your machine. Your data never leaves your computer.

---

## The Apps

The ecosystem follows a natural study flow across four interconnected apps, tied together by a central launcher.

### Bible Desk &mdash; READ

Your digital Bible reading environment. Open any passage, highlight verses, write notes, and bookmark what matters. Includes inline cross-references (click any verse number to see related passages), a commentary integration panel, and a passage autocomplete that recognizes 66 books plus 130+ abbreviations. Ships with KJV, ASV, WEB, and NET translations, with a built-in translation manager for downloading additional languages.

### Bible Study Engine &mdash; DISCOVER

An interactive concept graph explorer. Build visual maps of how verses, people, events, and themes connect across Scripture. Features guided study paths, multi-root workspaces (up to 20 separate graphs), undo/redo (30 levels), and spatial viewport culling for smooth performance with large graphs. Powered by React and a local SQL database of cross-references and topical seeds.

### Study Desk &mdash; CONSTRUCT

A theology-building workspace with a freeform SVG graph editor. Create nodes (verse, concept, person, event, insight) and connect them with typed edges (supports, explains, contrast, fulfillment, typology, parallel, and more). Includes bulk node operations, graph bookmarks, sharable graph templates, advanced analytics (shortest path, cluster detection, theme heatmap), and PDF export of your finished graphs.

### Christian Writing Workspace &mdash; EXPRESS

A writing environment for devotionals, reflections, outlines, and study notes. Multiple built-in templates, full Markdown and HTML export, a document library with search, and a three-step write/review/export flow. A sidebar pulls in your study context (collections, insights, verse references) from the other apps so everything you've studied is at hand while you write.

### Launcher &mdash; HUB

The central dashboard that ties the ecosystem together. Launch any app, view a study stats dashboard with per-book Bible coverage, manage ecosystem sessions, browse your insight library, process quick captures, and export study guides. Includes a personal verse map, study milestones, session templates, and collection sharing (import/export). Also handles update notifications for new releases.

---

## How the Apps Work Together

All four apps share data through a local sync file. When you highlight a verse in Bible Desk, that highlight is available in the Study Engine. When you create an insight in the Study Engine, it shows up in Study Desk and Writing Workspace. Everything stays in sync automatically.

**Key integration features:**

- **Ecosystem Dock** &mdash; A floating navigation bar at the bottom of every app. Click an icon or press Ctrl+1/2/3/4 to jump between apps instantly. Your current verse context travels with you.
- **Cross-App Search** &mdash; Press Ctrl+Shift+Space in any app to search across all your ecosystem data: highlights, notes, insights, sessions, collections, and more.
- **"Open In..." Links** &mdash; Right-click or use toolbar buttons to send a verse or passage directly to another app. The target app opens with your selection ready.
- **Shared Settings** &mdash; Theme, font size, and default Bible translation sync across all apps. Choose from four ecosystem themes: Midnight Gold, Deep Ocean, Ember, and Parchment.
- **Notifications** &mdash; A bell icon on the dock shows session reminders, reading plan nudges, and milestone achievements.
- **Quick Capture** &mdash; Press Ctrl+Shift+N in any app to jot down a thought. Process captures later in the Launcher's Capture Inbox.
- **Study Sessions** &mdash; Start a session in the Launcher and all apps track what you read, discover, build, and write during that session. Export a formatted study guide when you're done.

---

## Installation

1. Go to the [Releases](https://github.com/jns1992/Bible-Ecosystem-Releases/releases) page
2. Download the latest `Bible-Ecosystem-Setup-*.exe` installer
3. Run the installer and choose which apps to install (all are selected by default)

**Note:** Your browser may flag the download as an uncommon file, and Windows may show a SmartScreen warning when you run the installer. This is normal for independent software that hasn't purchased a code-signing certificate. Click **"More info"** then **"Run anyway"** to proceed.

The installer requires Windows 10 or later (64-bit).

---

## Keyboard Shortcuts

These work across all apps:

| Shortcut | Action |
|----------|--------|
| Ctrl+1/2/3/4 | Jump to Bible Desk / Study Engine / Study Desk / Writing Workspace |
| Ctrl+Shift+Space | Ecosystem-wide search |
| Ctrl+Shift+N | Quick capture |
| Ctrl+Shift+S | Manual sync |
| Ctrl+Shift+E | Toggle eco-dock |
| Ctrl+/ | Show keyboard shortcuts overlay |
| Ctrl+K | Command palette (in apps that have one) |

---

## Multi-Language Support

The interface supports multiple languages. Change the display language in the Launcher settings and all apps switch together. Bible text translations can be downloaded separately through the built-in translation manager in Bible Desk.

---

## Privacy

The Bible Ecosystem is fully offline. No accounts, no telemetry, no network calls. The only outbound request is an optional check for new releases (which you can also do manually from this page). All study data is stored locally in your AppData folder.

---

## About

Built by Jesse. Free to use.

> I pray that this will be a blessing to you. I want everyone to be able to see the beauty and depth that is in God's word and to know who He is.
