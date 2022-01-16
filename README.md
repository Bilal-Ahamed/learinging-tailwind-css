# learinging-tailwind-css
1. npm init -y
2. npm install -D tailwindcss postcss autoprefixer vite
3. npx tailwindcss init
4. open tailwind.config.js
module.exports = {
  content: ["*"],
  theme: {
    extend: {},
  },
  plugins: [],
}
5. create input.css and add link in your html
6. copy and paste in input.css
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
7. add start : vite in package.json
    {"name": "tailwind-css",
        "version": "1.0.0",
        "description": "",
        "main": "index.js",
        "scripts": {
        "start": "vite"
    },
8. npm run start
