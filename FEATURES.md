# Feature map

One line per thing NanumOS can do, with an honest status. This is the data behind https://nanumos.com/map as of 2026-11-18. Machine-readable: [features.json](features.json).

How to read the status words:

- **done**: a test runs it and it passes.
- **partly done**: the code is there but the feature is incomplete or no test checks it yet.
- **in progress**: someone is working on it right now.
- **being fixed**: its test is failing and a fix is under way.
- **planned**: decided, not built yet.

"Progress" counts done as 1 and partly done / in progress as half.

## Totals

| Status | Features |
| --- | ---: |
| done | 3803 |
| partly done | 4018 |
| in progress | 423 |
| being fixed | 32 |
| planned | 1902 |
| **all** | **10178** |

## By area

| Area | Features | Done | Partly done | In progress | Being fixed | Planned | Progress |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Apps | 4059 | 1967 | 440 | 104 | 0 | 1548 | 55% |
| Kernel | 2184 | 766 | 1246 | 137 | 25 | 10 | 67% |
| Server edition | 680 | 298 | 293 | 36 | 0 | 53 | 68% |
| Desktop edition | 3229 | 772 | 2039 | 146 | 7 | 265 | 58% |
| Phone | 5 | 0 | 0 | 0 | 0 | 5 | 0% |
| Developers (SDK) | 21 | 0 | 0 | 0 | 0 | 21 | 0% |

## Apps

| Part | Features | Done | Partly done | In progress | Being fixed | Planned | Progress |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| App settings | 165 | 125 | 7 | 33 | 0 | 0 | 88% |
| Archives & Korean documents | 10 | 0 | 0 | 0 | 0 | 10 | 0% |
| Calendar | 112 | 13 | 28 | 2 | 0 | 69 | 25% |
| Contacts | 63 | 4 | 16 | 5 | 0 | 38 | 23% |
| Files | 140 | 15 | 35 | 5 | 0 | 85 | 25% |
| Mail | 199 | 14 | 15 | 6 | 0 | 164 | 12% |
| Manuals | 75 | 75 | 0 | 0 | 0 | 0 | 100% |
| Notepad | 81 | 4 | 5 | 2 | 0 | 70 | 9% |
| Other apps (one dot per app) | 61 | 22 | 9 | 30 | 0 | 0 | 68% |
| Photo Retouch | 881 | 830 | 51 | 0 | 0 | 0 | 97% |
| Planned work | 3 | 0 | 0 | 0 | 0 | 3 | 0% |
| Reminders | 59 | 4 | 16 | 1 | 0 | 38 | 21% |
| Video Retouch | 633 | 383 | 122 | 1 | 0 | 127 | 70% |
| zOffice Documents | 345 | 128 | 54 | 5 | 0 | 158 | 46% |
| zOffice Sheet | 837 | 279 | 43 | 1 | 0 | 514 | 36% |
| zOffice Slides | 395 | 71 | 39 | 13 | 0 | 272 | 25% |

## Kernel

| Part | Features | Done | Partly done | In progress | Being fixed | Planned | Progress |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Being fixed | 25 | 0 | 0 | 0 | 25 | 0 | 0% |
| Display & console | 28 | 4 | 23 | 1 | 0 | 0 | 57% |
| Driver device IDs | 133 | 21 | 38 | 74 | 0 | 0 | 58% |
| Filesystem | 219 | 103 | 116 | 0 | 0 | 0 | 74% |
| Filesystem (flags) | 6 | 0 | 6 | 0 | 0 | 0 | 50% |
| Input devices | 33 | 25 | 8 | 0 | 0 | 0 | 88% |
| Input devices (flags) | 1 | 1 | 0 | 0 | 0 | 0 | 100% |
| Kernel contract docs | 186 | 125 | 61 | 0 | 0 | 0 | 84% |
| Kernel to fix | 5 | 0 | 0 | 0 | 0 | 5 | 0% |
| Left on paused work | 3 | 0 | 0 | 0 | 0 | 3 | 0% |
| Loader & pack | 189 | 19 | 166 | 4 | 0 | 0 | 55% |
| Memory & address space | 19 | 3 | 16 | 0 | 0 | 0 | 58% |
| Network layer | 353 | 116 | 232 | 5 | 0 | 0 | 66% |
| Network layer (flags) | 14 | 2 | 11 | 1 | 0 | 0 | 57% |
| Other kernel | 43 | 1 | 41 | 1 | 0 | 0 | 51% |
| Planned work | 2 | 0 | 0 | 0 | 0 | 2 | 0% |
| Power & ACPI | 24 | 10 | 14 | 0 | 0 | 0 | 71% |
| Rules to keep | 57 | 33 | 24 | 0 | 0 | 0 | 79% |
| SMP, interrupts, CPU | 36 | 3 | 33 | 0 | 0 | 0 | 54% |
| Security & accounts | 77 | 18 | 59 | 0 | 0 | 0 | 62% |
| Sound | 76 | 36 | 40 | 0 | 0 | 0 | 74% |
| Stability & records | 34 | 1 | 31 | 2 | 0 | 0 | 51% |
| Stability & records (flags) | 1 | 0 | 1 | 0 | 0 | 0 | 50% |
| Storage drivers | 78 | 18 | 59 | 1 | 0 | 0 | 62% |
| Syscalls (own numbers) | 93 | 39 | 6 | 48 | 0 | 0 | 71% |
| Syscalls, processes, threads | 66 | 6 | 60 | 0 | 0 | 0 | 55% |
| Time & timers | 37 | 12 | 25 | 0 | 0 | 0 | 66% |
| USB | 107 | 24 | 83 | 0 | 0 | 0 | 61% |
| Virtualization | 118 | 48 | 70 | 0 | 0 | 0 | 70% |
| Virtualization (flags) | 2 | 1 | 1 | 0 | 0 | 0 | 75% |
| Wi-Fi | 119 | 97 | 22 | 0 | 0 | 0 | 91% |

## Server edition

| Part | Features | Done | Partly done | In progress | Being fixed | Planned | Progress |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| HTTP server (httpd) | 5 | 5 | 0 | 0 | 0 | 0 | 100% |
| Left on paused work | 11 | 0 | 0 | 0 | 0 | 11 | 0% |
| Linux program syscalls (168) | 185 | 91 | 69 | 25 | 0 | 0 | 75% |
| Mail server internals | 128 | 41 | 86 | 1 | 0 | 0 | 66% |
| Mail: IMAP commands | 34 | 30 | 2 | 2 | 0 | 0 | 94% |
| Mail: SMTP commands | 14 | 14 | 0 | 0 | 0 | 0 | 100% |
| Measured server steps | 35 | 33 | 2 | 0 | 0 | 0 | 97% |
| Moving services | 17 | 0 | 2 | 0 | 0 | 15 | 6% |
| Planned work | 1 | 0 | 0 | 0 | 0 | 1 | 0% |
| Response codes | 30 | 4 | 0 | 0 | 0 | 26 | 13% |
| TLS & ACME | 97 | 46 | 51 | 0 | 0 | 0 | 74% |
| WebDAV methods | 12 | 10 | 0 | 2 | 0 | 0 | 92% |
| git protocol | 9 | 4 | 2 | 3 | 0 | 0 | 72% |
| git server (gitd) | 102 | 20 | 79 | 3 | 0 | 0 | 60% |

## Desktop edition

| Part | Features | Done | Partly done | In progress | Being fixed | Planned | Progress |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Assistant & speech | 98 | 30 | 65 | 3 | 0 | 0 | 65% |
| Basics: archive | 12 | 10 | 1 | 0 | 0 | 1 | 88% |
| Basics: comm | 7 | 3 | 3 | 0 | 0 | 1 | 64% |
| Basics: crypto | 11 | 6 | 3 | 0 | 0 | 2 | 68% |
| Basics: dev | 10 | 5 | 1 | 0 | 0 | 4 | 55% |
| Basics: device | 14 | 1 | 3 | 2 | 0 | 8 | 25% |
| Basics: format | 47 | 27 | 9 | 3 | 0 | 8 | 70% |
| Basics: hash | 8 | 8 | 0 | 0 | 0 | 0 | 100% |
| Basics: net | 19 | 7 | 5 | 2 | 0 | 5 | 55% |
| Basics: server | 13 | 3 | 3 | 2 | 0 | 5 | 42% |
| Basics: system | 36 | 16 | 4 | 4 | 0 | 12 | 56% |
| Basics: text | 14 | 12 | 1 | 0 | 0 | 1 | 89% |
| Basics: web | 9 | 2 | 5 | 1 | 0 | 1 | 56% |
| Commands | 1176 | 316 | 649 | 28 | 7 | 176 | 56% |
| Dock, launcher, search | 231 | 88 | 110 | 33 | 0 | 0 | 69% |
| Left on paused work | 1 | 0 | 0 | 0 | 0 | 1 | 0% |
| Manuals | 63 | 63 | 0 | 0 | 0 | 0 | 100% |
| Notifications & clipboard | 34 | 8 | 26 | 0 | 0 | 0 | 62% |
| Planned work | 40 | 0 | 0 | 0 | 0 | 40 | 0% |
| Settings panes | 92 | 13 | 73 | 6 | 0 | 0 | 57% |
| Windows & workspaces | 1294 | 154 | 1078 | 62 | 0 | 0 | 56% |

## Phone

| Part | Features | Done | Partly done | In progress | Being fixed | Planned | Progress |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Planned work | 5 | 0 | 0 | 0 | 0 | 5 | 0% |

## Developers (SDK)

| Part | Features | Done | Partly done | In progress | Being fixed | Planned | Progress |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| Most-used apps | 19 | 0 | 0 | 0 | 0 | 19 | 0% |
| Planned work | 2 | 0 | 0 | 0 | 0 | 2 | 0% |

## Apps and their stage

Stage "lab" = works but not yet at the bar for the stable list; "stable" = passed it.

| App | Stage | What it does |
| --- | --- | --- |
| Nanum Analytics | lab | See how many people visit your homepage, in the familiar web-analytics layout. |
| Automation | lab | Make 「when → what」 rules and the computer does the job at that time for you. |
| Nanum Blog | lab | Write posts on your own computer and publish them on your own web server. |
| Books | lab | Read EPUB books like a printed book, two pages side by side in a wide window. |
| Broadcast | lab | Your own radio station: several channels, an AI host on each. |
| ZBrowser | stable | A full-screen browser for web addresses. |
| Calculator | stable | Type a sum and get the answer. |
| Calendar | stable | See a month, a week or a day and write your events with their times. |
| the full web browser | lab | Opens web sites in the Mac web view, or in ZBrowser. |
| Clock | stable | World clock, alarm, stopwatch and timer. |
| Color Meter | stable | Shows the colour of the screen under the pointer as hex and RGB, and copies it. |
| Console | stable | Read the lines the computer and its apps log. |
| Contacts | stable | One card per person. |
| Phone | stable | Call people on the ZEUS exchange; 「Call Zeus」 talks with the assistant. |
| Dictionary | stable | Look up a word, hear its example sentences read whole, review your notebook. |
| Disk Utility | stable | See the size and use of the disks and USB sticks, and eject a stick safely. |
| zOffice Documents | stable | A word processor for document, Hangul (.hwpx, .hwp) and OpenDocument (.odt) files. |
| Drawings | lab | Draw diagrams and simple pictures: shapes, arrows, lines and text on a page. |
| Files | stable | See and organise your folders and files: open, rename, move, trash. |
| Font Book | lab | Install, remove and preview your own fonts. |
| Forms | lab | Make forms, try them, and collect and count the answers on this device. |
| Games | lab | Nine small games in one app. |
| Help | stable | Read and search the manuals. |
| Data Import | stable | Bring passwords, mail and files over from another computer. |
| Keep | lab | Pin your notes as cards and sort them by colour, pin, label and reminder. |
| Mac Apps | lab | Open a Mac app from NanumOS: one press brings it to the front. |
| Mail | stable | Read and write e-mail. |
| Messenger | lab | End-to-end encrypted conversations between the people of this computer. |
| USB Maker | stable | Make a boot USB, write an image to a stick, or save a stick as an image. |
| Music | stable | Play your music by album. |
| Network Utility | stable | Check whether your network works. |
| News | stable | You subscribe to outlets' RSS feeds and read them; articles are never stored. |
| Notepad | stable | A notepad that saves as you type. |
| Pager | lab | A small app that sends a beep, your voice and a number code to a friend or to Zeus. |
| Paint | lab | Draw and edit pictures (Lab): selections, levels, masks, clone stamp, history. |
| PDF | stable | Read PDF documents. |
| Phone Mirror | lab | Your Android phone's screen in a window, used from here (Lab). |
| Photo Booth | stable | A camera that shoots the moment you press. It all goes to Photos › Camera. |
| Photos | stable | Your pictures by day; pictures without a date go under "Default Pictures". |
| Zeus Radio | stable | Pick a radio station from all over the world and listen. |
| Remote Desktop | lab | Use another computer's screen in a window, or share this one. |
| Reader | stable | Reads a page as clean text. |
| Reminders | stable | Lists of things to do, with alerts. |
| Photo Retouch | lab | Open, fix, and give many photos the same edit at once - in the store, offline. |
| Screenshot | stable | Saves the screen or one window as a PNG; Zeus can take one too. |
| Security | stable | See if this computer is safe; check passwords and permissions. |
| Settings | stable | Change the screen, sound, language and more. |
| zOffice Sheet | stable | A spreadsheet for numbers, text and formulas, worked out as you type. |
| Shopping | lab | Find prices across shops at once; hear when a saved item gets cheaper. |
| Sites | lab | Build a small web site on your device and export it as a zip or a folder. |
| zOffice Slides | lab | Make slides and present them full screen. |
| Stocks | lab | Your watchlist's prices and charts at a glance. |
| System | stable | What this computer is and how it is doing, in one window. |
| Tasks | stable | See what runs and how busy the computer is, and find out why it is slow. |
| Terminal | stable | The window where you type commands. |
| To Do | lab | Keep your tasks in lists, tick them off and set dates. |
| Translate | lab | Korean ↔ English translation, on this computer or with your own API key. |
| Unit Converter | stable | Convert lengths, weights, temperatures and more. |
| Vault | stable | A safe place for your passwords. |
| Dohan | lab | Draw and edit vector art: logos, labels and shapes. |
| Video | lab | Open video files. |
| Video Retouch | lab | Join and cut the videos you recorded, add a title and music, and export. |
| Viewer | stable | View pictures and files at full size. |
| Virtual Machines | lab | Create and run virtual machines. |
| Voice Memos | lab | Record and keep voice memos. |
| Weather | stable | The weather now and a week ahead. |
| Web Apps | lab | Sites are the Browser's favourites now; this chapter is the Lab's web-app code. |
| Wire | lab | Links your devices like one home network, anywhere. Also in Settings › Wire. |
| zcloud | stable | Your photos, documents and vault on the home NAS at a glance. |
| Zeus | stable | An AI assistant you ask in plain words. |

## Became done in the last days (up to 7 days, up to 40 lines)

- 2026-11-18: Tells the folder git server uses for temporary work (Server edition, git server (gitd))
- 2026-11-18: Locks a file so others wait (Server edition, Linux program syscalls (168))
- 2026-11-18: Tells the scheduler that a job list changed (Kernel, Time & timers)
- 2026-11-18: Files held in memory follow a fixed folder layout (Kernel, Rules to keep)
- 2026-11-18: the assistant button inside an app = OUR logo (the tile mark in the chosen (Desktop edition, Windows & workspaces)
- 2026-11-18: Works out how much room the Dock has (Desktop edition, Windows & workspaces)
- 2026-11-18: Tells whether the radio or Music is the one playing (Desktop edition, Windows & workspaces)
- 2026-11-18: Handles media keys: play-pause, stop, next, previous (Desktop edition, Windows & workspaces)
- 2026-11-18: Draws the icons on the desktop (Desktop edition, Windows & workspaces)
- 2026-11-18: Draws the desktop wallpaper (Desktop edition, Windows & workspaces)
- 2026-11-18: An internal detail of this area (Desktop edition, Windows & workspaces)
- 2026-11-18:  (Desktop edition, Windows & workspaces)
- 2026-11-18: true = allowed, go on; false = the card is up and go runs on [허락] (Desktop edition, Settings panes)
- 2026-11-18: An internal detail of this area (Desktop edition, Settings panes)
- 2026-11-18:  (Desktop edition, Settings panes)
- 2026-11-18: OS manual chapter: Widgets — calendar, weather and notes on the desktop (Desktop edition, Manuals)
- 2026-11-18: under the windows and the icons (Desktop edition, Dock, launcher, search)
- 2026-11-18: the pixels of cw x ch cells whose right column is hc from the right edge, top row hr (Desktop edition, Dock, launcher, search)
- 2026-11-18: the gallery + the jiggle (right click, Settings, the assistant) (Desktop edition, Dock, launcher, search)
- 2026-11-18: the first free place; the index, -1 no room (Desktop edition, Dock, launcher, search)
- 2026-11-18: the bar's bottom to the Dock's top (the one work-area function) (Desktop edition, Dock, launcher, search)
- 2026-11-18: every frame: the edit mode's jiggle, the delayed save (Desktop edition, Dock, launcher, search)
- 2026-11-18: Tells the assistant what the open survey asks and has collected (Desktop edition, Dock, launcher, search)
- 2026-11-18: Lets the assistant add questions and fill in a survey (Desktop edition, Dock, launcher, search)
- 2026-11-18: An internal detail of this area (Desktop edition, Dock, launcher, search)
- 2026-11-18: An internal detail of this area (Desktop edition, Dock, launcher, search)
- 2026-11-18: An internal detail of this area (Desktop edition, Dock, launcher, search)
- 2026-11-18: An internal detail of this area (Desktop edition, Dock, launcher, search)
- 2026-11-18: An internal detail of this area (Desktop edition, Dock, launcher, search)
- 2026-11-18: An internal detail of this area (Desktop edition, Dock, launcher, search)
- 2026-11-18: An internal detail of this area (Desktop edition, Dock, launcher, search)
- 2026-11-18: An internal detail of this area (Desktop edition, Dock, launcher, search)
- 2026-11-18: An internal detail of this area (Desktop edition, Dock, launcher, search)
- 2026-11-18:  (Desktop edition, Dock, launcher, search)
- 2026-11-18:  (Desktop edition, Dock, launcher, search)
- 2026-11-18:  (Desktop edition, Dock, launcher, search)
- 2026-11-18: u blog build [-h HOME] [-o OUTDIR] Nanum Blog's engine: publish the scheduled posts that (Desktop edition, Commands)
- 2026-11-18: Shows the current date and time (Desktop edition, Commands)
- 2026-11-18: Sets a variable before the script starts (Desktop edition, Commands)
- 2026-11-18: Deletes without asking or complaining (Desktop edition, Commands)
