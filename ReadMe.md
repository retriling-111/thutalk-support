# 📱 ThuTalk Ecosystem (Full Documentation)

**ThuTalk** သည် **Django Framework** ကို အခြေခံ၍ တည်ဆောက်ထားသော ခေတ်မီ Social Media Platform တစ်ခုဖြစ်သည်။ ဤ platform ကို Web browser များတွင်သာမက Android devices များတွင်ပါ **Web View Architecture** ဖြင့် အဆင်ပြေချောမွေ့စွာ အသုံးပြုနိုင်ရန် ဖန်တီးထားပါသည်။ ဤ Project သည် အချိန်နှင့်တပြေးညီ ဆက်သွယ်ပြောဆိုနိုင်မှု (Real-time Communication) နှင့် အသုံးပြုသူများအကြား ချိတ်ဆက်မှုကို အဓိကထား၍ တည်ဆောက်ထားခြင်းဖြစ်သည်။

---

## 🚀 Detailed Features & Functions

### 1. Account & Security Management
*   **Password Recovery:** အသုံးပြုသူများ Login ဝင်ရန် အခက်အခဲရှိပါက Email verification သို့မဟုတ် လုံခြုံသော လုပ်ဆောင်ချက်များမှတစ်ဆင့် စကားဝှက်ကို ပြန်လည်ရယူနိုင်သည်။
*   **Delete Account:** အသုံးပြုသူ၏ ကိုယ်ရေးအချက်အလက် လုံခြုံမှုကို အလေးထားသောကြောင့် မိမိ၏ account နှင့် data များအားလုံးကို platform ပေါ်မှ အပြီးတိုင် ဖျက်သိမ်းနိုင်သော function ပါဝင်သည်။
*   **Privacy Settings:** မိမိ၏ profile အချက်အလက်များနှင့် privacy configuration များကို စိတ်ကြိုက် ထိန်းချုပ်နိုင်သည်။

### 2. Social & Connectivity
*   **Real-time Messaging:** Django ၏ လုံခြုံစိတ်ချရသော server logic ကို အသုံးပြု၍ အသုံးပြုသူများအကြား အချိန်နှင့်တပြေးညီ စာပို့ဆက်သွယ်နိုင်သည်။
*   **User Discovery:** အနီးနားရှိ သို့မဟုတ် စိတ်ဝင်စားမှုတူသော အသုံးပြုသူအသစ်များကို ရှာဖွေနိုင်ပြီး သူငယ်ချင်းအဖြစ် ချိတ်ဆက်နိုင်သည်။
*   **Profile Management:** မိမိ၏ Bio၊ ဓာတ်ပုံ နှင့် စိတ်ဝင်စားမှုများကို စိတ်ကြိုက် ပြင်ဆင်နိုင်သည်။

### 3. Smart Search & Navigation
*   **Integrated Search Engine:** FAQ များ၊ အသုံးပြုသူများ နှင့် platform ဆိုင်ရာ အချက်အလက်များကို keyword ရိုက်ရုံဖြင့် လျင်မြန်စွာ ရှာဖွေနိုင်သည်။
*   **Filter Logic:** Search bar တွင် 'password' သို့မဟုတ် 'android' ဟု ရိုက်နှိပ်လိုက်ပါက သက်ဆိုင်ရာ category များသာ filter ဖြစ်၍ ပေါ်လာမည်ဖြစ်သည်။

### 4. Advanced System Features
*   **AI Project Assistant:** အသုံးပြုသူများအား platform အသုံးပြုရာတွင် ကူညီပေးမည့် AI assistant ပါဝင်သည်။
*   **Official Certification:** ThuTalk App သည် APKPure တွင် တရားဝင် Certified ဖြစ်ပြီးသား Platform တစ်ခုဖြစ်သည်။

---

## 🎨 UI/UX Design (Adaptive Display)

Dark Mode နှင့် Light Mode နှစ်မျိုးလုံးတွင် အမြင်အာရုံကို မထိခိုက်စေရန်နှင့် စာသားများ ပျောက်ကွယ်မသွားစေရန် **Tailwind CSS** ကို အသုံးပြု၍ Color Contrast များကို သေချာစွာ ညှိနှိုင်းထားပါသည်။

*   **Light Mode:** အေးမြသော အဖြူရောင်နောက်ခံနှင့် ပြတ်သားသော စာသားများကို အသုံးပြုထားသည်။
*   **Dark Mode:** မျက်စိမပူစေရန် Deep Gray/Black နောက်ခံပေါ်တွင် ပိုမိုတောက်ပသော အပြာရောင် (Accent color) နှင့် အဖြူရောင်စာသားများကို သုံးထားသောကြောင့် color ပျောက်သွားခြင်း သို့မဟုတ် စာသားဖတ်မရခြင်းများ မရှိစေရန် ပြင်ဆင်ထားသည်။

---

## 🛠️ Technical Stack & Environment

*   **Backend:** Django (Python)
*   **Frontend:** HTML5, Tailwind CSS, JavaScript (Vanilla/React)
*   **Mobile Container:** Android WebView (Java/Kotlin)
*   **Database:** PostgreSQL / SQLite
*   **Dev Setup:** macOS (M1 Air) with Zsh Terminal

---

## ⚙️ Project Structure

| Component | Responsibility |
| :--- | :--- |
| **Django Server** | API handling, Authentication, and Database management |
| **Web View App** | Android native container for displaying the web interface |
| **Assets Manager** | Handling media uploads and static CSS/JS files |
| **Security** | CSRF protection and secure Django authentication |

---

## 👨‍💻 Development Team
*   **Lead Developer:** Nyi Phone Khant (RetriLing)

---

## 📲 Installation & Support

1.  **Web Access:** [khantdev.pythonanywhere.com](https://khantdev.pythonanywhere.com)
2.  **Android App:** **APKPure** မှတစ်ဆင့် **ThuTalk** ဟု ရှာဖွေ၍ download ရယူနိုင်သည်။
3.  **Support:** ပြဿနာတစ်စုံတစ်ရာရှိပါက Telegram [@Retriling](https://t.me/Retriling) သို့ တိုက်ရိုက် ဆက်သွယ်မေးမြန်းနိုင်ပါသည်။

---
© 2026 ThuTalk Ecosystem. Designed and Developed in Yangon, Myanmar။