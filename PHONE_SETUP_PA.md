# JARVIS Android — phone-only setup (Punjabi)

## Eh ki hai?
Eh ik free starter web app hai. Basic commands te shortcuts bina API key de chalde ne. Open-ended AI chat layi Google Gemini API key di lod hai. Google de free-tier limits/availability badal sakde ne; “bilkul unlimited free” guarantee nahi.

## Sab ton asaan tareeka (phone te)
1. ZIP nu Android phone te download karke Files app naal extract karo.
2. `index.html` nu Chrome vich khol ke test kar sakde ho. Kujh phone/browser `file://` ton microphone jaan AI network requests block kar sakde ne.
3. App nu install hon varga home-screen icon den layi HTTPS hosting di lod hai. Phone-only option: GitHub Pages (free public website) use karo:
   - GitHub account banao/sign in karo.
   - New public repository banao, misal `jarvis-personal`.
   - Is folder de files repository de root vich upload karo.
   - Repository Settings → Pages → deploy from branch → `main` / root select karo.
   - GitHub tuhanu HTTPS page link devega. Chrome vich khol ke menu → “Add to Home screen” chuno.
   - Public repository vich API key kade vi upload na karo. Key sirf app de Settings vich local browser te pao.
4. Free Gemini key layi Google AI Studio vich API key banao: https://aistudio.google.com/app/apikey
5. Apni HTTPS JARVIS site khol ke ⚙ Settings vich key paste karo te Save dabao. Test: “Explain photosynthesis simply” jaan Punjabi vich koi sawaal.
6. Chrome site settings vich microphone permission allow karo.

## Security te limitations
- API key is browser di local storage vich save hundi hai; shared phone/browser te key na save karo. Settings vich “Remove saved key” naal hata sakde ho.
- AI prompts Google Gemini API nu bheje jande ne.
- Eh starter “Hey Jarvis” always-on wake-word listening nahi karda. Always-on listening layi native Android app, microphone/background permissions te battery restrictions handle karne painge.
- Phone actions limited shortcuts ne. App apne aap WhatsApp message send, calls confirm, jaan arbitrary settings change nahi kardi.
- Je Google free-tier available na hove jaan limits hit hon, API usage ruk sakdi hai; paid billing enable karan di lod ho sakdi hai, par tusi payment na karna chaho taan na karo.
