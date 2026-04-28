# VSNEXOS GST Calculator

A modern, professional GST Calculator web application for India built with Next.js, React, TypeScript, and Tailwind CSS.

## Features

### Core Features
- ✅ GST Exclusive Calculation
- ✅ GST Inclusive Calculation
- ✅ Quick GST Slab Buttons (0%, 3%, 5%, 12%, 18%, 28%)
- ✅ Custom GST Rate Input
- ✅ Real-Time Auto Calculation
- ✅ CGST + SGST Split (Intra-State)
- ✅ IGST Full (Inter-State)
- ✅ Indian Currency Formatting (₹1,25,000)

### Advanced Features
- ✅ Copy Result to Clipboard
- ✅ Download PDF Result
- ✅ Download TXT Result
- ✅ Share Result via Link
- ✅ Multi-Item GST Calculator
- ✅ GST Invoice Preview
- ✅ Reset Button

### SEO & Content
- ✅ GST Knowledge Section
- ✅ FAQ Section with Schema Markup
- ✅ GST Slabs Information
- ✅ Calculation Formulas
- ✅ Open Graph & Twitter Cards
- ✅ Structured Data (JSON-LD)

### UI/UX
- ✅ Mobile-First Responsive Design
- ✅ Glassmorphism Cards
- ✅ Smooth Framer Motion Animations
- ✅ Professional Finance Look
- ✅ Sleek Modern UI
- ✅ Fast Loading

## Tech Stack

- **Framework:** Next.js 16 (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS v4
- **Animations:** Framer Motion
- **Icons:** Lucide React
- **PDF Generation:** jsPDF
- **Font:** Inter (next/font)

## Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd gst-calculator
```

2. Install dependencies
```bash
npm install
```

3. Run development server
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Build for Production

```bash
npm run build
```

The static files will be in the `out` directory, ready for deployment.

## Deployment

### Vercel (Recommended)
```bash
vercel deploy
```

### Netlify
```bash
npm run build
netlify deploy --prod --dir=out
```

### GitHub Pages
1. Build the project: `npm run build`
2. Push the `out` directory to your gh-pages branch
3. Configure GitHub Pages in repository settings

## Project Structure

```
gst-calculator/
├── app/                      # Next.js App Router
│   ├── layout.tsx           # Root layout with SEO
│   ├── page.tsx             # Main page
│   ├── loading.tsx          # Loading state
│   ├── not-found.tsx        # 404 page
│   └── globals.css          # Global styles
├── components/              # React components
│   ├── Header.tsx
│   ├── Hero.tsx
│   ├── CalculatorCard.tsx
│   ├── ResultPanel.tsx
│   ├── MultiItemCalculator.tsx
│   ├── GSTGuide.tsx
│   ├── FAQ.tsx
│   └── Footer.tsx
├── hooks/                   # Custom React hooks
│   ├── useGSTCalculator.ts
│   ├── useAnimatedCounter.ts
│   └── useMultiItem.ts
└── utils/                   # Utility functions
    ├── gst-calculations.ts
    └── validation.ts
```

## GST Formulas

### GST Exclusive (Add Tax)
```
GST Amount = (Original Cost × GST Rate) / 100
Total Price = Original Cost + GST Amount
```

### GST Inclusive (Extract Tax)
```
Original Cost = Total Price × [100 / (100 + GST Rate)]
GST Amount = Total Price - Original Cost
```

## Color Palette

- **Primary:** #0F172A (Dark slate)
- **Accent:** #2563EB (Blue)
- **Success:** #16A34A (Green)
- **Glow:** #38BDF8 (Light blue)
- **Background:** #F8FAFC (Light gray)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- ⚡ Lightning fast load time
- 📦 Static optimized
- 🎯 Code split
- 🖼️ Images optimized
- 📊 Lighthouse score: 95+

## Security

- ✅ Input sanitization
- ✅ Number validation
- ✅ XSS prevention
- ✅ Secure headers configured
- ✅ No unsafe scripts

## License

MIT License - feel free to use this project for personal or commercial purposes.

## Credits

**Developed by VSNEXOS**

- Website: https://vsnexos.com
- Email: contact@vsnexos.com

## Support

For issues, questions, or suggestions, please create an issue in the repository.

---

© 2026 VSNEXOS. All rights reserved.
"# gst-calculator" 
