:root {
    --card: rgba(15, 20, 45, 0.85);
    --text: #e5e7eb;
    --primary: #a78bfa;
    --link: #7dd3fc;
}

/* PAGE BACKGROUND */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background:
        radial-gradient(circle at 20% 30%, #7c3aed55, transparent 40%),
        radial-gradient(circle at 80% 70%, #2563eb55, transparent 40%),
        radial-gradient(circle at 50% 50%, #0ea5e955, transparent 45%),
        linear-gradient(180deg, #020617, #000000);
    color: var(--text);
    cursor: none;
    overflow-x: hidden;
}

/* BACKGROUND STARS */
body::before {
    content: "";
    position: fixed;
    inset: 0;
    background:
        radial-gradient(1px 1px at 10% 20%, #fff, transparent),
        radial-gradient(1px 1px at 30% 80%, #fff, transparent),
        radial-gradient(1px 1px at 60% 40%, #fff, transparent),
        radial-gradient(1px 1px at 80% 60%, #fff, transparent);
    opacity: 0.5;
    z-index: -1;
}

/* STAR CURSOR */
.star-cursor {
    position: fixed;
    font-size: 18px;
    color: #fde047;
    pointer-events: none;
    z-index: 1000;
    transform: translate(-50%, -50%);
    text-shadow: 0 0 15px rgba(253,224,71,1);
}

/* CURSOR TRAIL */
.cursor-star {
    position: fixed;
    width: 3px;
    height: 3px;
    background: white;
    border-radius: 50%;
    pointer-events: none;
    box-shadow: 0 0 8px white;
    z-index: 999;
}

/* HEADER */
header {
    padding: 60px 20px;
    text-align: center;
}

.header-box {
    max-width: 900px;
    margin: auto;
    background:
        linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
        url("https://images.unsplash.com/photo-1444703686981-a3abbc4d4fe3?auto=format&fit=crop&w=1600&q=80");
    background-size: cover;
    background-position: center;
    border-radius: 22px;
    padding: 40px;
    backdrop-filter: blur(6px);
    box-shadow: 0 0 45px rgba(167,139,250,0.6);
}

.container {
    max-width: 900px;
    margin: 40px auto;
    background: var(--card);
    padding: 28px;
    border-radius: 22px;
    backdrop-filter: blur(12px);
    box-shadow: 0 0 35px rgba(14,165,233,0.4);
}

h2 {
    color: var(--primary);
    border-bottom: 2px solid rgba(167,139,250,0.4);
}

.info p {
    position: relative;
    padding-right: 30px;
    transition: transform 0.3s ease, color 0.3s ease;
}

.info p::after {
    content: "\f005";
    font-family: "Font Awesome 6 Free";
    font-weight: 900;
    position: absolute;
    right: 0;
    top: 50%;
    transform: translateY(-50%);
    color: #fde047;
    opacity: 0;
}

.info p:hover {
    transform: translateX(6px);
    color: var(--primary);
}

.info p:hover::after {
    opacity: 1;
}

a {
    color: var(--link);
    text-decoration: none;
}

footer {
    text-align: center;
    padding: 20px;
    color: #9ca3af;
}
