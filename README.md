# Using [TailwindCSS](https://tailwindcss.com/) with DNN9.8.1

## Run DNN locally

Follow the [Setting Up DNN](https://dnndocs.com/content/tutorials/server/setup/administrators-setup-overview/index.html) section of the doc to:

1. Set up IIS for serving DNN site locally
2. Set up a SQL Server instance
3. Complete the DNN installation

## Add Tailwind to DNN

> These are just FYI. You don't need to do these if you clone this repo.

Install the [DNN_Tailwind module](https://www.dnntailwind.com/).

Installation instructions:

- https://www.dnntailwind.com/Installation.html
- https://github.com/skrantzman/DNN_Tailwind

## Enable DNN theme and apply the theme to pages

The Tailwind DNN theme need to be enabled and apply to individual pages.

## Edit template to get rid of non-tailwind CSS classes

Non-tailwind classes need to be removed in order for Tailwind to work properly.
