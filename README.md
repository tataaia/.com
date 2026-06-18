# TATA AIA Life Insurance - Interactive Home Page

Welcome to the interactive and storytelling homepage of **TATA AIA Life Insurance**. This project is designed to present core insurance values, legacy trust, safety shields, and policy details in an immersive, non-congested scroll-triggered format.

Using modern web design methodologies, this portal ensures users learn why financial protection is essential and how they can secure their family's future.

## ✨ Key Features

*   **Interactive On-Scroll SVG Filters**: Visual mask transitions powered by GSAP's `ScrollTrigger` and `Flip` to reveal premium section graphics.
*   **Floating Glassmorphic Header**: A sticky, modern header styled with a backdrop blur filter for clean floating navigation.
*   **Highly Readable Typography**: Styled with responsive font-size clamps and sentence-case paragraphs to prevent overlapping and ensure smooth readability across screen sizes.
*   **Visual Hover Interactions**: Resources cards lift on hover (`translateY`) with smooth image zoom-scaling and red/coral shadows to highlight selections.
*   **Robust Loader Fallback**: Custom font preloader fallback logic to prevent black-screen hangs if remote CDNs are slow.

## 📁 Content Structure

1.  **Protecting Dreams (Hero Section)**: Dynamic landing screen with TATA AIA branding.
2.  **Legacy & Trust**: Highlighting the legacy of the Tata Group combined with AIA's global strength.
3.  **Shield & Family**: Emotional representation of family security.
4.  **Maha & Raksha**: Explaining the term life protection plan.
5.  **Wealth & Grow**: Showcasing savings and market-linked investment growth.
6.  **Global & Insight**: Stat-based insights about the under-insurance gap.
7.  **Peace & Mind**: Inspirational quote of security.
8.  **Secure & Today**: Strong call to action.
9.  **Helpful Resources**: Links to Wikipedia records, risk articles, and Buffett quotes.

## 🚀 Running Locally

To run this project locally, simply start a development server in the root directory:

**Using Python:**
```bash
python -m http.server 8000
```

**Using Node.js (http-server):**
```bash
npx http-server -p 8000
```

Once running, navigate to `http://localhost:8000` in your browser.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
