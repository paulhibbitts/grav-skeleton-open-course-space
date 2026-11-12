---
title: 'Read Me'
published: true
---

# Read Me

## Create, Share and Collaborate using Grav Open Course Space!  

1. Create a new [Git](https://git-scm.com/) repository (hosted on [GitHub](https://github.com/), [GitLab](https://about.gitlab.com/), [Bitbucket](https://bitbucket.org/) or your own server) with at least one commit.
2. Set up Git Sync with the step-by-step instructions in the Admin Panel's [Git Sync](../../admin/plugin/git-sync) menu item.
3. Configure the [Git Sync Link](../../admin/themes/mytheme) settings in the Theme options to change the display and functionality of the automatically displayed Git Sync Link.

## Embed Open Course Space Page Content into Other Systems

By adding the URL parameter (i.e. flag) `chromeless:true` to any Open Course Space page you can display that page's content without the global header image, site navigation bar, sidebar and footer - a great way to seamlessly embed Open Course Space pages into other systems.  

For example, the URL [https://demo.hibbittsdesign.org/grav-open-course-space-2/](https://demo.hibbittsdesign.org/grav-open-course-space-2/) displays the site's home page with the full site around it, but the URL [https://demo.hibbittsdesign.org/grav-open-course-space-2/chromeless:true](https://demo.hibbittsdesign.org/grav-open-course-space-2/chromeless:true) will only display that page's content. Any links between Open Course Space pages will result in pages being displayed in the same manner.

## Get Any Page as Markdown

On Grav 2.1 and newer, adding `.md` to a page's address gets that page as Markdown, ready to reuse – for example `/cpt363-basic/syllabus.md`, or `/index.md` for the home page. To show a "This page as Markdown (.md)" link below each page's content, turn on **Display This Page as Markdown Link** under **Reuse Pages as Markdown** in **Themes → My Theme** (off at first), and Grav's Markdown output can be turned off in **Configuration → System → Content**.

## One Course or Many

The **Courses** page shows a card for each course on the site. To add a course, copy a course folder (such as `01.cpt363-basic`) and change the title and description in its `course.md`. To leave a course off the Courses page, set **Show on Courses Page** to No on its Course tab.

With only one course, the logo goes straight to that course's home page. To open the site on the course too, set **Home Page** to the course's home (for example `/cpt363-basic/home`) in **Configuration → System** – the Courses page stays at `/courses`.

## Give a Course Its Own Address

Want a course to open at its own address, such as `cpt363.example.edu`? Point a second domain or subdomain at this site's folder (your web host's control panel can do this), then create `user/env/<that address>/config/system.yaml` with:

```yaml
home:
  alias: '/my-course/home'
```

The site's main address still opens as before, and both addresses share the same pages. A `site.yaml` beside it can also give that address its own description and share image – see Grav's [Environment Configuration](https://learn.getgrav.org/2/advanced/environment-config).

## What Else Can the Open Course Space do for You? ##
Learn more about the capabilities of the Open Course Space project in its [README on GitHub](https://github.com/hibbitts-design/grav-skeleton-open-course-space#readme).

<hr>
<br>
Want to no longer display this page on your site?  
Delete the page 'Read Me' in your [Admin Pages panel](../../admin/pages) or set the page's 'Published' option under the 'Options' Tab to 'No'.
