:root {
    /* Neon Editorial Color Palette (Gold-Free) */
    --color-paper: #F7F7F5;
    --color-ink: #0B0B0F;
    --color-soft-gray: #E7E7EA;
    --color-warm-stone: #EFE7E0;
    --color-punch-magenta: #D81AA6;
    --color-blaze-orange: #FF4A1A;
    
    /* Mapped to original variable names for easy replacement */
    --color-primary: var(--color-ink);
    --color-secondary: var(--color-punch-magenta);
    --color-accent: var(--color-blaze-orange);
    --color-bg: var(--color-paper);
    --color-text: var(--color-ink);
    --color-text-light: #5a5a5f;
    --color-white: var(--color-paper);
    
    /* Typography */
    --font-display: 'Bebas Neue', sans-serif;
    --font-heading: 'Space Grotesk', -apple-system, sans-serif;
    --font-body: 'Inter', -apple-system, sans-serif;
    
    --spacing-xs: 0.5rem;
    --spacing-sm: 1rem;
    --spacing-md: 2rem;
    --spacing-lg: 4rem;
    --spacing-xl: 6rem;
    
    --shadow-sm: 0 2px 8px rgba(11,11,15,0.1);
    --shadow-md: 0 4px 16px rgba(11,11,15,0.15);
}

/* Import Google Fonts - Bebas Neue, Space Grotesk, and Inter */
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Space+Grotesk:wght@400;600;700&family=Inter:wght@400;500;600&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: var(--font-body);
    background: var(--color-bg);
    color: var(--color-text);
    line-height: 1.6;
    overflow-x: hidden;
}

/* Navigation */
.main-nav {
    background: var(--color-ink);
    color: var(--color-white);
    padding: 1.5rem 0;
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: var(--shadow-sm);
}

.nav-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-family: var(--font-heading);
    font-size: 0.9rem;
    font-weight: 700;
    letter-spacing: 0.06em;
    line-height: 1.2;
    text-decoration: none;
    color: var(--color-white);
    text-transform: uppercase;
    transition: color 0.3s ease;
}

.logo:hover {
    color: var(--color-punch-magenta);
}

.nav-links {
    display: flex;
    gap: 2rem;
    list-style: none;
}

.nav-links a {
    color: var(--color-white);
    text-decoration: none;
    font-size: 0.95rem;
    font-weight: 600;
    letter-spacing: 0.04em;
    text-transform: uppercase;
    transition: color 0.3s ease;
    position: relative;
}

.nav-links a::after {
    content: '';
    position: absolute;
    bottom: -4px;
    left: 0;
    width: 0;
    height: 2px;
    background: var(--color-punch-magenta);
    transition: width 0.3s ease;
}

.nav-links a:hover {
    color: var(--color-punch-magenta);
}

.nav-links a:hover::after {
    width: 100%;
}

/* Hero Section */
.hero {
    min-height: 85vh;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    padding: var(--spacing-lg) 2rem;
    background: linear-gradient(135deg, var(--color-ink) 0%, #1a1a1f 100%);
    overflow: hidden;
}

.hero-decoration {
    position: absolute;
    top: -50%;
    right: -20%;
    width: 80%;
    height: 150%;
    background: radial-gradient(circle, rgba(216,26,166,0.1) 0%, transparent 70%);
    animation: float 20s ease-in-out infinite;
}

@keyframes float {
    0%, 100% { transform: translate(0, 0) rotate(0deg); }
    25% { transform: translate(-5%, 5%) rotate(2deg); }
    50% { transform: translate(5%, -5%) rotate(-2deg); }
    75% { transform: translate(-5%, -5%) rotate(1deg); }
}

.hero-content {
    max-width: 900px;
    position: relative;
    z-index: 2;
    animation: fadeInUp 1s ease-out;
}

@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.hero-title {
    font-family: var(--font-display);
    font-size: clamp(3.5rem, 10vw, 7rem);
    font-weight: 400;
    color: var(--color-white);
    line-height: 0.95;
    margin-bottom: var(--spacing-sm);
    letter-spacing: 0.02em;
    text-transform: uppercase;
}

.title-line {
    display: block;
    animation: slideIn 0.8s ease-out backwards;
}

.title-line:nth-child(2) {
    animation-delay: 0.2s;
}

.subtitle {
    font-size: clamp(2.5rem, 6vw, 4rem);
    color: var(--color-soft-gray);
}

@keyframes slideIn {
    from {
        opacity: 0;
        transform: translateX(-50px);
    }
    to {
        opacity: 1;
        transform: translateX(0);
    }
}

.hero-subtitle {
    font-family: var(--font-display);
    font-size: clamp(2rem, 5vw, 3.5rem);
    font-weight: 400;
    color: var(--color-punch-magenta);
    line-height: 1;
    margin-bottom: var(--spacing-md);
    animation: fadeInUp 1s ease-out 0.4s backwards;
    text-transform: uppercase;
    letter-spacing: 0.02em;
}

.subtitle-line {
    display: block;
}

.hero-description {
    font-size: clamp(1.1rem, 2vw, 1.3rem);
    color: rgba(247,247,245,0.9);
    max-width: 650px;
    margin-bottom: var(--spacing-md);
    line-height: 1.7;
    animation: fadeInUp 1s ease-out 0.6s backwards;
}

.cta-button {
    display: inline-block;
    background: var(--color-punch-magenta);
    color: var(--color-white);
    padding: 1rem 2.5rem;
    font-size: 1rem;
    font-weight: 700;
    text-decoration: none;
    text-transform: uppercase;
    letter-spacing: 0.06em;
    border: none;
    cursor: pointer;
    transition: all 0.3s ease;
    box-shadow: 0 4px 20px rgba(216,26,166,0.3);
    animation: fadeInUp 1s ease-out 0.8s backwards;
}

.cta-button:hover {
    background: var(--color-blaze-orange);
    transform: translateY(-2px);
    box-shadow: 0 6px 30px rgba(255,74,26,0.4);
}

/* Quick Intro Section */
.quick-intro {
    padding: var(--spacing-xl) 2rem;
    background: var(--color-white);
}

.container {
    max-width: 1200px;
    margin: 0 auto;
}

.intro-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: var(--spacing-md);
}

.intro-card {
    padding: var(--spacing-md);
    background: var(--color-soft-gray);
    border-left: 4px solid var(--color-punch-magenta);
    transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease;
}

.intro-card:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-md);
    border-left-color: var(--color-blaze-orange);
}

.intro-card h3 {
    font-family: var(--font-heading);
    font-size: 1.8rem;
    font-weight: 700;
    color: var(--color-primary);
    margin-bottom: var(--spacing-sm);
    letter-spacing: -0.01em;
}

.intro-card p {
    color: var(--color-text);
    line-height: 1.7;
}

/* Latest Content Section */
.latest-content {
    padding: var(--spacing-xl) 2rem;
    background: var(--color-bg);
}

.section-title {
    font-family: var(--font-display);
    font-size: clamp(3rem, 6vw, 4.5rem);
    font-weight: 400;
    color: var(--color-primary);
    margin-bottom: var(--spacing-lg);
    text-align: center;
    position: relative;
    letter-spacing: 0.02em;
    line-height: 1;
    text-transform: uppercase;
}

.section-title::after {
    content: '';
    display: block;
    width: 100px;
    height: 4px;
    background: var(--color-punch-magenta);
    margin: var(--spacing-sm) auto 0;
}

.content-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: var(--spacing-md);
}

.content-card {
    background: var(--color-white);
    padding: var(--spacing-md);
    border-top: 3px solid var(--color-ink);
    transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease;
}

.content-card:hover {
    transform: translateY(-8px);
    box-shadow: var(--shadow-md);
    border-top-color: var(--color-punch-magenta);
}

.card-label {
    font-family: var(--font-heading);
    font-size: 0.75rem;
    font-weight: 700;
    color: var(--color-blaze-orange);
    text-transform: uppercase;
    letter-spacing: 0.08em;
    display: block;
    margin-bottom: var(--spacing-xs);
}

.content-card h3 {
    font-family: var(--font-heading);
    font-size: 1.6rem;
    font-weight: 700;
    color: var(--color-primary);
    margin-bottom: var(--spacing-sm);
    line-height: 1.2;
    letter-spacing: -0.01em;
}

.content-card p {
    color: var(--color-text);
    margin-bottom: var(--spacing-sm);
    line-height: 1.7;
}

.read-more {
    display: inline-block;
    color: var(--color-punch-magenta);
    font-weight: 600;
    text-decoration: none;
    text-transform: uppercase;
    letter-spacing: 0.04em;
    font-size: 0.9rem;
    transition: transform 0.3s ease, color 0.3s ease;
}

.read-more:hover {
    transform: translateX(5px);
    color: var(--color-blaze-orange);
}

/* Footer */
.main-footer {
    background: var(--color-ink);
    color: var(--color-white);
    padding: var(--spacing-lg) 2rem var(--spacing-md);
}

.footer-content {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: var(--spacing-md);
    flex-wrap: wrap;
    gap: var(--spacing-md);
}

.footer-logo {
    font-family: var(--font-heading);
    font-size: 1.2rem;
    font-weight: 700;
    letter-spacing: 0.06em;
    margin-bottom: var(--spacing-xs);
    text-transform: uppercase;
}

.footer-tagline {
    color: rgba(247,247,245,0.7);
    font-size: 0.9rem;
}

.footer-links {
    display: flex;
    gap: var(--spacing-md);
    flex-wrap: wrap;
}

.footer-links a {
    color: var(--color-white);
    text-decoration: none;
    font-size: 0.9rem;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 0.04em;
    transition: color 0.3s ease;
}

.footer-links a:hover {
    color: var(--color-punch-magenta);
}

.footer-bottom {
    text-align: center;
    padding-top: var(--spacing-md);
    border-top: 1px solid rgba(247,247,245,0.1);
}

.footer-bottom p {
    color: rgba(247,247,245,0.6);
    font-size: 0.85rem;
}

/* Responsive Design */
@media (max-width: 768px) {
    .nav-container {
        flex-direction: column;
        gap: 1rem;
    }
    
    .nav-links {
        gap: 1rem;
    }
    
    .hero {
        min-height: 70vh;
        padding: var(--spacing-md) 1.5rem;
    }
    
    .intro-grid,
    .content-grid {
        grid-template-columns: 1fr;
    }
    
    .footer-content {
        flex-direction: column;
        text-align: center;
    }
    
    .footer-links {
        justify-content: center;
    }
}
