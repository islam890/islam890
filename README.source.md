```aura width=860 height=260 link="https://github.com/islam890"
<div style={{ display: 'flex', width: '100%', height: '100%', fontFamily: 'Inter, sans-serif', position: 'relative', overflow: 'hidden', background: '#08080C', borderRadius: 18, padding: 32, border: '1px solid rgba(249,115,22,0.25)' }}>
  <svg width="860" height="260" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="heroGlow1"><stop offset="0%" stopColor="rgba(249,115,22,0.62)" /><stop offset="72%" stopColor="rgba(249,115,22,0)" /></radialGradient>
      <radialGradient id="heroGlow2"><stop offset="0%" stopColor="rgba(255,122,0,0.40)" /><stop offset="72%" stopColor="rgba(255,122,0,0)" /></radialGradient>
      <radialGradient id="heroGlow3"><stop offset="0%" stopColor="rgba(251,146,60,0.28)" /><stop offset="74%" stopColor="rgba(251,146,60,0)" /></radialGradient>
      <linearGradient id="heroBorder" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stopColor="#F97316" />
        <stop offset="50%" stopColor="#FF7A00" />
        <stop offset="100%" stopColor="#FB923C" />
        <animateTransform attributeName="gradientTransform" type="rotate" from="0 0.5 0.5" to="360 0.5 0.5" dur="10s" repeatCount="indefinite" />
      </linearGradient>
    </defs>

    <ellipse cx="132" cy="30" rx="148" ry="88" fill="url(#heroGlow3)" opacity="0.45">
      <animate attributeName="opacity" values="0.25;0.58;0.25" dur="6s" repeatCount="indefinite" />
      <animate attributeName="cx" values="115;165;115" dur="9s" repeatCount="indefinite" />
    </ellipse>

    <ellipse cx="360" cy="248" rx="246" ry="130" fill="url(#heroGlow1)" opacity="0.85">
      <animate attributeName="cx" values="300;460;300" dur="10s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.55;0.95;0.55" dur="7s" repeatCount="indefinite" />
    </ellipse>

    <ellipse cx="718" cy="182" rx="190" ry="126" fill="url(#heroGlow2)" opacity="0.65">
      <animate attributeName="rx" values="160;220;160" dur="8s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.35;0.75;0.35" dur="6s" repeatCount="indefinite" />
    </ellipse>

    <circle cx="92" cy="82" r="3" fill="#F97316" opacity="0.35">
      <animate attributeName="cy" values="82;62;82" dur="5s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.15;0.55;0.15" dur="5s" repeatCount="indefinite" />
    </circle>

    <circle cx="640" cy="48" r="4" fill="#FF7A00" opacity="0.32">
      <animate attributeName="cx" values="640;690;640" dur="7s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.12;0.5;0.12" dur="7s" repeatCount="indefinite" />
    </circle>

    <circle cx="790" cy="205" r="3" fill="#FB923C" opacity="0.28">
      <animate attributeName="r" values="2;5;2" dur="4.5s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.1;0.45;0.1" dur="4.5s" repeatCount="indefinite" />
    </circle>

    <circle cx="420" cy="38" r="2.5" fill="#FF7A00" opacity="0.35">
      <animate attributeName="opacity" values="0.1;0.6;0.1" dur="5s" repeatCount="indefinite" />
      <animate attributeName="r" values="2;4;2" dur="5s" repeatCount="indefinite" />
    </circle>

    <path d="M-160 225 C 80 170, 220 260, 470 205 S 720 170, 1010 220" stroke="rgba(255,122,0,0.22)" strokeWidth="2" fill="none">
      <animateTransform attributeName="transform" type="translate" values="-120 0;120 0;-120 0" dur="9s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.08;0.32;0.08" dur="9s" repeatCount="indefinite" />
    </path>

    <path d="M-220 55 L 1080 55" stroke="rgba(251,146,60,0.16)" strokeWidth="1.4" fill="none">
      <animateTransform attributeName="transform" type="translate" values="-260 0;260 0;-260 0" dur="11s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0;0.35;0" dur="11s" repeatCount="indefinite" />
    </path>

    <rect x="1" y="1" width="858" height="258" rx="18" fill="none" stroke="url(#heroBorder)" strokeWidth="1.4" />
  </svg>

  <div style={{ display: 'flex', width: '100%', height: '100%', position: 'relative', alignItems: 'center', gap: 22 }}>
    <div style={{ display: 'flex', flexDirection: 'column', justifyContent: 'center', width: 558 }}>
      <div style={{ display: 'flex', gap: 10, marginBottom: 16 }}>
        <span style={{ fontSize: 12, fontWeight: 800, color: '#F97316', border: '1px solid rgba(249,115,22,0.42)', borderRadius: 999, padding: '8px 14px', background: 'rgba(249,115,22,0.10)' }}>Available for Work</span>
        <span style={{ fontSize: 12, fontWeight: 800, color: '#FB923C', border: '1px solid rgba(251,146,60,0.30)', borderRadius: 999, padding: '8px 14px', background: 'rgba(251,146,60,0.08)' }}>Open to Opportunities</span>
      </div>

      <span style={{ fontSize: 42, fontWeight: 900, color: '#FFFFFF', letterSpacing: -1.55, lineHeight: 0.98 }}>Ahmed Islam Adrouche</span>
      <span style={{ fontSize: 22, fontWeight: 900, color: '#FB923C', marginTop: 8, lineHeight: 1.05 }}>Full-Stack Developer</span>
      <span style={{ fontSize: 15, color: '#A1A1AA', marginTop: 12, width: 525, lineHeight: 1.5 }}>Software Engineering Graduate building modern web, mobile, AI-powered and scalable applications.</span>

      <div style={{ display: 'flex', gap: 9, marginTop: 16, flexWrap: 'wrap' }}>
        {['Web Development', 'Desktop Software', 'Mobile Applications', 'AI Solutions'].map((item) => (
          <span style={{ fontSize: 12, color: '#FFFFFF', padding: '7px 12px', borderRadius: 999, background: 'rgba(255,255,255,0.06)', border: '1px solid rgba(255,255,255,0.08)' }}>{item}</span>
        ))}
      </div>
    </div>

    <div style={{ display: 'flex', flexDirection: 'column', gap: 12, justifyContent: 'center', marginLeft: 'auto', width: 228 }}>
      <div style={{ display: 'flex', flexDirection: 'column', justifyContent: 'center', minHeight: 88, padding: 18, borderRadius: 16, background: '#111111', border: '1px solid rgba(249,115,22,0.20)' }}>
        <span style={{ fontSize: 11, color: '#A1A1AA', textTransform: 'uppercase', letterSpacing: 1.1 }}>Focus</span>
        <span style={{ fontSize: 18, fontWeight: 900, color: '#FFFFFF', marginTop: 7, lineHeight: 1.1 }}>Web • Desktop • Mobile • AI</span>
      </div>
      <div style={{ display: 'flex', flexDirection: 'column', justifyContent: 'center', minHeight: 88, padding: 18, borderRadius: 16, background: '#111111', border: '1px solid rgba(249,115,22,0.20)' }}>
        <span style={{ fontSize: 11, color: '#A1A1AA', textTransform: 'uppercase', letterSpacing: 1.1 }}>Based in</span>
        <span style={{ fontSize: 18, fontWeight: 900, color: '#F97316', marginTop: 7, lineHeight: 1.1 }}>Algeria</span>
      </div>
    </div>
  </div>
</div>
```

```aura width=860 height=145
<div style={{ display: 'flex', width: '100%', height: '100%', gap: 14, fontFamily: 'Inter, sans-serif' }}>
    {[
    ['Frontend', 'Modern Web Interfaces', 'Clean, responsive and user-focused UI development.'],
    ['Backend', 'APIs & Databases', 'Scalable backend logic, data models and integrations.'],
    ['Desktop • Mobile • AI', 'Software Solutions', 'Building desktop, mobile and AI-powered applications across multiple platforms.']
  ].map((card, index) => (
    <div style={{ display: 'flex', flexDirection: 'column', flex: 1, justifyContent: 'center', gap: 6, padding: 20, background: '#111111', borderRadius: 18, border: '1px solid rgba(249,115,22,0.24)', position: 'relative', overflow: 'hidden' }}>
      <svg width="280" height="145" style={{ position: 'absolute', top: 0, left: 0 }}>
        <defs>
          <radialGradient id={`expertGlow${index}`}><stop offset="0%" stopColor="rgba(255,122,0,0.22)" /><stop offset="75%" stopColor="rgba(255,122,0,0)" /></radialGradient>
        </defs>

        <ellipse cx="70" cy="25" rx="130" ry="75" fill={`url(#expertGlow${index})`} opacity="0.45">
          <animate attributeName="cx" values="50;130;50" dur="8s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.25;0.6;0.25" dur="6s" repeatCount="indefinite" />
        </ellipse>

        <circle cx="230" cy="32" r="3" fill="#F97316" opacity="0.22">
          <animate attributeName="r" values="2;4;2" dur="5s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.38;0.08" dur="5s" repeatCount="indefinite" />
        </circle>

        <path d="M-40 118 C 45 95, 120 138, 290 105" stroke="rgba(251,146,60,0.13)" strokeWidth="1.5" fill="none">
          <animateTransform attributeName="transform" type="translate" values="-40 0;40 0;-40 0" dur="8s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.05;0.28;0.05" dur="8s" repeatCount="indefinite" />
        </path>
      </svg>

      <span style={{ fontSize: 13, fontWeight: 900, color: '#FB923C', position: 'relative', letterSpacing: 0.2 }}>{card[0]}</span>
      <span style={{ fontSize: 20, color: '#FFFFFF', fontWeight: 900, position: 'relative', lineHeight: 1.12 }}>{card[1]}</span>
      <span style={{ fontSize: 12, color: '#A1A1AA', position: 'relative', lineHeight: 1.35 }}>{card[2]}</span>
    </div>
  ))}
</div>
```

```aura width=860 height=275
<div style={{ display: 'flex', width: '100%', height: '100%', flexDirection: 'column', fontFamily: 'Inter, sans-serif', background: '#08080C', borderRadius: 18, padding: 30, border: '1px solid rgba(249,115,22,0.25)', overflow: 'hidden', position: 'relative' }}>
  <svg width="860" height="275" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="stackGlow"><stop offset="0%" stopColor="rgba(255,122,0,0.24)" /><stop offset="75%" stopColor="rgba(255,122,0,0)" /></radialGradient>
    </defs>

    <ellipse cx="690" cy="238" rx="280" ry="148" fill="url(#stackGlow)" opacity="0.8">
      <animate attributeName="cx" values="690;420;690" dur="11s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.4;0.85;0.4" dur="7s" repeatCount="indefinite" />
    </ellipse>

    <ellipse cx="120" cy="30" rx="130" ry="70" fill="url(#stackGlow)" opacity="0.35">
      <animate attributeName="cx" values="100;190;100" dur="10s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.15;0.45;0.15" dur="6s" repeatCount="indefinite" />
    </ellipse>

    <circle cx="110" cy="220" r="3" fill="#F97316" opacity="0.25">
      <animate attributeName="cx" values="110;210;110" dur="8s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.08;0.45;0.08" dur="8s" repeatCount="indefinite" />
    </circle>

    <circle cx="760" cy="70" r="4" fill="#FF7A00" opacity="0.22">
      <animate attributeName="cy" values="70;110;70" dur="6s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.08;0.4;0.08" dur="6s" repeatCount="indefinite" />
    </circle>

    <path d="M-120 245 C 160 190, 360 270, 610 210 S 830 180, 1020 230" stroke="rgba(255,122,0,0.12)" strokeWidth="2" fill="none">
      <animateTransform attributeName="transform" type="translate" values="-80 0;80 0;-80 0" dur="12s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.04;0.26;0.04" dur="12s" repeatCount="indefinite" />
    </path>
  </svg>

  <span style={{ fontSize: 13, color: '#FB923C', fontWeight: 900, textTransform: 'uppercase', letterSpacing: 1.5, position: 'relative' }}>Tech Stack</span>
  <span style={{ fontSize: 26, color: '#FFFFFF', fontWeight: 900, marginTop: 8, position: 'relative', letterSpacing: -0.3, lineHeight: 1.15 }}>Tools I use to build digital products</span>

  <div style={{ display: 'flex', gap: 14, marginTop: 22, position: 'relative' }}>
    {[
      ['Languages', ['JavaScript', 'TypeScript', 'Python', 'Java']],
      ['Frontend', ['React', 'Next.js', 'Tailwind CSS', 'Figma']],
      ['Backend', ['Node.js', 'Express.js', 'PostgreSQL', 'Prisma']],
      ['Desktop, Mobile & Cloud', ['React Native', 'Expo', 'Electron', 'Supabase']]
    ].map((group) => (
      <div style={{ display: 'flex', flexDirection: 'column', flex: 1, gap: 10, background: '#111111', borderRadius: 16, padding: 20, border: '1px solid rgba(249,115,22,0.18)' }}>
        <span style={{ color: '#FB923C', fontSize: 13, fontWeight: 900, letterSpacing: 0.2 }}>{group[0]}</span>
        {group[1].map((item) => (
          <span style={{ color: '#FFFFFF', fontSize: 13, lineHeight: 1.25 }}>{item}</span>
        ))}
      </div>
    ))}
  </div>
</div>
```

```aura width=860 height=135
<div style={{ display: 'flex', width: '100%', height: '100%', alignItems: 'center', justifyContent: 'space-between', gap: 18, fontFamily: 'Inter, sans-serif', background: '#050505', borderRadius: 18, padding: '0 34px', border: '1px solid rgba(249,115,22,0.16)', position: 'relative', overflow: 'hidden' }}>
  <svg width="860" height="135" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="ctaGlow">
        <stop offset="0%" stopColor="rgba(255,122,0,0.24)" />
        <stop offset="75%" stopColor="rgba(255,122,0,0)" />
      </radialGradient>
    </defs>

    <ellipse cx="650" cy="90" rx="170" ry="75" fill="url(#ctaGlow)" opacity="0.6">
      <animate attributeName="opacity" values="0.25;0.75;0.25" dur="6s" repeatCount="indefinite" />
      <animate attributeName="rx" values="130;190;130" dur="8s" repeatCount="indefinite" />
    </ellipse>

    <circle cx="760" cy="42" r="4" fill="#F97316" opacity="0.22">
      <animate attributeName="r" values="2;5;2" dur="5s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.08;0.42;0.08" dur="5s" repeatCount="indefinite" />
    </circle>

    <path d="M420 115 C 530 80, 680 135, 910 85" stroke="rgba(251,146,60,0.15)" strokeWidth="1.6" fill="none">
      <animateTransform attributeName="transform" type="translate" values="-60 0;60 0;-60 0" dur="9s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.04;0.3;0.04" dur="9s" repeatCount="indefinite" />
    </path>
  </svg>

  <div style={{ display: 'flex', flexDirection: 'column', justifyContent: 'center', width: 390, flexShrink: 0, position: 'relative' }}>
    <span style={{ fontSize: 24, fontWeight: 900, color: '#FFFFFF', letterSpacing: -0.45, lineHeight: 1.1 }}>Let’s Create Impactful Digital Experiences.</span>
    <span style={{ fontSize: 13, color: '#A1A1AA', marginTop: 8, lineHeight: 1.4 }}>Available for freelance projects, software engineering roles and strategic collaborations.</span>
  </div>

  <div style={{ display: 'flex', width: 390, gap: 10, alignItems: 'center', justifyContent: 'space-between', flexShrink: 0, marginLeft: 'auto', position: 'relative' }}>
    {[
      ['LinkedIn', 'https://www.linkedin.com/in/adrouche-ahmed-islam-1391aa341/'],
      ['Email', 'mailto:islxmad@gmail.com'],
      ['Portfolio', 'PUT_PORTFOLIO_LINK_HERE']
    ].map((btn, index) => (
      <a href={btn[1]} style={{ textDecoration: 'none' }}>
        <div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', width: 120, height: 46, background: '#08080C', borderRadius: 999, position: 'relative', overflow: 'hidden' }}>
          <svg width="120" height="46" style={{ position: 'absolute', top: 0, left: 0, pointerEvents: 'none' }}>
            <defs>
              <linearGradient id={`btnBorder${index}`} x1="0" y1="0" x2="1" y2="0">
                <stop offset="0%" stopColor="#F97316" />
                <stop offset="36%" stopColor="#FF7A00" />
                <stop offset="52%" stopColor="#050505" />
                <stop offset="74%" stopColor="#FB923C" />
                <stop offset="100%" stopColor="#F97316" />
                <animateTransform attributeName="gradientTransform" type="rotate" from="0 0.5 0.5" to="360 0.5 0.5" dur="5.5s" repeatCount="indefinite" />
              </linearGradient>
            </defs>

            <rect x="1" y="1" width="118" height="44" rx="22" fill="none" stroke={`url(#btnBorder${index})`} strokeWidth="1.7" strokeDasharray="16 8">
              <animate attributeName="stroke-dashoffset" values="0;48" dur="4.6s" repeatCount="indefinite" />
            </rect>
            <rect x="1" y="1" width="118" height="44" rx="22" fill="none" stroke={`url(#btnBorder${index})`} strokeWidth="3" opacity="0.18" strokeDasharray="16 8">
              <animate attributeName="stroke-dashoffset" values="0;48" dur="4.6s" repeatCount="indefinite" />
              <animate attributeName="opacity" values="0.08;0.25;0.08" dur="4.6s" repeatCount="indefinite" />
            </rect>
            <rect x="2" y="2" width="116" height="42" rx="21" fill="#08080C" />
          </svg>

          <span style={{ color: '#F97316', fontSize: 14, fontWeight: 900, position: 'relative' }}>{btn[0]}</span>
        </div>
      </a>
    ))}
  </div>
</div>
```
