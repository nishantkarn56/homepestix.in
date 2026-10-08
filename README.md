<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="description" content="HomePestix India provides residential pest control services in Faridabad, Delhi and Noida. House pest control starting from ₹1,100. We use only Herbal Medicines.">
        <meta name="keywords" content="pest control Faridabad, pest control Delhi, pest control Noida, home pest control, residential pest control Delhi NCR">
        <title>HomePestix India | Residential Pest Control in Faridabad, Delhi & Noida</title>
        <style>
            :root {
                --green: #214f3a;
                --deep: #132a20;
                --forest: #0d241a;
                --cream: #f7f1e5;
                --ivory: #fffdf8;
                --gold: #b99552;
                --gold2: #d9c08a;
                --text: #2d352f;
                --muted: #6f746f;
                --line: #ddd2ba;
                --shadow: 0 18px 45px rgba(33,79,58,.14)
            }

            * {
                box-sizing: border-box;
                margin: 0;
                padding: 0
            }

            html {
                scroll-behavior: smooth
            }

            body {
                font-family: Georgia,'Times New Roman',serif;
                color: var(--text);
                line-height: 1.65;
                background: var(--ivory);
                overflow-x: hidden
            }

            a {
                text-decoration: none;
                color: inherit
            }

            .wrap {
                width: min(1160px,92%);
                margin: auto
            }

            header {
                position: sticky;
                top: 0;
                z-index: 50;
                background: rgba(255,253,248,.95);
                backdrop-filter: blur(10px);
                border-bottom: 1px solid var(--line);
                box-shadow: 0 3px 18px rgba(19,42,32,.05)
            }

            .nav {
                height: 80px;
                display: flex;
                align-items: center;
                justify-content: space-between
            }

            .logo {
                font-size: 1.52rem;
                font-weight: 900;
                color: var(--deep);
                letter-spacing: .3px
            }

            .logo span {
                color: var(--green)
            }

            nav {
                display: flex;
                gap: 26px;
                align-items: center
            }

            nav a {
                font-size: .92rem;
                font-weight: 700;
                letter-spacing: .2px;
                transition: .25s
            }

            nav a:hover {
                color: var(--gold)
            }

            .navcta,.btn {
                background: linear-gradient(135deg,var(--green),#2c6b4d);
                color: white;
                padding: 12px 20px;
                border-radius: 4px;
                font-weight: 800;
                display: inline-block;
                border: 1px solid #2e6a4f;
                box-shadow: 0 8px 20px rgba(33,79,58,.18);
                transition: .25s
            }

            .navcta:hover,.btn:hover {
                transform: translateY(-2px);
                box-shadow: 0 12px 26px rgba(33,79,58,.24)
            }

            .hero {
                position: relative;
                isolation: isolate;
                background: radial-gradient(circle at 10% 10%,rgba(217,192,138,.34),transparent 28%),linear-gradient(135deg,#f8f2e6 0%,#fffdf8 58%,#eef5f0 100%);
                padding: 98px 0 92px;
                border-bottom: 1px solid var(--line);
                overflow: hidden
            }

            .hero:before,.hero:after {
                content: '';
                position: absolute;
                border: 1px solid rgba(185,149,82,.28);
                border-radius: 50%;
                z-index: -1
            }

            .hero:before {
                width: 420px;
                height: 420px;
                right: -120px;
                top: -150px
            }

            .hero:after {
                width: 260px;
                height: 260px;
                left: -100px;
                bottom: -120px
            }

            .hero-grid {
                display: grid;
                grid-template-columns: 1.15fr .85fr;
                gap: 58px;
                align-items: center
            }

            .kicker {
                font-family: Arial,Helvetica,sans-serif;
                font-size: .74rem;
                text-transform: uppercase;
                letter-spacing: 2.4px;
                font-weight: 900;
                color: var(--gold);
                margin-bottom: 14px
            }

            h1 {
                font-size: clamp(2.7rem,5vw,4.7rem);
                line-height: 1.03;
                color: var(--deep);
                margin-bottom: 22px;
                letter-spacing: -1px
            }

            h1 span {
                color: var(--green)
            }

            .hero p {
                font-family: Arial,Helvetica,sans-serif;
                font-size: 1.08rem;
                color: var(--muted);
                max-width: 670px;
                margin-bottom: 28px
            }

            .actions {
                display: flex;
                gap: 12px;
                flex-wrap: wrap
            }

            .btn.alt {
                background: transparent;
                color: var(--green);
                border: 1px solid var(--gold);
                box-shadow: none
            }

            .btn.alt:hover {
                background: #fffaf0
            }

            .herbal-badge {
                display: inline-flex;
                align-items: center;
                gap: 9px;
                background: #f4ead2;
                border: 1px solid #d7bd83;
                color: #5f4c27;
                padding: 9px 13px;
                border-radius: 999px;
                font-family: Arial,Helvetica,sans-serif;
                font-size: .84rem;
                font-weight: 800;
                margin: 0 0 22px
            }

            .hero-card {
                position: relative;
                background: linear-gradient(180deg,#fffdf8,#fbf6eb);
                border: 1px solid var(--gold2);
                border-radius: 10px;
                padding: 34px;
                box-shadow: var(--shadow)
            }

            .hero-card:before {
                content: '';
                position: absolute;
                inset: 8px;
                border: 1px solid rgba(185,149,82,.28);
                border-radius: 6px;
                pointer-events: none
            }

            .house {
                font-size: 4rem;
                margin-bottom: 7px
            }

            .hero-card h3 {
                font-size: 1.55rem;
                color: var(--deep);
                margin-bottom: 7px
            }

            .hero-card p,.hero-card li {
                font-family: Arial,Helvetica,sans-serif
            }

            .hero-card ul {
                list-style: none;
                margin-top: 18px
            }

            .hero-card li {
                padding: 10px 0;
                border-bottom: 1px solid #ece2cc
            }

            .hero-card li:last-child {
                border: 0
            }

            .hero-card li:before {
                content: '✓';
                font-weight: 900;
                color: var(--green);
                margin-right: 9px
            }

            section {
                padding: 80px 0
            }

            .light {
                background: linear-gradient(180deg,#f7f1e5,#fbf8f1)
            }

            .heading {
                text-align: center;
                max-width: 760px;
                margin: 0 auto 44px
            }

            .heading h2 {
                font-size: 2.55rem;
                color: var(--deep);
                margin-bottom: 10px
            }

            .heading p {
                font-family: Arial,Helvetica,sans-serif;
                color: var(--muted)
            }

            .ornament {
                display: flex;
                justify-content: center;
                align-items: center;
                gap: 10px;
                margin: 13px 0 0;
                color: var(--gold)
            }

            .ornament:before,.ornament:after {
                content: '';
                width: 70px;
                height: 1px;
                background: var(--gold2)
            }

            .grid3 {
                display: grid;
                grid-template-columns: repeat(3,1fr);
                gap: 22px
            }

            .card {
                background: rgba(255,253,248,.94);
                border: 1px solid var(--line);
                border-radius: 8px;
                padding: 28px;
                box-shadow: 0 10px 28px rgba(19,42,32,.06);
                transition: .25s
            }

            .card:hover {
                transform: translateY(-4px);
                box-shadow: 0 16px 34px rgba(19,42,32,.11)
            }

            .icon {
                font-size: 2rem;
                margin-bottom: 10px
            }

            .card h3 {
                color: var(--deep);
                margin-bottom: 7px
            }

            .card p {
                font-family: Arial,Helvetica,sans-serif;
                color: var(--muted);
                font-size: .95rem
            }

            .herbal-strip {
                margin-top: 28px;
                background: linear-gradient(135deg,#173d2c,#214f3a);
                color: #fff;
                border: 1px solid #7f9f8f;
                border-radius: 8px;
                padding: 22px 26px;
                display: flex;
                gap: 18px;
                align-items: center;
                box-shadow: var(--shadow)
            }

            .herbal-strip .leaf {
                font-size: 2rem
            }

            .herbal-strip strong {
                display: block;
                color: #f4e2b4;
                font-size: 1.05rem
            }

            .herbal-strip p {
                font-family: Arial,Helvetica,sans-serif;
                color: #e7efe9;
                font-size: .94rem
            }

            .price-grid {
                display: grid;
                grid-template-columns: repeat(4,1fr);
                gap: 18px
            }

            .price {
                border: 1px solid var(--line);
                border-radius: 8px;
                text-align: center;
                padding: 28px;
                background: #fffdf8;
                box-shadow: 0 10px 26px rgba(19,42,32,.05)
            }

            .price strong {
                display: block;
                color: var(--green);
                font-size: 1.78rem;
                margin: 8px 0
            }

            .price small {
                font-family: Arial,Helvetica,sans-serif;
                color: var(--muted)
            }

            .dark {
                position: relative;
                background: linear-gradient(135deg,#0b2117,#173d2c 55%,#214f3a);
                color: white;
                overflow: hidden
            }

            .dark:after {
                content: '';
                position: absolute;
                width: 320px;
                height: 320px;
                border: 1px solid rgba(217,192,138,.18);
                border-radius: 50%;
                right: -90px;
                bottom: -120px
            }

            .area-grid {
                display: grid;
                grid-template-columns: 1fr 1fr;
                gap: 38px;
                align-items: center;
                position: relative;
                z-index: 1
            }

            .dark h2 {
                font-size: 2.45rem;
                margin-bottom: 10px
            }

            .dark p {
                font-family: Arial,Helvetica,sans-serif;
                color: #d4e0da
            }

            .pills {
                display: flex;
                gap: 11px;
                flex-wrap: wrap;
                margin-top: 20px
            }

            .pill {
                border: 1px solid #7b9d8d;
                border-radius: 99px;
                padding: 9px 15px;
                font-family: Arial,Helvetica,sans-serif
            }

            .notice {
                background: #fbf1d9;
                color: #624b16;
                border-radius: 8px;
                padding: 26px;
                border: 1px solid #d8ba79;
                box-shadow: 0 12px 26px rgba(0,0,0,.08)
            }

            .notice strong {
                font-size: 1.05rem
            }

            .steps {
                display: grid;
                grid-template-columns: repeat(3,1fr);
                gap: 22px
            }

            .step {
                border: 1px solid var(--line);
                border-radius: 8px;
                padding: 27px;
                background: #fffdf8
            }

            .step p {
                font-family: Arial,Helvetica,sans-serif;
                color: var(--muted)
            }

            .num {
                width: 39px;
                height: 39px;
                background: linear-gradient(135deg,var(--gold),#d6b36e);
                color: #213228;
                border-radius: 50%;
                display: grid;
                place-items: center;
                font-family: Arial,Helvetica,sans-serif;
                font-weight: 900;
                margin-bottom: 14px
            }

            .contact {
                background: linear-gradient(180deg,#f7f1e5,#efe5d2)
            }

            .contactbox {
                background: #fffdf8;
                border: 1px solid var(--gold2);
                border-radius: 10px;
                padding: 42px;
                display: flex;
                justify-content: space-between;
                align-items: center;
                gap: 30px;
                box-shadow: var(--shadow)
            }

            .contactbox h2 {
                font-size: 2.2rem;
                color: var(--deep)
            }

            .contactbox p,.phone {
                font-family: Arial,Helvetica,sans-serif
            }

            .phone {
                font-weight: 800;
                margin-top: 7px
            }

            footer {
                background: #081b13;
                color: #cbd8d2;
                padding: 32px 0;
                border-top: 1px solid #294536
            }

            .foot {
                display: flex;
                justify-content: space-between;
                gap: 20px;
                flex-wrap: wrap;
                font-family: Arial,Helvetica,sans-serif
            }

            .float {
                position: fixed;
                right: 21px;
                bottom: 21px;
                background: #25d366;
                color: white;
                width: 60px;
                height: 60px;
                border-radius: 50%;
                display: grid;
                place-items: center;
                font-family: Arial,Helvetica,sans-serif;
                font-weight: 900;
                box-shadow: 0 8px 24px #0004;
                z-index: 60;
                transition: .25s
            }

            .float:hover {
                transform: scale(1.06)
            }

            @media(max-width: 800px) {
                nav {
                    display:none
                }

                .hero {
                    padding: 64px 0
                }

                .hero-grid,.area-grid {
                    grid-template-columns: 1fr
                }

                .grid3 {
                    grid-template-columns: 1fr 1fr
                }

                .price-grid {
                    grid-template-columns: 1fr 1fr
                }

                .steps {
                    grid-template-columns: 1fr
                }

                .contactbox {
                    flex-direction: column;
                    align-items: flex-start
                }
            }

            @media(max-width: 520px) {
                .grid3,.price-grid {
                    grid-template-columns:1fr
                }

                section {
                    padding: 58px 0
                }

                .heading h2 {
                    font-size: 2.05rem
                }

                .hero-card {
                    padding: 26px
                }

                .contactbox {
                    padding: 28px
                }
            }
        </style>
    </head>
    <body>
        <header>
            <div class="wrap nav">
                <a class="logo" href="#">
                    HomePestix <span>India</span>
                </a>
                <nav>
                    <a href="#services">Services</a>
                    <a href="#pricing">Pricing</a>
                    <a href="#areas">Areas</a>
                    <a href="#contact">Contact</a>
                    <a class="navcta" target="_blank" rel="noopener" href="https://wa.me/917303671413?text=Hello%20HomePestix%20India%2C%20I%20want%20a%20house%20pest%20control%20enquiry.">WhatsApp</a>
                </nav>
            </div>
        </header>
        <main>
            <section class="hero">
                <div class="wrap hero-grid">
                    <div>
                        <div class="kicker">Residential Pest Control</div>
                        <h1>
                            A cleaner, safer <span>home starts here.</span>
                        </h1>
                        <p>HomePestix India provides professional pest control services for houses in Faridabad, Delhi and Noida. Easy enquiry, clear starting prices and service focused on residential properties.</p>
                        <div class="herbal-badge">🌿 We use only Herbal Medicines</div>
                        <div class="actions">
                            <a class="btn" target="_blank" rel="noopener" href="https://wa.me/917303671413?text=Hello%20HomePestix%20India%2C%20I%20want%20a%20pest%20control%20enquiry.">Enquire on WhatsApp</a>
                            <a class="btn alt" href="#pricing">See Pricing</a>
                        </div>
                    </div>
                    <div class="hero-card">
                        <div class="house">🏠</div>
                        <h3>Home Pest Protection</h3>
                        <p>Residential properties only. Commercial properties are not serviced.</p>
                        <ul>
                            <li>Faridabad</li>
                            <li>Delhi</li>
                            <li>Noida</li>
                            <li>₹1,100–₹5,600 pricing range</li>
                            <li>We use only Herbal Medicines</li>
                        </ul>
                    </div>
                </div>
            </section>
            <section id="services" class="light">
                <div class="wrap">
                    <div class="heading">
                        <div class="kicker">What we offer</div>
                        <h2>Residential pest control services</h2>
                        <p>Tell us what is happening in your home and enquire directly through WhatsApp.</p>
                    </div>
                    <div class="ornament">◆</div>
                </div>
                <div class="grid3">
                    <div class="card">
                        <div class="icon">🪳</div>
                        <h3>Cockroach Control</h3>
                        <p>Residential treatment for common cockroach problems in kitchens, bathrooms and other home areas.</p>
                    </div>
                    <div class="card">
                        <div class="icon">🐜</div>
                        <h3>Ant Control</h3>
                        <p>Help reduce ant activity around common entry points and areas inside the home.</p>
                    </div>
                    <div class="card">
                        <div class="icon">🦟</div>
                        <h3>Mosquito Control</h3>
                        <p>Residential mosquito-control solutions to help make your home more comfortable.</p>
                    </div>
                    <div class="card">
                        <div class="icon">🐀</div>
                        <h3>Rodent Control</h3>
                        <p>Enquire for help with rats and mice affecting your residential property.</p>
                    </div>
                    <div class="card">
                        <div class="icon">🪲</div>
                        <h3>Termite Control</h3>
                        <p>Enquire about termite treatment options for your house and property.</p>
                    </div>
                    <div class="card">
                        <div class="icon">🐞</div>
                        <h3>General Pest Control</h3>
                        <p>Have another pest issue? Contact us with details so we can discuss the suitable service.</p>
                    </div>
                </div>
                <div class="herbal-strip">
                    <div class="leaf">🌿</div>
                    <div>
                        <strong>Herbal Treatment Approach</strong>
                        <p>We use only Herbal Medicines for our residential pest-control services.</p>
                    </div>
                </div>
</ div></ section>
<section id="pricing">
    <div class="wrap">
        <div class="heading">
            <div class="kicker">Simple pricing</div>
            <h2>Services from ₹1,100</h2>
            <p>The final price can vary based on the pest problem, property requirements and treatment needed.</p>
        </div>
        <div class="price-grid">
            <div class="price">
                <small>Starting</small>
                <strong>₹1,100</strong>
                <small>Residential service</small>
            </div>
            <div class="price">
                <small>Standard</small>
                <strong>₹2,000+</strong>
                <small>Depending on requirement</small>
            </div>
            <div class="price">
                <small>Advanced</small>
                <strong>₹3,500+</strong>
                <small>Depending on requirement</small>
            </div>
            <div class="price">
                <small>Maximum shown</small>
                <strong>₹5,600</strong>
                <small>Residential service</small>
            </div>
        </div>
    </div>
</section>
<section id="areas" class="dark">
    <div class="wrap area-grid">
        <div>
            <div class="kicker" style="color:#9bd6b7">Where we serve</div>
            <h2>Serving homes across Delhi-NCR</h2>
            <p>HomePestix India provides pest control services for houses in Faridabad, Delhi and Noida.</p>
            <div class="pills">
                <span class="pill">Faridabad</span>
                <span class="pill">Delhi</span>
                <span class="pill">Noida</span>
            </div>
        </div>
        <div class="notice">
            <strong>Residential only</strong>
            <br>
            <br>
            HomePestix India currently provides services for <strong>houses/residential properties only</strong>
            . We do not provide pest-control services for commercial properties.
        </div>
    </div>
</section>
<section>
    <div class="wrap">
        <div class="heading">
            <div class="kicker">Easy booking</div>
            <h2>How it works</h2>
        </div>
        <div class="steps">
            <div class="step">
                <div class="num">1</div>
                <h3>Send an enquiry</h3>
                <p>Message us on WhatsApp with your location and pest problem.</p>
            </div>
            <div class="step">
                <div class="num">2</div>
                <h3>Discuss your requirement</h3>
                <p>Share the basic details of your house and the issue you are facing.</p>
            </div>
            <div class="step">
                <div class="num">3</div>
                <h3>Schedule the service</h3>
                <p>Confirm the details and arrange your residential pest-control service.</p>
            </div>
        </div>
    </div>
</section>
<section id="contact" class="contact">
    <div class="wrap">
        <div class="contactbox">
            <div>
                <div class="kicker">Get in touch</div>
                <h2>Need pest control for your home?</h2>
                <p>Contact HomePestix India directly on WhatsApp.</p>
                <p style="margin-top:6px;color:#6f746f">🌿 We use only Herbal Medicines.</p>
                <div class="phone">WhatsApp: 7303671413</div>
            </div>
            <a class="btn" target="_blank" rel="noopener" href="https://wa.me/917303671413?text=Hello%20HomePestix%20India%2C%20I%20want%20to%20book%20a%20house%20pest%20control%20service.">Chat on WhatsApp →</a>
        </div>
    </div>
</section>
</ main>
<footer>
    <div class="wrap foot">
        <div>
            <strong>HomePestix India</strong>
            <br>Residential Pest Control
        </div>
        <div>
            Faridabad • Delhi • Noida<br>© 2026 HomePestix India
        </div>
    </div>
</footer>
<a class="float" aria-label="WhatsApp" target="_blank" rel="noopener" href="https://wa.me/917303671413?text=Hello%20HomePestix%20India%2C%20I%20want%20a%20pest%20control%20enquiry.">WA</a>
</ body></ html>
