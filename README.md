    Last updated on: 31st August 2023

<div align=center>
    <a href="https://promptopia-iota-orcin.vercel.app/">
        <img width="702" src="https://github.com/calvinseptyanto/promptopia/assets/98633109/5c3f5517-5758-4bc9-8afe-c9617f4a4b97" alt="Nike">
    </a>

</div>

# [Promptopia: AI-Powered Prompts](https://promptopia-iota-orcin.vercel.app/)

![line]

## Table of Contents

- [Introduction](#introduction)
- [Development](#development)
- [Tech Stack Used](#tech-stack-used)
- [API Endpoints](#api-endpoints)
- [Preview](#preview)
- [License](#license)

![line]

## Introduction

- 🌐 **Discover, Create, and Share Creative Prompts** 🌐
  <br/>
  With Promptopia, the possibilities are endless. Whether you're an artist, writer, designer, or simply someone looking to ignite their creativity, our platform is your ultimate source for inspiration. Create prompts that challenge the status quo, explore new horizons, and spark innovation.
  
- 🔍 **Seamless Search Functionality** 🔍
  <br/>
  Finding the perfect prompt has never been easier. Our search feature allows you to explore prompts and profiles, connecting with like-minded individuals who share your passion and vision. It's a hub for collaboration and networking that transcends borders and boundaries.

- 🧑‍🤝‍🧑 **Personalized Profiles** 🧑‍🤝‍🧑
  <br/>
  Your journey on Promptopia is unique, and your profile reflects that. Showcase your creative portfolio, track your prompt deployments, and let the world discover your creative genius. Connect with fellow creators and build lasting connections that fuel your imagination.
  
- 📢 **Share Your Prompts with the World** 📢
  <br/>
  Promptopia isn't just a platform; it's a community. Share your prompts, collaborate on projects, and witness your ideas come to life. Join a global network of creators and be part of the creative revolution.

![line]

## Development

```sh
> npm install
> npm run dev
```

![line]

## Tech Stack Used

- Next.js: Framework
- TailwindCSS: Styling
- MongoDB: Database
- Google Auth 2.0: Authentication
- Git & Github: Version Control
- Vercel: Hosting

![Next.js](https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=blue) ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white) ![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Vercel](https://img.shields.io/badge/vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

![line]

## API Endpoints

- POST /api/prompt/new : Create new prompt.
- GET /api/users/${session.user.id}/posts: Get all posts for the user.
- GET /api/users/${params?.id}/posts: Get all posts of the user on the user`s profile.
- GET /api/prompt/${promptId} Get prompt.
- PATCH /api/prompt/${promptId} Update prompt.
- GET /api/prompts/${project}/prompts Get all prompts.
- DELETE /api/prompt/${post._id.toString()} Delete prompt.

![line]

## Preview

![](https://github.com/calvinseptyanto/promptopia/assets/98633109/b508def5-904e-45aa-8b44-78f9f3ec5c56)

![line]

## License

- See [LICENSE]

**Calvin Septyanto**

[line]: https://user-images.githubusercontent.com/75939390/137615281-3a875960-92cc-407f-97fe-fd2319bdb252.png
[License]: https://github.com/calvinseptyanto/nike-landing-page/blob/main/LICENSE
[badges]: https://github.com/Ileriayo/markdown-badges

