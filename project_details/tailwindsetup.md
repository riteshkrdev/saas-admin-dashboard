npm install tailwindcss @tailwindcss/vite

vite.config.js file:
import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'

export default defineConfig({
  plugins: [
    tailwindcss(), ==> import this
  ],
})


@import "tailwindcss";  ==> index.css global styles