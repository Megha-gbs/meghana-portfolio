# Meghana Guthi | Portfolio

A static site (plain HTML, CSS, JS). No build step, so Vercel serves it as-is.

## Files
- `index.html`: the whole site
- `Meghana_Guthi_Resume.pdf`: the file behind the "Download resume" button (replace it to update your resume, keep the same filename)
- `vercel.json`: Vercel settings

## Deploy to Vercel (about 3 minutes)
1. Create a new GitHub repository (for example `portfolio`) and upload these files to it.
2. Go to vercel.com, sign in with GitHub, click Add New, then Project, and import that repository.
3. Framework Preset: choose **Other**. Leave Build Command and Output Directory empty.
4. Click Deploy. You will get a link like `https://portfolio-yourname.vercel.app`.

Put that link in the Portfolio URL field on your Devnovate profile.

## Deploy from the command line instead
```
npm i -g vercel
cd this-folder
vercel --prod
```

## Adding a project
Copy one `<article class="proj">` block in `index.html`, change the text, the GitHub link, and `data-cat`
(`hackathon`, `ai`, `cloud`, or `java`) so the filter tabs pick it up.
