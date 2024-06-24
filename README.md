# Next Auth v5 - Advanced Guide (2024)

Key Features:
- 🔐 Next-auth v5 (Auth.js)
- 🚀 Next.js 14 with server actions
- 🔑 Credentials Provider
- 🌐 OAuth Provider (Social login with Google & GitHub)
- 🔒 Forgot password functionality
- ✉️ Email verification
- 📱 Two factor verification
- 🔓 Login component (Opens in redirect or modal)
- 📝 Register component
- 🤔 Forgot password component
- ✅ Verification component
- ⚠️ Error component
- 🔘 Login button
- 🚪 Logout button
- 🚧 Role Gate
- 🔍 Exploring next.js middleware
- 📈 Extending & Exploring next-auth session

### Install packages

```shell
npm i
```

### Setup .env file


```js

GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=
AUTH_SECRET=


GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=


DATABASE_URL=

```

### Setup Prisma
```shell
npx prisma generate
npx prisma db push
```

### Start the app

```shell
npm run dev
```