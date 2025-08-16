# Jesse-sales-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RankExpand - AI-Driven SEO That Actually Works</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        html, body {
            overflow-x: hidden;
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background: #fff;
        }
        
        .container {
            width: 100%;
            max-width: 800px;
            margin: 0 auto;
            padding: 0 2rem;
        }
        
        .hero {
            background: linear-gradient(135deg, #1a237e 0%, #3949ab 100%);
            color: white;
            padding: 4rem 0;
            text-align: center;
        }
        
        .preheader {
            font-size: 0.9rem;
            color: #b39ddb;
            margin-bottom: 1rem;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        
        .hero h1 {
            font-size: 3rem;
            font-weight: bold;
            margin-bottom: 1.5rem;
            line-height: 1.2;
        }
        
        .hero .subheader {
            font-size: 1.3rem;
            margin-bottom: 2rem;
            color: #e8eaf6;
            font-weight: 300;
        }
        
        .vsl-container {
            margin: 2rem 0;
            position: relative;
            display: flex;
            justify-content: center;
            cursor: pointer;
        }
        
        .vsl-thumbnail {
            width: 500px;
            max-width: 100%;
            height: 280px;
            background: linear-gradient(45deg, #1a1a1a, #2d2d2d);
            background-image: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 280"><rect width="500" height="280" fill="%23000"/><text x="250" y="140" text-anchor="middle" fill="%23fff" font-family="Arial" font-size="24">Case Study Video</text></svg>');
            background-size: cover;
            border-radius: 12px;
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 8px 32px rgba(0,0,0,0.4);
            cursor: pointer;
            transition: transform 0.3s ease;
        }
        
        .vsl-thumbnail:hover {
            transform: scale(1.02);
        }
        
        .video-title {
            position: absolute;
            bottom: 15px;
            left: 15px;
            color: white;
            font-size: 1rem;
            font-weight: bold;
            background: rgba(0,0,0,0.7);
            padding: 0.5rem 1rem;
            border-radius: 6px;
        }
        
        .video-length {
            position: absolute;
            top: 15px;
            right: 15px;
            background: rgba(0,0,0,0.8);
            color: white;
            padding: 0.3rem 0.6rem;
            border-radius: 4px;
            font-size: 0.9rem;
        }
        
        .play-button {
            width: 80px;
            height: 80px;
            background: rgba(255,255,255,0.9);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            transition: transform 0.3s ease;
        }
        
        .play-button:hover {
            transform: scale(1.1);
        }
        
        .play-button::before {
            content: '';
            width: 0;
            height: 0;
            border-left: 25px solid #1a237e;
            border-top: 15px solid transparent;
            border-bottom: 15px solid transparent;
            margin-left: 5px;
        }
        
        .cta-primary {
            background: #ff5722;
            color: white;
            padding: 1rem 2.5rem;
            font-size: 1.2rem;
            font-weight: bold;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            text-decoration: none;
            display: block;
            margin: 2rem auto 1rem auto;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 1px;
            text-align: center;
            width: fit-content;
        }
        
        .cta-primary:hover {
            background: #e64a19;
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(255, 87, 34, 0.4);
        }
        
        .section {
            padding: 4rem 0;
        }
        
        .section h2 {
            font-size: 2.5rem;
            margin-bottom: 2rem;
            color: #1a237e;
            text-align: center;
        }
        
        .section p {
            font-size: 1.1rem;
            margin-bottom: 1.5rem;
            color: #424242;
        }
        
        .problem-section {
            background: #fafafa;
        }
        
        .origin-section {
            background: white;
        }
        
        .solution-section {
            background: #f3e5f5;
        }
        
        .product-section {
            background: white;
        }
        
        .offer-section {
            background: #e8f5e8;
        }
        
        .faq-section {
            background: #fff3e0;
        }
        
        .bullets {
            list-style: none;
            margin: 2rem 0;
        }
        
        .bullets li {
            padding: 1rem 0;
            border-bottom: 1px solid #e0e0e0;
            font-size: 1.1rem;
            position: relative;
            padding-left: 2rem;
        }
        
        .bullets li::before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #4caf50;
            font-weight: bold;
            font-size: 1.3rem;
        }
        
        .testimonial {
            background: white;
            padding: 2rem;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            margin: 2rem 0;
            border-left: 5px solid #4caf50;
        }
        
        .testimonial p {
            font-style: italic;
            color: #555;
        }
        
        .testimonial-author {
            font-weight: bold;
            color: #1a237e;
            margin-top: 1rem;
        }
        
        .guarantee-box {
            background: #fff;
            border: 3px solid #4caf50;
            padding: 2rem;
            border-radius: 12px;
            text-align: center;
            margin: 2rem 0;
        }
        
        .guarantee-box h3 {
            color: #4caf50;
            font-size: 1.8rem;
            margin-bottom: 1rem;
        }
        
        .faq-item {
            margin-bottom: 2rem;
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }
        
        .faq-question {
            font-weight: bold;
            color: #1a237e;
            font-size: 1.2rem;
            margin-bottom: 1rem;
        }
        
        .highlight {
            background: #ffeb3b;
            padding: 0.2rem 0.5rem;
            border-radius: 4px;
        }
        
        .bold {
            font-weight: bold;
        }
        
        .caps {
            text-transform: uppercase;
            font-weight: bold;
        }
        
        .italic {
            font-style: italic;
        }
        
        @media (max-width: 1024px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            .container {
                padding: 0 1.5rem;
            }
        }
        
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }
            .hero .subheader {
                font-size: 1.1rem;
            }
            .section h2 {
                font-size: 2rem;
            }
            .vsl-thumbnail {
                width: 100%;
                height: 200px;
            }
            .container {
                padding: 0 1rem;
            }
            .section {
                padding: 3rem 0;
            }
        }
    </style>
</head>
<body>
    <!-- HERO SECTION -->
    <section class="hero">
        <div class="container">
            <div class="preheader">For Niche Service Business Owners & E-Commerce Sellers</div>
            
            <h1>Get #1 Google Rankings in 90 Days Using AI-Driven Semantic SEO</h1>
            
            <div class="subheader">
                Without wasting months on outdated SEO tactics or paying $5,000/month agency retainers
            </div>
            
            <div class="vsl-container">
                <div class="vsl-thumbnail">
                    <div class="video-title">Watch: How We Got 47 New HVAC Customers in 90 Days</div>
                    <div class="play-button"></div>
                    <div class="video-length">8:34</div>
                </div>
            </div>
            
            <a href="https://rankexpand.com/semantic-branching-seo-audit" class="cta-primary">Apply For Your Free SEO Audit</a>
        </div>
    </section>

    <!-- PROBLEM IDENTIFICATION -->
    <section class="section problem-section">
        <div class="container">
            <h2>You're Losing Money Every Day Your Business Stays Invisible</h2>
            
            <p>Your competitors are stealing your customers...</p>
            
            <p>While you're stuck on page 3 of Google, watching your phone stay silent and your inbox empty.</p>
            
            <p>You've tried everything. <span class="italic">Generic SEO agencies</span> that promise the world but deliver cookie-cutter content that Google ignores...</p>
            
            <p><span class="italic">DIY keyword tools</span> that give you the same outdated data everyone else is using...</p>
            
            <p><span class="italic">Content writers</span> who churn out blog posts that sound like they were written by a robot (because they probably were)...</p>
            
            <p>And each month that passes? <span class="bold">You're falling further behind.</span></p>
            
            <p>Your competitors are getting smarter. They're using AI. They're ranking higher. They're getting the leads that should be yours.</p>
            
            <p>But what if I told you there's a <span class="highlight">proven new way</span> that's already working for service businesses just like yours?</p>
        </div>
    </section>

    <!-- ORIGIN STORY -->
    <section class="section origin-story">
        <div class="container">
            <h2>The Night Everything Changed</h2>
            
            <p>Three years ago, I was exactly where you are now...</p>
            
            <p>Running an SEO agency, burning through client budgets with traditional tactics that used to work but suddenly... didn't.</p>
            
            <p>Client after client was asking the same question: <span class="italic">"Why aren't we ranking anymore?"</span></p>
            
            <p>Google had changed. Their algorithms got smarter. They started understanding context, intent, and meaning in ways that made old-school keyword stuffing look like stone-age tactics.</p>
            
            <p>That's when I discovered something that changed everything...</p>
            
            <p><span class="bold caps">Google's own NLP API.</span></p>
            
            <p>The same artificial intelligence Google uses to understand web pages... I could use it to create content that speaks Google's language fluently.</p>
            
            <p>Instead of guessing what Google wanted, I could <span class="italic">ask Google directly</span> through their own AI system.</p>
            
            <p>The results were immediate. Clients who were stuck on page 2 shot to position #1 within weeks. Local service businesses started generating so many leads they had to hire more staff.</p>
            
            <p>But here's what nobody else realized...</p>
        </div>
    </section>

    <!-- SOLUTION REVELATION -->
    <section class="section solution-section">
        <div class="container">
            <h2>The Secret Google Doesn't Want SEO Agencies to Know</h2>
            
            <p>Google's algorithm doesn't just look at keywords anymore...</p>
            
            <p>It understands <span class="bold">semantic relationships</span>. Context. Intent. The deeper meaning behind what people are actually searching for.</p>
            
            <p>That's why traditional SEO fails. It's still playing checkers while Google is playing 4D chess.</p>
            
            <p><span class="bold">Our Semantic Analysis Tool</span> uses Google's own NLP API to:</p>
            
            <ul class="bullets">
                <li><span class="bold">Reverse-engineer exactly what Google wants to see</span> → So you stop guessing and start ranking → Making you the obvious expert in your niche</li>
                <li><span class="bold">Identify semantic keyword clusters your competitors miss</span> → Giving you traffic they don't even know exists → Positioning you as the market leader</li>
                <li><span class="bold">Create content that sounds natural but ranks unnaturally high</span> → No more robotic, keyword-stuffed pages → Building trust that converts visitors into customers</li>
                <li><span class="bold">Map your entire content strategy based on search intent</span> → Every page serves a specific purpose in your sales funnel → Turning your website into a lead-generation machine</li>
            </ul>
            
            <div class="testimonial">
                <p>"We went from invisible to owning the first page for 'HVAC repair [our city]' in just 6 weeks. Our phone hasn't stopped ringing since. Last month alone we booked $47,000 in new business."</p>
                <div class="testimonial-author">- Mike Patterson, Patterson HVAC</div>
            </div>
            
            <p>This isn't theory. It's not some "hack" that'll stop working next month.</p>
            
            <p><span class="caps bold">This is using Google's own technology against itself.</span></p>
        </div>
    </section>

    <!-- PRODUCT INTRODUCTION -->
    <section class="section product-section">
        <div class="container">
            <h2>Introducing RankExpand: SEO That Actually Works in 2025</h2>
            
            <p>Finally, an SEO solution built for the way Google <span class="italic">actually</span> works today...</p>
            
            <p>Not the way it worked in 2015. Not the way other agencies wish it worked. The way it works <span class="bold">right now</span>.</p>
            
            <p>Here's what you get when you work with RankExpand:</p>
            
            <ul class="bullets">
                <li><span class="bold">Semantic Analysis Tool powered by Google's NLP API</span> - The same AI Google uses to understand your website, now working FOR you instead of against you</li>
                <li><span class="bold">15-page comprehensive website optimization</span> - Every page strategically crafted to dominate your most profitable keywords</li>
                <li><span class="bold">Monthly high-authority backlink building</span> - Real relationships with real websites in your industry, not spam links that'll get you penalized</li>
                <li><span class="bold">AI-optimized content creation</span> - Content that reads naturally to humans but speaks fluent Google to algorithms</li>
                <li><span class="bold">Real-time ranking tracking and reporting</span> - Watch your competitors disappear in your rearview mirror</li>
            </ul>
            
            <p>But here's what makes this different from every other SEO service you've seen...</p>
            
            <p>Instead of generic strategies that might work for anyone, this is <span class="highlight">laser-targeted for niche service businesses</span> and e-commerce sellers.</p>
            
            <p>We know your customers don't just search for "plumber"... they search for "emergency plumber near me at 2am."</p>
            
            <p>We know your success depends on local dominance, not national awareness.</p>
            
            <p>And we know you need leads <span class="italic">this month</span>, not next year.</p>
        </div>
    </section>

    <!-- OFFER STRUCTURE -->
    <section class="section offer-section">
        <div class="container">
            <h2>Get Your Business Ranking #1 Starting Today</h2>
            
            <p>Here's everything included in your RankExpand transformation:</p>
            
            <ul class="bullets">
                <li><span class="bold">Complete Semantic SEO Audit</span> - We analyze your website through Google's own AI lens and show you exactly what's holding you back</li>
                <li><span class="bold">15 High-Impact Page Optimizations</span> - Every page becomes a lead-generation asset targeting your most profitable keywords</li>
                <li><span class="bold">Monthly Content Strategy</span> - 4 pieces of semantic-optimized content that build authority and drive traffic</li>
                <li><span class="bold">Authority Backlink Campaign</span> - 10 high-quality backlinks per month from real websites in your industry</li>
                <li><span class="bold">Dedicated SEO Specialist</span> - Your personal ranking expert who knows your business inside and out</li>
                <li><span class="bold">Monthly Progress Reports</span> - See exactly how your rankings, traffic, and leads are growing</li>
            </ul>
            
            <div class="guarantee-box">
                <h3>Our Iron-Clad Guarantee</h3>
                <p>If you don't see measurable ranking improvements within the first 90 days, we'll continue working for free until you do. No questions asked.</p>
            </div>
            
            <p><span class="bold caps">But you need to act fast...</span></p>
            
            <p>We only work with 50 businesses at a time. Any more and we can't deliver the personal attention your success demands.</p>
            
            <p>Right now, we have 7 spots left for January.</p>
            
            <p>And here's the thing about waiting...</p>
            
            <p>Every day you delay, your competitors are getting stronger. They're building more authority. Getting more reviews. Stealing more customers.</p>
            
            <p>The longer you wait, the harder it becomes to catch up.</p>
            
            <a href="#audit" class="cta-primary" id="audit">Claim Your Free SEO Audit Before It's Gone</a>
        </div>
    </section>

    <!-- FAQ SECTION -->
    <section class="section faq-section">
        <div class="container">
            <h2>Questions Smart Business Owners Ask</h2>
            
            <div class="faq-item">
                <div class="faq-question">Q: "This sounds expensive. What if I can't afford it?"</div>
                <p>Here's the reality: You can't afford NOT to do this. Every month you stay invisible on Google costs you thousands in lost revenue. One new customer typically pays for several months of our service. Plus, we start with a FREE audit so you can see the opportunity before investing a penny.</p>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Q: "How do I know this isn't just another SEO gimmick?"</div>
                <p>Because we're using Google's own technology. This isn't some black-hat trick or temporary loophole. We're literally using the same AI Google uses to understand websites. It's like having Google's algorithm tell you exactly what it wants to see.</p>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Q: "I've been burned by SEO agencies before. How is this different?"</div>
                <p>Most agencies use outdated tactics from 2015. We use Google's 2025 technology. Most agencies give you generic strategies. We specialize exclusively in niche service businesses. Most agencies lock you into long contracts. We prove our value first with results, then earn your continued business.</p>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Q: "What if this doesn't work for my specific business?"</div>
                <p>Our Semantic Analysis Tool works for ANY business that wants to be found online. Whether you're an HVAC contractor, e-commerce seller, or professional service provider, Google's algorithm works the same way. We just adapt the strategy to your specific market and keywords.</p>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Q: "How long before I see results?"</div>
                <p>Most clients see ranking improvements within 4-6 weeks. Significant traffic increases typically happen within 90 days. But here's what's important: Every day you wait, your competitors get stronger. The best time to start was last year. The second best time is today.</p>
            </div>
            
            <p style="text-align: center; font-size: 1.2rem; margin-top: 3rem;">
                Ready to stop watching your competitors win and start dominating your market?
            </p>
            
            <div style="text-align: center;">
                <a href="https://rankexpand.com/semantic-branching-seo-audit" class="cta-primary">Get Your Free SEO Audit Now</a>
            </div>
        </div>
    </section>
</body>
</html>
