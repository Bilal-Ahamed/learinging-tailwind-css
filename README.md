# learinging-tailwind-css
1. npm install -D tailwindcss postcss autoprefixer
2. npx tailwindcss init
3. npm install vite

4. go to tailwind.config.js file and write
module.exports = {
  content: ["*"],
  theme: {
    extend: {},
  },
  plugins: [],
}


5. go to package.json file and write
{
  "scripts": {
    "start": "vite"
  },
  "devDependencies": {
    "autoprefixer": "^10.4.2",
    "postcss": "^8.4.5",
    "tailwindcss": "^3.0.15"
  },
  "dependencies": {
    "vite": "^2.7.12"
  }
}

6. install tailwind intellisence extension
