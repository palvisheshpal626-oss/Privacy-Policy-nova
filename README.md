<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Privacy Policy</title>
<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: linear-gradient(135deg, #0f172a, #1e293b);
  color: white;
}
header {
  text-align: center;
  padding: 40px 20px;
}
header h1 {
  font-size: 32px;
}
header p {
  opacity: 0.7;
}
.container {
  max-width: 900px;
  margin: auto;
  padding: 20px;
}
.card {
  background: rgba(255,255,255,0.05);
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 15px;
  backdrop-filter: blur(10px);
  transition: 0.3s;
  opacity: 0;
  transform: translateY(30px);
}
.card:hover {
  transform: scale(1.03);
  background: rgba(255,255,255,0.1);
}
.card.show {
  opacity: 1;
  transform: translateY(0);
}
footer {
  text-align: center;
  padding: 20px;
  opacity: 0.6;
}
</style>
</head>
<body>

<header>
  <h1>Privacy Policy</h1>
  <p>Last updated: February 22, 2026</p>
</header>

<div class="container">

<div class="card">
<h2>Introduction</h2>
<p>At Privacy Policy
Last updated: February 22, 2026

At Nova AI Video & Image Maker, we prioritize your privacy. This Privacy Policy describes how we collect, use, and handle your information when you use our mobile application.

1. Information We Collect
- User-Provided Content: We collect images and videos you upload to our service for processing (e.g., upscaling, background removal).
- Usage Data: We collect information about how you interact with the app, such as features used and time spent.
- Device Information: We collect information about your mobile device, including model, operating system version, and unique device identifiers.
- Advertising Data: We may collect advertising identifiers (like IDFA or GAID) to serve personalized ads.

2. How We Use Your Data
- AI Processing: Images are sent to our AI processing partners to perform the requested tasks (Generation, Upscaling, BG Removal).
- Cloud Storage: Processed media is stored in our secure Supabase storage buckets to allow you to access your history and download results.
- Monetization: We use data to serve rewarded and banner advertisements via AdMob and Unity Ads.
- Improvements: Analytics data helps us fix bugs and improve the AI models and user interface.

3. Third-Party Services
- Supabase: For user authentication, database management, and cloud media storage.
- Replicate API: For high-end AI image and video generation and processing.
- Google AdMob & Unity Ads: For serving advertisements and managing our reward system.

4. Data Storage and Retention
- Your uploaded and generated images are stored in protected Supabase "media" buckets.
- You can view and manage your generation history within the app.
- We retain data as long as necessary to provide specialized AI services to you.

5. Your Rights
- Access your data
- Request deletion
- Opt-out of personalized ads

6. Security
We use industry-standard security measures.

7. Contact
Email: smart.tech.clubvs@gmail.com.</p>
</div>

<div class="card">
<h2>1. Information We Collect</h2>
<p>User-Provided Content: Images and videos you upload.</p>
<p>Usage Data: Features used and time spent.</p>
<p>Device Information: Model, OS version, identifiers.</p>
<p>Advertising Data: Ad identifiers like IDFA/GAID.</p>
</div>

<div class="card">
<h2>2. How We Use Your Data</h2>
<p>AI Processing: For generation, upscaling, BG removal.</p>
<p>Cloud Storage: Stored in Supabase buckets.</p>
<p>Monetization: Ads via AdMob & Unity.</p>
<p>Improvements: Analytics for better performance.</p>
</div>

<div class="card">
<h2>3. Third-Party Services</h2>
<p>Supabase: Auth & storage</p>
<p>Replicate API: AI processing</p>
<p>AdMob & Unity Ads: Advertising</p>
</div>

<div class="card">
<h2>4. Data Storage and Retention</h2>
<p>Images stored in Supabase media buckets.</p>
<p>History accessible in app.</p>
<p>Data retained as needed for service.</p>
</div>

<div class="card">
<h2>5. Your Rights</h2>
<p>Access your data</p>
<p>Request deletion</p>
<p>Opt-out of ads</p>
</div>

<div class="card">
<h2>6. Security</h2>
<p>We use industry-standard security measures.</p>
</div>

<div class="card">
<h2>7. Contact</h2>
<p>Email: smart.tech.clubvs@gmail.com</p>
</div>

</div>

<footer>
  © 2026 Nova AI
</footer>

<script>
const cards = document.querySelectorAll('.card');

const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add('show');
    }
  });
});

cards.forEach(card => {
  observer.observe(card);
});
</script>

</body>
</html>
