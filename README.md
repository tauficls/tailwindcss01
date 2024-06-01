# tailwindcss01
it's a mini project learning about styling css using tailwindcss. Tailwindcss is a CSS framework packed with classes such as grid-col-2, place-center-content, items-center, pt-2, font-bold etc and you can write those classes directly in your HTML. It's a powerful tools that let you to develop fast, flexible and reliable. 

For installation you can you this link to the [tailwindcss website](https://tailwindcss.com)

to run tailwindcss you need [Node.js](https://nodejs.org/) and run this commandline

```sh
npx tailwindcss init
```

1. Edit the file config tailwind.config.js by adding all paths to your template files.
2. Add the Tailwind directives to your CSS
3. Build your css by running CLI to scan the tailwind templates and classes. "Watch" options will check the changes of tailwindcss input.
```sh
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

4. You can start right away by editting html templates

I learned the tailwindcss step by step from youtube tutorial. Credits to [Dave Grey](https://www.youtube.com/@DaveGrayTeachesCode)

