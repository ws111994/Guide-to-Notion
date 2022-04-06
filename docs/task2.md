---
layout: default
title: Creating task board
nav_order: 5
---

# Creating Task Board in Notion

![image](https://user-images.githubusercontent.com/90341253/161876472-1e94ec7f-2203-41cb-8292-ad6aabc4d706.png)

In Notion, creating task board is simple. With the task board, it is easy to plan, track, and do all your work in one place. By alongside all your notes, you will be able to easily access your task board to keep you on tack.

---

### Table of contents
{: .no_toc .text-delta }
* TOC
{:toc}

---
## Commands and Keys

`Enter` is the same as `Return` on Mac OS machines. 

---

## Creating New Page

Notion is user friednly app that will not let user get lost when you try to make a new page. In order to make a task board on Notion, you will need to create a new page.

This is the image of landing page of the Nontion when you open it. 
1. Create a new page by clicking `+ New page` at the bottom left of the app. 

<img width="1517" alt="Screen Shot 2022-04-05 at 10 52 40 PM" src="https://user-images.githubusercontent.com/90341253/161904913-182bf5c4-7bbe-41a1-956c-291d14902bce.png">

![Note icon](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/icons/note.png?raw=true "Note"){: style="float: left" }
> **Note:** Your Notion can appear different depending on what you already have on your local machine, but the location of the `+ New page` will be at the same place.


2. Name your new page with proper name.
If you want to distingush this task board from other notes, you can assign an icon to it. 

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/90341253/161932543-15030bd3-b99e-4ca8-802a-ac6e3445f4e6.gif)

After creating the new page with proper title and with a icon, you will be able to locate it on the side bar on the left of the Notion.

<img width="1521" alt="Screen Shot 2022-04-05 at 11 08 13 PM" src="https://user-images.githubusercontent.com/90341253/161906749-39b48b23-6734-4bbd-9f7a-f776185cbe01.png">


## Customizing the task board


### Creating the category

After creating new page, you will now need to add heading to create categories. 
1. Type `/heading 2` to create category, then name the catagory.

<img width="1517" alt="Screen Shot 2022-04-05 at 11 28 58 PM" src="https://user-images.githubusercontent.com/90341253/161932980-8e61a351-7ae0-41c2-88de-ed15954d6823.png">

Alternatively, you can use markdown syntax to create the headings.
If you use `##` followed by single `space` press, you will be able to create a heading 2.

![ezgif com-gif-maker](https://user-images.githubusercontent.com/90341253/161910882-59bea58d-a861-446d-a231-3d26d180f94b.gif)

### Arranging the categories 

To have a better visual representation, the categories will need to be arranged horizontally on your Notion. 
In order to achieve this, you will need to click and grab the second category. Then you drag and drop to the right of the first category.

1. Click on the 6 dot icon and drag and drop the category right to the first category.

![ezgif com-gif-maker](https://user-images.githubusercontent.com/90341253/161934666-d0a2f6fc-db30-4444-936e-5ea6630ac234.gif)

*Blue lines are there to guide you where it will land.*

Repeat the process to rearrange the categories in order.

2. Locate the `•••` and select `Full width`.

<img width="1636" alt="Screen Shot 2022-04-06 at 2 19 13 AM" src="https://user-images.githubusercontent.com/90341253/161942013-71aceecc-a274-4873-b642-053aaca40a2e.png">

*You can locate the `•••` button on the right top corner of the Notion.*

<img width="1636" alt="Screen Shot 2022-04-06 at 2 23 00 AM" src="https://user-images.githubusercontent.com/90341253/161942725-4017f73c-a879-4518-adfb-ee2d211b348b.png">

3. Add dividers under each categories. 

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/90341253/161944665-f9ef6a53-976a-4008-a204-70eca7eb0658.gif)


>```
> ---
>```
After selecting the category, press `enter`, then use 3 hyphen `-` to create a divider under

---

## Creating To-Do lists

After creating appropriate columns of categories, you will add list of things to do under those categories.

1. Add the To-Do list

Input the following words and press `enter` to create To-Do list.

>```
>/to-do 
>```

![ezgif com-gif-maker](https://user-images.githubusercontent.com/90341253/161949701-d0a617cd-69b8-4af1-83c5-3ada6905d608.gif)



![Note icon](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/icons/note.png?raw=true "Note"){: style="float: left" }
> **Note:** You can tyle `[]` to create To-Do list faster.

2. Add reminders to the To-Do list

Input the following in the same field as To-Do list to add reminder.

>```
> @remind date time 
>```

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/90341253/161972710-95da345f-a52c-4404-b780-b79a8d8bab7f.gif)


*You can replace the 'date' and 'time' to desired date and time*
---

## Creating archive page to store the completed tasks

1. Create new page inside your task board.

Click on the top of the page and input this follwowing command in your Notion and press `Enter` .

>```
> /page
>```

Then name the new page "Archive" with icon of your choice.





#### Example

{: .no_toc }

```yaml
---
layout: default
title: UI Components
nav_order: 2
has_children: true
---

```

Here we're setting up the UI Components landing page that is available at `/docs/ui-components`, which has children and is ordered second in the main nav.

### Child pages

{: .text-gamma }

On child pages, simply set the `parent:` YAML front matter to whatever the parent's page title is and set a nav order (this number is now scoped within the section).

#### Example

{: .no_toc }

```yaml
---
layout: default
title: Buttons
parent: UI Components
nav_order: 2
---

```

The Buttons page appears as a child of UI Components and appears second in the UI Components section.

### Auto-generating Table of Contents

By default, all pages with children will automatically append a Table of Contents which lists the child pages after the parent page's content. To disable this auto Table of Contents, set `has_toc: false` in the parent page's YAML front matter.

#### Example

{: .no_toc }

```yaml
---
layout: default
title: UI Components
nav_order: 2
has_children: true
has_toc: false
---

```

### Children with children

{: .text-gamma }

Child pages can also have children (grandchildren). This is achieved by using a similar pattern on the child and grandchild pages.

1. Add the `has_children` attribute to the child
1. Add the `parent` and `grand_parent` attribute to the grandchild

#### Example

{: .no_toc }

```yaml
---
layout: default
title: Buttons
parent: UI Components
nav_order: 2
has_children: true
---

```

```yaml
---
layout: default
title: Buttons Child Page
parent: Buttons
grand_parent: UI Components
nav_order: 1
---

```

This would create the following navigation structure:

```
+-- ..
|
|-- UI Components
|   |-- ..
|   |
|   |-- Buttons
|   |   |-- Button Child Page
|   |
|   |-- ..
|
+-- ..
```

---

## Auxiliary Links

To add auxiliary links to your site (in the upper right on all pages), add it to the `aux_links` [configuration option]({{ site.baseurl }}{% link docs/configuration.md %}#aux-links) in your site's `_config.yml` file.

#### Example

{: .no_toc }

```yaml
# Aux links for the upper right navigation
aux_links:
  "Just the Docs on GitHub":
    - "//github.com/just-the-docs/just-the-docs"
```

---

## In-page navigation with Table of Contents

To generate a Table of Contents on your docs pages, you can use the `{:toc}` method from Kramdown, immediately after an `<ol>` in Markdown. This will automatically generate an ordered list of anchor links to various sections of the page based on headings and heading levels. There may be occasions where you're using a heading and you don't want it to show up in the TOC, so to skip a particular heading use the `{: .no_toc }` CSS class.

#### Example

{: .no_toc }

```markdown
# Navigation Structure

{: .no_toc }

## Table of contents

{: .no_toc .text-delta }

1. TOC
   {:toc}
```

This example skips the page name heading (`#`) from the TOC, as well as the heading for the Table of Contents itself (`##`) because it is redundant, followed by the table of contents itself. To get an unordered list, replace `1. TOC` above by `- TOC`.

### Collapsible Table of Contents

The Table of Contents can be made collapsible using the `<details>` and `<summary>` elements , as in the following example. The attribute `open` (expands the Table of Contents by default) and the styling with `{: .text-delta }` are optional.

```markdown
<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>
```

The result is shown at [the top of this page](#navigation-structure) (`{:toc}` can be used only once on each page).
