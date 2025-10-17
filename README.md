# Solana Blink - Tip Jar

Deploy your own tip jar Blink in 60 seconds!

## 🚀 Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/jordan-m-finn/solana-blink-tip-jar)

## ✏️ Customize Your Blink

After deploying, edit `pages/api/actions/tip.ts`:

### 1. Change Your Wallet Address
```typescript
const RECIPIENT_ADDRESS = "YOUR_WALLET_ADDRESS_HERE";
```
Replace with your Phantom wallet address.

### 2. Update Tip Amounts
```typescript
const TIP_AMOUNTS = [0.1, 0.5, 1.0];
```
Change to any amounts you want (in SOL).

### 3. Customize Text
```typescript
const TITLE = "☕ Tip Me!";
const DESCRIPTION = "Support my work with SOL";
```

### 4. Change Image (Optional)
```typescript
const IMAGE_URL = "https://your-image-url.com/image.png";
```
Upload to [imgur.com](https://imgur.com) and paste URL.

## 🧪 Test Your Blink

Your Blink URL: `https://your-project.vercel.app/api/actions/tip`

Test at: https://actions.dialect.to

## 🛠️ How to Edit

1. Go to your GitHub repo (Vercel creates this automatically)
2. Click `pages/api/actions/tip.ts`
3. Click pencil icon to edit
4. Make changes
5. Commit - Vercel redeploys automatically!

## 📚 Resources

- [Solana Actions Docs](https://solana.com/docs/advanced/actions)

---

Built at UCI Blockchain Club Workshop
