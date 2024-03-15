If you open this project in VS code and download the suggested extensions and run `pnpm i`, when you save `apps/web/src/routes/+page.svelte`, it will shuffle the order of the tailwindcss classes to `mr-1 mt-1`.

However, if you run `prettier --write .` in the root of the project, it will format the file and the tailwindcss classes will be in the correct order `mt-1 mr-1`.
