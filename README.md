<div align="center">

# 🏫 Grav Open Course Space

### Ready-to-Run Skeleton Package

<p><em>An open home for one course or many – inside or outside your LMS, with content in portable Markdown files you control.</em></p>

[![Grav Discord Chat](https://img.shields.io/discord/501836936584101899.svg?logo=discord&colorB=728ADA&label=Grav%20Discord%20Chat)](https://chat.getgrav.org) [![Latest Release](https://img.shields.io/github/v/release/hibbitts-design/grav-skeleton-open-course-space?style=flat-square&label=Release)](https://github.com/hibbitts-design/grav-skeleton-open-course-space/releases/latest) [![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://github.com/hibbitts-design/grav-skeleton-open-course-space/blob/main/LICENSE) [![PHP](https://img.shields.io/badge/PHP-%3E%3D8.3-8892BF?style=flat-square&logo=php&logoColor=white)](https://learn.getgrav.org/2/basics/requirements)

<p>Try the <a href="https://demo.hibbittsdesign.org/grav-open-course-space/">demo</a></p>

<p>A free, open-source package built on <a href="https://getgrav.org">Grav CMS</a> 2 and the <a href="https://github.com/hibbitts-design/grav-theme-quark2-open-publishing">Quark 2 Open Publishing</a> theme – the twin of <a href="https://github.com/hibbitts-design/grav-skeleton-open-publishing-space">Grav Open Publishing Space</a>, with Markdown file-based content, a built-in Admin panel, and no database required.</p>

<a href="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-open-course-space/refs/heads/main/screenshots/screenshot.webp"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-open-course-space/refs/heads/main/screenshots/screenshot-dark.webp"><img alt="Courses page with a card for each of the three example courses, with their images, descriptions and instructors" src="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-open-course-space/refs/heads/main/screenshots/screenshot.webp" width="49%"></picture></a> <a href="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-open-course-space/refs/heads/main/screenshots/screenshot-2.webp"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-open-course-space/refs/heads/main/screenshots/screenshot-2-dark.webp"><img alt="Course home page with the course navbar, a header image banner, What's Happening This Week reminders, and the course sidebar" src="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-open-course-space/refs/heads/main/screenshots/screenshot-2.webp" width="49%"></picture></a><br>
<a href="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-open-course-space/refs/heads/main/screenshots/screenshot-3.webp"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-open-course-space/refs/heads/main/screenshots/screenshot-3-dark.webp"><img alt="Modules page with a card for each module and the course sidebar" src="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-open-course-space/refs/heads/main/screenshots/screenshot-3.webp" width="49%"></picture></a> <a href="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-open-course-space/refs/heads/main/screenshots/screenshot-4.webp"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-open-course-space/refs/heads/main/screenshots/screenshot-4-dark.webp"><img alt="Welcome module page with an image, a link back to the Modules page, and the module list with search beside it" src="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-open-course-space/refs/heads/main/screenshots/screenshot-4.webp" width="49%"></picture></a>

<p>Open Course Space – Courses page and a course home page (top), and the Modules page and a module page (bottom)</p>

</div>

A complete, pre-configured package that gives one course or many an open home in a single site, inside or outside your LMS. Each course has its own pages, menu, colour, header image, sidebar and footer, and content can be shared between courses. Content is stored as simple Markdown files you can keep locally, with a built-in Admin panel for browser-based editing and no database required. Runs on nearly any web hosting service.

## What Sets It Apart

- **One course or many** – a Courses page with a card for each course; with only one course, the logo goes straight to it
- **Each course its own space** – a course navbar with the course's name and pages (a dropdown when they don't fit, usually on phones), plus its own colour, header image, sidebar and footer
- **Modules or weekly units, plus a blog** – each course is organised its own way: a Modules page with a card for each module, a list of modules beside every module page, and Previous and Next buttons, as in [Grav Helios Course Hub](https://github.com/hibbitts-design/grav-skeleton-helios-course-hub), and a site Blog shared by all courses
- **A course-ready structure** – a Home page with "What's Happening This Week" reminders, plus schedule, resources and syllabus pages
- **Share content between courses** – reuse any page or section across courses with the included Page Inject plugin
- **LMS embedding without LTI** – add `/chromeless:true` or `?embedded=true` to any page URL to show only its content, ready to embed in Canvas, Moodle, Brightspace or Blackboard
- **Open authoring built in** – Git Sync keeps the site in step with GitHub or a similar Git service, with "Edit this Page" links to each page's Markdown source, and a "This page as Markdown (.md)" link on pages
- **Course content shortcodes and rich embeds** – learning objectives, key takeaways, reflections and more, with the same shortcodes as Grav Helios Course Hub, plus Google Slides, H5P, PDF, iFrame and link cards
- **Course search** – a search box in each course's sidebar and beside its modules searches just that course
- **Built on Quark 2** – Grav 2's modern default theme, with Light, Dark and Auto modes and a toggle for visitors
- **Portable by design** – your content is plain Markdown files on your server, ready to move to any tool or host if your needs change

## When is Grav Open Course Space a Good Candidate?

Grav Open Course Space is a good fit when you:

- Want an open companion site for one course or several, managed in one installation
- Want each course to have its own pages, colour and header image
- Value Git-based, open authoring of course materials
- Prefer a clean, minimal design you can adjust through theme options

Other options might be better when you:

- Want a guide or open textbook-style resource rather than course companions – consider its twin, [Grav Open Publishing Space](https://github.com/hibbitts-design/grav-skeleton-open-publishing-space)
- Want a structured course site with a table of contents on every page and a more refined design – consider [Grav Helios Course Hub](https://github.com/hibbitts-design/grav-skeleton-helios-course-hub), built on the premium Helios theme
- Want zero-server publishing directly from GitHub – consider [Docsify-This](https://docsify-this.net)
- Need real LMS features such as enrollment, grading, or student progress tracking

Already running Open Course Hub or Open MultiCourse Hub? See [Moving Existing Courses](#moving-existing-courses).

## Quick Start

Open Course Space is best suited for authors and educators comfortable with web hosting and folder-based content. An online Admin panel is included for browser-based editing – no code editor required.

### Pre-flight Checklist
1. Confirm your web server meets [Grav's requirements](https://learn.getgrav.org/2/basics/requirements) (PHP 8.3 or higher)
2. Have your web server login credentials ready (username and password)

### Installation Steps
1. **Download** the [Open Course Space Skeleton](https://github.com/hibbitts-design/grav-skeleton-open-course-space/releases/latest/download/grav-skeleton-open-course-space.zip) package
2. **Unzip** the package onto your desktop
3. **Copy** the entire Grav Open Course Space folder to your web server
4. **Open your browser** and go to your site's URL
5. **Create your site administrator account** when prompted
6. **You're done!** – press the preview icon in the Admin Panel to view your site

> [!TIP]
> When copying the Grav Open Course Space folder to your web server, copy the **entire folder** – it contains hidden files (such as `.htaccess`) that are not selected by default. Omitting these hidden files can cause problems when running Grav.

## Course Setup

Everything below is done in the Admin Panel, or by editing the files in `user/pages` if you prefer. Folder names such as `01.cpt363-basic` start with a number that sets their order.

### Site Name and Home Page

1. Open **Configuration → Site** and set **Site Title** and **Description**
2. The Courses page is the homepage; to use another page, change **Home Page** in **Configuration → System**

### Courses Page

The Courses page (`00.courses`) shows its welcome text, then a card for each course. On its **Courses** tab: **Subtitle**, **Cards Per Row** (3 unless set), **Card Image Layout**, **Description Line Limit** and **Show Search Box** (a box above the cards that searches all the courses).

### Courses

Each course is a top-level folder (`cpt363-basic`, `cpt363-intermediate`, `cpt363-advanced`) with a `course.md` page of its own and its pages inside it, using the same page names as Grav Helios Course Hub. A course's settings are on its **Course** tab:

| Setting | What it does |
|---|---|
| **Course Card Description**, **Instructor(s)**, **Course Card Image** and **Course Card Title** | The course's card on the Courses page (the image is the course's header image unless set) |
| **Courses Page Group**, **Badge Label** and **Badge Color** | A heading for the card, and a short status on it, such as "New" |
| **Show on Courses Page** | Whether the card appears |
| **Course Home Page** | The course's home page, such as `home` (its first page unless set) |
| **Course Name in Header** | The name in the course navbar, if different from the title |
| **Course Color** | A light tint of the course navbar, as in Open Course Hub (links keep the site's accent colour) |
| **Show Header Image on Home Page** | The image in the course's `headerimage` folder, as a banner on its home page |
| **Keep My Place** and **Side Box** | A "Continue reading" bar on the Modules page, and Markdown under the module list on every module page |

On its **Attribution** tab, as for a guide: **Show OER Attribution Block**, **License**, **License URL** and **Attribution Text**, shown at the bottom of every page in the course.

Each course is in the site menu, as guides are in Open Publishing Space; turn on **Hide from Menu** (on its **Advanced** tab) to leave it out, as the example courses do, so readers start from the Courses page.

The example courses each show different features: CPT363-1 and CPT363-2 are organised by modules (CPT363-2 with more page types), and CPT363-3 is organised by weekly units (`cpt363-advanced/weekly-units`) and shows an OER attribution and license on its pages.

### Adding a Course

1. Copy an existing course folder, such as `01.cpt363-basic`, and rename it
2. Set its title and card settings on its **Course** tab
3. Edit its pages, sidebar, footer and header image, and change links that still include the old folder name (such as `/cpt363-basic/modules/module-04` in the reminders)

With only one course, the logo goes straight to that course's home page. To open the site on the course too, set **Home Page** in **Configuration → System** to its home (for example `/cpt363-basic/home`) – the Courses page stays at `/courses`.

### Give a Course Its Own Address

Want a course to open at its own address, such as `cpt363.example.edu`? Point a second domain or subdomain at this site's folder (your web host's control panel can do this), then create `user/env/<that address>/config/system.yaml` with:

```yaml
home:
  alias: '/my-course/home'
```

The site's main address still opens as before, and both addresses share the same pages. A `site.yaml` beside it can also give that address its own description and share image – see Grav's [Environment Configuration](https://learn.getgrav.org/2/advanced/environment-config).

### Each Course's Pages

- **Home** – the course's "What's Happening This Week" reminders and preparations, kept in its own parts (`_reminders`, `_preparations`) and shown with Page Inject, so the same text can appear on the `lms-home` page too
- **Modules** – a **Modules** page (`module.md`) with a card for each module; each module is a **Course Page** inside it (its Description and Group set its card), with the module list beside it, a link back to the Modules page, and Previous and Next buttons through every module and page
- **Weekly units** – a blog page inside the course, as in CPT363-3; weekly units hide their post dates and tags (`hide_post_date`, `hide_post_taxonomy`)
- **Schedule, Resources, Syllabus and the like** – **Course Pages**, which can have Learning Objectives and a header image (`header_image: true`)
- **The course navbar** – lists the course's visible pages; turn on **Hide from Menu** (on the **Advanced** tab) to leave one out

Each course also has its own shared parts, which don't appear in the menu:

- **Sidebar** (`sidebar`) – beside the course's pages (not its module pages, which show the module list); without one, the course's pages are full width, and a course page such as "Essentials" in the course navbar can hold the same information, as in Grav Helios Course Hub
- **Footer** (`footer`) – the site footer is used when a course has none
- **Header image** (`headerimage`) – a banner on the course's home page

### Sharing Content Between Courses

To include a page from one course in another, add `[plugin:page-inject](/cpt363-basic/resources)` with the page's route. Edits to the original then appear in every course that includes it.

Pages for every course sit outside the courses, in the site menu: the **Blog** (`15.blog`) and **About the Courses** (`16.about-the-courses`), with the sections, important dates and policies they share.

### Theme Options

Under **Themes → My Theme** (see the [Quark 2 Open Publishing README](https://github.com/hibbitts-design/grav-theme-quark2-open-publishing#theme-options) for every option):

- **Look** – Light, Dark or Auto mode, and accent colour
- **Layout** – logo, header and footer style, and a chromeless site (no menu, sidebar or footer)
- **More** – Creative Commons license, custom menu items, and the Git Sync Link (see below)

### Embedding in Your LMS

Add one of these to any page's address to show only its content, without the menu, sidebar or footer, ready to embed in a Canvas, Moodle, Brightspace or Blackboard page:

| Add to the address | For example |
|---|---|
| `/chromeless:true` | `https://yoursite.com/cpt363-basic/home/chromeless:true` |
| `?embedded=true` | `https://yoursite.com/cpt363-basic/home?embedded=true` |

Each course's `lms-home` page shows just that course's reminders and preparations, ready to embed as your LMS course's home page.

Pages can also be reused as Markdown: a "This page as Markdown (.md)" link below a page's content gets that page as Markdown (the same as adding `.md` to its address, for example `/cpt363-basic/syllabus.md`). Its settings are under **Reuse Pages as Markdown** in **Themes → My Theme**, and Grav's Markdown output can be turned off in **Configuration → System → Content**.

### Git Sync and "Edit this Page"

1. Set up Git Sync with its own menu item in the Admin Panel, with a repository on GitHub, GitLab, Bitbucket or your own server
2. Under **Themes → My Theme → Git Sync Link**, choose where the link appears and whether it views or edits each page's source

### Callouts and Shortcodes

Start a blockquote with `> [!NOTE]`, `> [!TIP]`, `> [!IMPORTANT]`, `> [!WARNING]` or `> [!CAUTION]` for a callout; the `cpt363-intermediate` Home page's announcement shows an example.

For course content, wrap it in one of these shortcodes, such as `[objectives]...[/objectives]` (see Week 1 of `cpt363-advanced`). Each one except `[excerpt]` can have its own heading, such as `[objectives title="By the end of this week"]`:

| Shortcode | Default heading |
|---|---|
| `[objectives]` | Learning Objectives |
| `[key-takeaways]` | Key Takeaways |
| `[reflection]` | Reflection |
| `[definition]` | Definition |
| `[example]` | Example |
| `[case-study]` | Case Study |
| `[project-brief]` | Project Brief |
| `[process-note]` | Process Note |
| `[feedback-requested]` | Feedback Requested |
| `[exercise]` | Interactive Activity |
| `[announcement]` | Announcement |
| `[references]` | References |
| `[excerpt]` | – (a quoted passage) |

These are the same as in Grav Helios Course Hub, so content moves across unchanged.

For embeds and more:

| Shortcode | What it adds |
|---|---|
| `[googleslides url="..."]` | Google Slides |
| `[pdf url="..."]` | A PDF viewer |
| `[iframe url="..."]` | Any embeddable page |
| `[h5p url="..."]` | H5P interactive content |
| `[embedly url="..."]` | A link card from Embedly |
| `[linkpreviewcard url="..."]` | A link card made on your own site, without Embedly |
| `[topics]...[/topics]` | An A–Z topics index, from single-letter headings (`## A`, `## B`, …) inside it; see `cpt363-intermediate/topics` |
| `[badge label="..."]`, `[button label="..." url="..."]` | Badges and buttons |
| `[showifembedded]`, `[hideifembedded]` | Content shown only, or never, when the page is embedded |

### Search

Search uses the SimpleSearch plugin. On a course's pages, the search box in its sidebar and beside its modules searches just that course; the Search page searches the whole site.

## Moving Existing Courses

### From Grav Open MultiCourse Hub

Courses move with no content changes:

1. Copy the courses' folders into `user/pages` – their `subsite.md` pages and settings still work (renaming one to `course.md` is optional, with Grav Helios Course Hub's field names, such as `description` for `subsite_list_description` and `course_home` for `subsite_home`)
2. Course colours carry over (`navbar_bg_color`)
3. To list a course in the site menu, remove `visible: false` from its `subsite.md`
4. In **Themes → My Theme**, set the options again – Open Matter's Bootstrap style settings have no equivalent here

Some things look different: the header image shows on each course's home page only, the course navbar replaces the Bootstrap NavBar, a course's own `favicon` folder isn't used, and custom CSS written for Bootstrap needs rewriting.

### From Grav Open Course Hub

The course sits at the site root, so it moves into its own folder:

1. Create a course folder (such as `01.cpt363`) with a `course.md` page – a title, a description for its card, and `course_home: home`
2. Move the course's pages into it, including `sidebar`, `footer`, `headerimage` and `lms-home`
3. Change links that start at the site root, such as `/schedule` to `/cpt363/schedule`, and Page Inject paths such as `/home/_reminders`
4. Update the links and embeds in your LMS, as the course's addresses now include its folder

The free [Common Cartridge Converter](https://common-cartridge-converter.hibbittsdesign.org/) (beta) turns a Canvas, Moodle, Brightspace or Blackboard course into an Open Course Hub course, which can then be moved in the same way.

## Requirements

- PHP >= 8.3
- Grav CMS 2.1 or newer (included in the package)

## Support

**Contact and Support**

- Follow [@hibbittsdesign@mastodon.social](https://mastodon.social/@hibbittsdesign) on Mastodon for updates
- 👩🏻‍💻🧑🏻‍💻 Join the [Grav Discord](https://chat.getgrav.org) and often find me there
- Add a ⭐️ [star on GitHub](https://github.com/hibbitts-design/grav-skeleton-open-course-space) to the Open Course Space project repository
- For bugs or feature requests, [open an issue](https://github.com/hibbitts-design/grav-skeleton-open-course-space/issues) on GitHub

**Professional Services**

By leveraging his extensive UX design expertise and systems-oriented approach, Paul helps teams and individuals utilize open content in education and publication settings. Professional services include user experience and workflow consulting, premium support subscriptions, workshops, and custom development. Interested? Send a note to [paul@hibbittsdesign.org](mailto:paul@hibbittsdesign.org).

## License

MIT – Hibbitts Design
