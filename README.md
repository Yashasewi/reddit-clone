# Breadit - A Modern Fullstack Reddit Clone

Built with the Next.js App Router, TypeScript & Tailwind

## Features

-   Infinite scrolling for dynamically loading posts
-   Authentication using NextAuth & Google
-   Custom feed for authenticated users
-   Advanced caching using [Upstash Redis](https://upstash.com/)
-   Optimistic updates for a great user experience
-   Modern data fetching using React-Query
-   A beautiful and highly functional post editor
-   Image uploads & link previews
-   Full comment functionality with nested replies
-   ... and much more

## Getting started

To get started with this project, run

```bash
  git clone https://github.com/Yashasewi/reddit-clone.git
```

and copy these .env.example variables into a separate .env file:

```bash
DATABASE_URL=
NEXTAUTH_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

REDIS_URL=
REDIS_SECRET=
```

## Acknowledgements

-   [Upstash Redis](https://upstash.com/) for making this possible

## License

[MIT](https://choosealicense.com/licenses/mit/)
