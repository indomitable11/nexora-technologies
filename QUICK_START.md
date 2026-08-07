# Nexora Technologies - Local Setup Guide

## Quick Start

### 1. Make sure you're in the correct folder:

```powershell
cd C:\Users\USER\nexora-technologies
```

### 2. Install dependencies:

```powershell
npm install --legacy-peer-deps
```

**Wait for this to complete** (2-5 minutes). You should see:
```
added XXX packages
```

### 3. Create environment file:

```powershell
copy .env.example .env.local
```

### 4. Run development server:

```powershell
npm run dev
```

### 5. Open in browser:

```
http://localhost:3000
```

---

## Troubleshooting

### Error: "npm: The term 'npm' is not recognized"

**Solution:**
1. Make sure Node.js is installed: Download from https://nodejs.org/
2. Restart your terminal/PowerShell
3. Try again

### Error: "ERESOLVE unable to resolve dependency tree"

**Solution:**
```powershell
npm install --legacy-peer-deps
```

### Error: "'next' is not recognized"

**Solution:**
```powershell
npm install --legacy-peer-deps
```

Then try again:
```powershell
npm run dev
```

---

## Commands Reference

| Command | What it does |
|---------|-------------|
| `npm install --legacy-peer-deps` | Installs all dependencies |
| `npm run dev` | Starts development server |
| `npm run build` | Creates production build |
| `npm run start` | Starts production server |
| `npm run lint` | Checks code quality |

---

## If you have errors:

1. **Delete node_modules:**
   ```powershell
   rmdir /s node_modules
   ```

2. **Delete package-lock.json:**
   ```powershell
   del package-lock.json
   ```

3. **Install again:**
   ```powershell
   npm install --legacy-peer-deps
   ```

4. **Run dev:**
   ```powershell
   npm run dev
   ```

---

## Need Help?

Contact Nexora Technologies:
- **Email**: marvieindomitable63@gmail.com
- **Phone**: +234 814 917 9696
- **WhatsApp**: +234 814 917 9696
