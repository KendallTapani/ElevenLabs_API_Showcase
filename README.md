This is a neat little Next.js app I put together while going through the ElevenLabs API docs.

In the docs, people assume this is only a Python-based API, but you can make the HTTP request in any language as long as it’s formatted correctly. I did that it here in TypeScript without any complications. (see screenshot)

The app uses generic Next.js, TypeScript, and Tailwind. The main files to check out are the route.ts and text-to-speech.tsx files, which contain most of the code. The rest is generic rendering and styling.

For some of the more complicated parts in the route.ts file, I added comments explaining what each individual section is doing.

The docs are very easy to follow, and I haven’t encountered any issues after the initial debugging.

Overall, it’s been a pretty good experience, and the end result is quite impressive.

The API key isn’t active; normally, I’d put it in a .env file, but I wanted to show the key in a string to demonstrate what it looks like for anyone curious.
![Screenshot from 2024-11-25 01-10-43](https://github.com/user-attachments/assets/551c488b-759d-4552-a901-3ab626a61d56)
