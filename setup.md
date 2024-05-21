## hot to setup Tailwind Css

step-1 Run the followng commands

npm install -D tailwindcss
npx tailwindcss init

step-2 update tailwind.conf.js file to include this line:
content: ["*.html"],

step-3 create src/input.css to include

@tailwind base;
@tailwind components;
@tailwind utilities;

step-4: include the src/output.css file to html

step-5 run the following command

npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
