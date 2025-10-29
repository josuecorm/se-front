This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Challenge

### Description

Build a small React app where the user can type or paste text into a textarea and click a “Count Words” button to display word statistics.

The app should:

- Count and display the **total number of words** in the text.
- Count and display the **number of unique words** (case-insensitive, ignoring punctuation).
- Display the **top 3 most frequent words** along with their counts.

**Example**

**Input**
```
"Hello, hello. How are you? You look great, hello."
```

**Output**:
```
Total words: 9
Unique words: 6
Top 3: hello (3 times), you (2 times), are (1 time)
```

**Constraints**
- Words are **case-insensitive** (“Hello” and “hello” are the same).
- **Ignore punctuation and special characters**.
- Empty input or input with only spaces/punctuation → 0 words.
- Multiple words with the same frequency.

