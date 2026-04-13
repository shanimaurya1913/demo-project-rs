# 🚀 Project Name

This is a Next.js application built using modern React features.

---

## 📦 Clone the Repository

```bash
git clone https://github.com/shanimaurya1913/demo-project-rs
cd demo-project-rs
```

---

## 📥 Install Dependencies

Using npm:

```bash
npm install
```

Using yarn:

```bash
yarn
```

Using pnpm:

```bash
pnpm install
```

---

## 🌐 Environment Variables

Create a local environment file from the example:

```bash
cp .env.example .env.local
```

Update the values inside `.env.local`:

```env
NEXT_PUBLIC_API_URL=http://localhost:3000/api
```

### ⚠️ Notes

- Do NOT commit `.env.local` to version control
- Variables starting with `NEXT_PUBLIC_` are exposed to the browser
- Keep sensitive keys private

---

## 🧑‍💻 Run Development Server

```bash
npm run dev
```

Open your browser and visit:

```
http://localhost:3000
```

---

## 🏗️ Build for Production

```bash
npm run build
```

---

## ▶️ Run Production Server

```bash
npm start
```

---

## 📁 Project Structure

```
.
├── app/            # App Router (pages & layouts)
├── public/         # Static assets
├── styles/         # Global styles
├── next.config.js  # Next.js configuration
```

---

## ⚙️ Tech Stack

- Next.js
- React
- TypeScript

---

## 🧪 Linting

```bash
npm run lint
```
