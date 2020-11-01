from: [Sean C Davis.](https://cobwwweb.com/building-static-api-eleventy)

MAY 06, 2020
# BUILDING A STATIC API WITH ELEVENTY

---

## Step 1: Setup Project

open terminal:

`mkdir 11ty-magingreeenpages-api`

`cd 11ty-magingreeenpages-api`

`npm init -y`

`npm install @11ty/eleventy`

`git init`

`echo "node_modules" > .gitignore`

---

## Step 2: Add Data Files

make:

`_data/companies.json`

package.json

`
"scripts": {
  "dev": "eleventy --serve"
}
`

`npm run dev`
