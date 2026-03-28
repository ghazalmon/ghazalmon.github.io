# Ghazal Shabestani Monfared — Personal Website

Personal homepage built with [Astro](https://astro.build) and Tailwind CSS.

## How to edit the website content

All text on the website is stored in **one file**:

**[`src/content/site-content.json`](src/content/site-content.json)**

To update the site:

1. Go to [site-content.json on GitHub](../../blob/main/src/content/site-content.json)
2. Click the **pencil icon** (Edit this file)
3. Change the text you want to update
4. Click **Commit changes** at the bottom
5. The site will automatically rebuild and go live within a couple of minutes

### What you can change

| Section | What to look for in the file |
|---------|------------------------------|
| Top of page | `"hero"` — your name, tagline, intro text |
| About me | `"about"` — paragraphs, languages, interests |
| Work experience | `"experience"` — jobs, roles, bullet points |
| Skills | `"skills"` — skill categories and items |
| Education | `"education"` — schools and degrees |
| Publications | `"publications"` — paper titles |
| Contact | `"contact"` — headline, text, LinkedIn URL |

### Important

- Keep the quotation marks `"` around text
- Keep the commas `,` between items
- Keep the square brackets `[]` around lists
- If you're unsure, copy the file first as a backup before editing

### To update the CV

1. Go to the `public/` folder on GitHub
2. Upload a new PDF named `cv-ghazal-monfared.pdf` (replacing the old one)
