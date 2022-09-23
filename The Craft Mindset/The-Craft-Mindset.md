<h1>The Craft Mindset</h1>

<h2>Picturing Craft</h2>
>Typical Site
>  -  **Boxes of content** (Sections) that define and store our data/content
>    - devoid of seperators, forlders, and organization
>  - **Content Types** boxes broken down into pieces - blog posts, emp profile, etc
>    - Made with Fields and Field Types
>      - allow even further breakdown (modeling content so it fits in software)
>      - Content is inputted into the fields and saved in the system
>  - **Output** (Templates) Where we put out content to people can read/use it
>    - Template used to output the requested Entry (web page)

<h2>Pieces of Craft</h2>
<h3>1. Sections</h2>
- Big boxes where you store your content
  - (news articles, set of docs, website pages)
  - 3 types of sections in Craft
    - Channel 
      - A collection of Related Content
      - Blog Posts, News Articles, staff listing
    - Structure
      - Hierarchical collection of content
      - Product Docs, Instruction Manuel, Website Pages
    - Single
      - one-off pages
      - no sibling content
      - Home & Landing Pages
      - Allowed only one entry type, one field layout, {# entry. #}

>Think: How do we represent boxes of content as Craft Sections?

<h3>2.Fields and Field Types</h3>

- **Fields** - Organizes content into smaller pieces
- **Field Types** - Define what kind of content you can store
  - <a href="https://craftcms.com/docs/3.x/fields.html#field-types">Check documentation</a> for all field types
  - Third Party field types available but *require upkeep*
>- Illustration of Field Types
>  - Example Fields and Field Types for content type "News Article"
>    - Headline - Title Field
>    - Article Excerpt - Plain Text Field
>    - Article Image - Assets Field
>    - Article Image Caption - Plain Text Field
>    - Article Body Copy - Rich Text Field (redactor)

<h3>3. Entries</h3>

- *Content Inputted into Sections using Fields*
- Each piece of content is stored as an **Entry**
- Typically, we display content in template at the entry level
> - Displaying Entries
>   - **Listing** - Set of entries with links to single entry (ex. Blogs.php)
>   - **Single Entry** - The full entry at a unique url (ex. Blog-Single.php)

<h3>4. Templates</h3>

- Outputs Content and HTML Markup
- *Not Complete HTML Documents*
  - Missing content (!= Finished Page)
- *Twig tags pull **Content** as **Entries** from **Sections** which we can then output via **Fields** in our **Templates***

<h3>The Crafting Process</h3>
- Review the website content
- Define content as Sections, Fields, and Field Types
- Enter sample content to test Sections and Fields
- Surface the content via Fields in Templates
