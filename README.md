# Discord Message Cleaner · منظّف رسائل Discord

Scan a Discord DM or channel, pick users, preview and bulk-delete their messages, with verification, rate-limit handling, and **resume after stop**. UI in **English / العربية**.

افحص محادثة أو قناة في Discord، اختر المستخدمين، عاين الرسائل واحذفها مع التحقق والتعامل مع حدود المعدل و**المتابعة بعد الإيقاف**. الواجهة بالعربية والإنكليزية.

> ⚠️ **Read first / اقرأ أولاً.** The extension automates your *own* Discord account using your session token. Discord's Terms of Service restrict automating user accounts, so use it at your own risk (heavy use on a main account could get it limited). The token never leaves your browser.
> الإضافة تؤتمت حسابك الشخصي باستخدام توكن الجلسة، وشروط Discord تقيّد أتمتة الحسابات، فالاستخدام على مسؤوليتك. التوكن لا يغادر متصفحك.

## Download · التحميل

Get the zip for your browser from **[Releases](https://github.com/iraqswat09/discord-message-cleaner/releases)**.
حمّل الملف المناسب لمتصفحك من صفحة **[Releases](https://github.com/iraqswat09/discord-message-cleaner/releases)**.

## Install · التثبيت

**Chrome / Edge / Brave / Opera**
1. Unzip the file. / فك الضغط.
2. Open `chrome://extensions` (or `edge://extensions`). / افتح صفحة الإضافات.
3. Enable **Developer mode**. / فعّل **وضع المطوّر**.
4. Click **Load unpacked** and pick the unzipped folder. / اضغط **Load unpacked** واختر المجلد.

**Firefox**
Use the signed `.xpi` file from Releases and open it in Firefox. / استخدم ملف `.xpi` الموقّع من Releases وافتحه في Firefox.

## Usage · الاستخدام

1. Open **discord.com** (desktop mode) and go to a DM or channel. / افتح discord.com وادخل إلى محادثة أو قناة.
2. Click the round 🗑 button (bottom-right). Switch language with **EN / ع**. / اضغط زر 🗑 وغيّر اللغة بزر **EN / ع**.
3. **Scan my messages (fast)** or **Full scan** (all users). / **فحص رسائلي** أو **فحص كامل**.
4. Select users, check the preview, press **Start**. / اختر المستخدمين ثم **ابدأ**.
5. **Stop** any time; **Start** again continues with what is left, no re-scan needed (unless the page is reloaded). / **إيقاف** في أي وقت، و**ابدأ** يكمل من الباقي فقط.

Deletion is permanent. Deleting other people's messages needs **Manage Messages**. / الحذف نهائي، وحذف رسائل الآخرين يتطلب صلاحية Manage Messages.

## Privacy · الخصوصية

The extension runs only on `discord.com`. It reads your Discord session token locally and uses it only to call Discord's own API. It collects nothing and sends no data to anyone else. The only thing stored is your language choice.

تعمل الإضافة على `discord.com` فقط، وتقرأ التوكن محلياً وتستخدمه فقط للتواصل مع Discord. لا تجمع أي بيانات ولا ترسل شيئاً لأي جهة أخرى. المخزَّن الوحيد هو اللغة التي اخترتها.

## License
MIT
