npm install -D tailwindcss@3 postcss autoprefixer
npx tailwindcss init -p

npm create vite@latest my-project -- --template react
cd my-project

/ @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src//*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
