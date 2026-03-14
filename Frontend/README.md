- to fix tailwind version mismatch with vite 8:
- use in package.json :
```"overrides": {
    "@tailwindcss/vite": {
      "vite": "$vite"
    }
  }```