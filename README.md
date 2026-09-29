# AAI STATIC SITE CLONE

## Getting started

* Ensure NPX installed.
* Run `npx serve`
* Site should show up at `localhost:3000`

## TODOS

* Restore all file references; set all pointers to `/` (e.g.) to `/`
* Figure out how to get stuff that was served using query params (like `/newsletter?page=1`) to serve as the requested content, OR like edit the static file to include all content and disregard params
* Delete and/or find replacements for webform type submissions
* Delete any missing and/or broken links from anywhere they show up in HTML - for example remove the `/login` link from menus on all rendered pages
* Find any other dynamic content (GA scripts? comment submission boxes?) and check if necessary to remove or if it can maintain functionality on a static system (GA may continue to work? do we want it tho lol)
