# Ecommerce Admin

Next.js로 만드는 풀스택 E-commerce

## 추가 패키지

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=Next.js&logoColor=white"/>
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=Prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=flat-square&logo=Tailwind CSS&logoColor=white"/>

```bash
npx shadcn-ui@latest init
npm install @clerk/nextjs
```

- planetscale

## .env

프로젝트에서 필요한 몇가지 설정정보를 가진 `.env`는 비공개 처리 하였습니다.
대신 어떤 항목이 필요한지 정리하겠습니다.

- `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY`
- `CLERK_SECRET_KEY`

- `NEXT_PUBLIC_CLERK_SIGN_IN_URL`
- `NEXT_PUBLIC_CLERK_SIGN_UP_URL`
- `NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL`
- `NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL`

위 6가지 정보는 [clerk](https://clerk.com/) 프로젝트의 API Key와 [clerk doc](https://clerk.com/docs/nextjs/get-started-with-nextjs)에서 확인할 수 있습니다.

- `DATABASE_URL`

Prisma에서 사용할 Database URL입니다. 저는 [planetscale](https://app.planetscale.com/)에서 데이터베이스를 생성해 사용했습니다.
