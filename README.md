<div align="center">

  <h1 align="center">
        Mojai  
    </h1>
    <p align="center"> 
        <i><b>AI-generated emojis.</b></i>
        <br /> 
    </p>

[![Website][website]][website-url]
[![Github][github]][github-url]


<img src="https://res.cloudinary.com/dnz16usmk/image/upload/f_auto,q_auto/v1/vd7-website/mojai"   />





 </div>

<br/>

## Table of Contents

  <ol>
    <a href="#about">📝 About</a><br/>
    <a href="#how-i-built">💻 How I Built</a><br/>
    <a href="#tools-used">🔧 Tools Used</a>
        <ul>
        </ul>
    <a href="#contact">👤 Contact</a>
  </ol>

<br/>

## 📝About

- Create an avatar emoji of anyone or anything, real or fictional.
- Powered by AI and your creativity.
- Type a description (comma-separated) and download a masterpiece in 5-10 seconds.

  

## 💻How I Built

- Fine-tuned SDXL (Stable Diffusion XL) model
- Datasets sourced from:
  - iOS emojis
  - Wii / Mii avatars
  - a few dozen photorealistic video games (GTA, etc.)
- Inference and LoRA training via HuggingFace
  - Remote endpoint powered by A100 GPU
- Ngrok for webhook and CDN via Cloudinary
- Planetscale / Prisma for image metadata on backend
- Frontend NextJs app hosted on Vercel


## 🔧Tools Used

[![LoRA][LoRA]][LoRA-url]
[![HuggingFace][huggingface]][huggingface-url]
[![Next][next]][next-url]
[![Vercel][vercel]][vercel-url]
[![Ngrok][Ngrok]][Ngrok-url]
[![Planetscale][Planetscale]][Planetscale-url]
[![Prisma][Prisma]][Prisma-url]
[![Cloudinary][Cloudinary]][Cloudinary-url]



## 👤Contact

[![Email][email]][email-url]
[![Twitter][twitter]][twitter-url]

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[next]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[next-url]: https://nextjs.org/
[tailwindcss]: https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=skyblue&color=0A192F
[tailwindcss-url]: https://tailwindcss.com/
[openai]: https://img.shields.io/badge/OpenAI_GPT--3.5--turbo-0058A0?style=for-the-badge&logo=openai&logoColor=white&color=4aa481
[openai-url]: https://openai.com/
[vercel]: https://img.shields.io/badge/Vercel-FFFFFF?style=for-the-badge&logo=Vercel&logoColor=white&color=black
[vercel-url]: https://Vercel.com/
[LoRA]: https://img.shields.io/badge/LoRA-FFFFFF?style=for-the-badge&color=black
[LoRA-url]: #
[huggingface]: https://img.shields.io/badge/🤗Hugging_Face-FFFFFF?style=for-the-badge&logo=huggingface&color=black
[huggingface-url]: https://huggingface.co/
[Ngrok]: https://img.shields.io/badge/Ngrok-FFFFFF?style=for-the-badge&color=blue
[Ngrok-url]: https://ngrok.com/
[Planetscale]: https://img.shields.io/badge/Planetscale-FFFFFF?style=for-the-badge&color=purple
[Planetscale-url]: https://planetscale.com/
[Prisma]: https://img.shields.io/badge/Prisma-FFFFFF?style=for-the-badge&color=lavender
[Prisma-url]: https://www.prisma.io/
[Cloudinary]: https://img.shields.io/badge/Cloudinary-FFFFFF?style=for-the-badge&color=indigo
[Cloudinary-url]: https://cloudinary.com/
[website]: https://img.shields.io/badge/🔗Website-7f18ff?style=for-the-badge
[website-url]: https://mojai.vercel.app
[github]: https://img.shields.io/badge/💻Github-000000?style=for-the-badge
[github-url]: https://github.com/vdutts7/avamoji/
[email]: https://img.shields.io/badge/me@vd7.io-FFCA28?style=for-the-badge&logo=Gmail&logoColor=00bbff&color=black
[email-url]: #
[twitter]: https://img.shields.io/badge/Twitter-FFCA28?style=for-the-badge&logo=Twitter&logoColor=00bbff&color=black
[twitter-url]: https://twitter.com/vdutts7/
