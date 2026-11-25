AI VIDEO GENERATE — STARTER PROJECT
==================================

यह पहला working starter version है। इसमें:
- Dark Premium black/purple/blue design
- Text to Video prompt draft
- Image to Video prompt draft
- Story draft template
- Script draft template
- Voiceover text preparation
- AI Image prompt draft
- Drafts इस device के browser में localStorage से save होते हैं
- Basic PWA/offline cache support

महत्वपूर्ण सीमाएँ:
यह अभी वास्तविक AI video/image/audio generation नहीं करता।
कोई AI API, login, cloud sync, payment या premium subscription जुड़ा नहीं है।
इन सुविधाओं के लिए सुरक्षित backend और किसी AI provider की अनुमति/उपलब्ध free tier चाहिए।
इस starter को production-ready या Play Store-ready न समझें।

मोबाइल पर टेस्ट:
1. ZIP को extract करें।
2. सभी files एक ही folder में रखें।
3. इस folder को किसी static hosting पर publish करना होगा (उदाहरण: GitHub Pages)।
4. Hosting का HTTPS link Chrome में खोलें।
5. Chrome menu > Add to Home screen / Install app चुनें।

ध्यान:
सिर्फ ZIP को फोन में खोलने से PWA install नहीं होगा; service worker के लिए HTTPS hosting जरूरी है।
Play Store पर डालने से पहले native Android packaging, privacy policy, data safety, content moderation,
billing, testing और Google Play requirements पूरी करनी होंगी।
