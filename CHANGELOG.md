# Changelog

سجل التغييرات

Tags: `v3.1-shrine`, `v3.2-shrine`.  
The release file is always `CleanYourTV-Shrine.apk`.

الوسوم: `v3.1-shrine` و`v3.2-shrine`.  
اسم ملف الإصدار دائمًا `CleanYourTV-Shrine.apk`.

## 3.2-shrine

versionCode 12.

### English

- Edit the featured dock from Launcher settings or by holding OK on a tile. The order is stored in the app, so a later theme refresh does not put the shrine row back.
- Hide an app from the launcher. Uninstall an app you installed. Delete a preinstalled app for this user through Network debugging on the TV itself (localhost only). Settings, the system UI, Play services, the Play Store, and this launcher stay protected. Restore a deleted app from the same place.
- Language: follow the system, English, or Arabic. Arabic uses a single Regular weight of Cairo, cut down to the letters this screen needs.
- About & updates shows the installed version and the list at `https://api.github.com/repos/Nighsuh/cleanyourtv-shrine/releases`. You can download and install the version you pick. The file is `https://github.com/Nighsuh/cleanyourtv-shrine/releases/download/<tag>/CleanYourTV-Shrine.apk`. An older version does not install over this one; uninstall first. Uninstalling also deletes a file this screen downloaded.
- A clock widget is hosted only after one has been added. A fresh home screen does not start a widget host.
- The release build is shrunk with R8 and resource shrinking. Debugging no longer carries a TLS library. The shrine wallpaper is decoded off the first frame and scaled to the screen.
- Launcher settings, reached with the D-pad, opens the dock editor, top-bar chips (Settings stays on), wallpaper and dim, a grey Themes · Coming soon row until the online index lists another theme, screensaver and sleep, prayer times with place and method, widgets (none until you add one, prayer times first), date and time, the default Home choice, language, and About & updates.
- Date and time: 12-hour or 24-hour, seconds, a few date shapes, Gregorian only, Hijri only, or both, and a Hijri shift of −2 to +2 days (Umm al-Qura). The zone list starts with Asia/Riyadh. Setting the TV’s zone uses the system call, then debugging, then Date settings.
- Prayer times is a page, a module card, and a home widget. The default place is Dammam and the default method is Jafari.
- The shrine dream is the screensaver: a clock, a slideshow every 5 seconds, or the current wallpaper.
- Hold OK on a tile to hide, uninstall, or delete. Delete and restore ask with the debugging popup: Take me there, Show steps only, Cancel.
- The launcher icon and the leanback banner are the shrine picture with a white home mark and a gold edge.

### العربية

- يمكن تعديل صف التطبيقات المميزة من إعدادات الشاشة أو بالضغط المطوّل على موافق. يُحفظ الترتيب داخل التطبيق، فلا تعيد خلفية المزار الصف كما كان.
- إخفاء تطبيق من الشاشة، وإلغاء تثبيت ما ثبّته المستخدم، وحذف تطبيق مدمج لهذا المستخدم عبر تصحيح الشبكة على التلفاز نفسه. تبقى الإعدادات وواجهة النظام وخدمات غوغل ومتجر بلاي وهذه الشاشة محمية. يمكن استعادة تطبيق حُذف من المكان نفسه.
- اللغة: لغة النظام أو الإنجليزية أو العربية. العربية تستخدم وزنًا واحدًا من خط القاهرة، مقتصرًا على الحروف التي تحتاجها الشاشة.
- «حول الشاشة والتحديثات» يعرض الإصدار المثبّت والقائمة من `https://api.github.com/repos/Nighsuh/cleanyourtv-shrine/releases`. يمكن تنزيل الإصدار الذي تختاره وتثبيته. الملف هو `https://github.com/Nighsuh/cleanyourtv-shrine/releases/download/<tag>/CleanYourTV-Shrine.apk`. الإصدار الأقدم لا يُثبَّت فوق هذا؛ أزل التثبيت أولًا. إزالة التثبيت تحذف أيضًا أي ملف نزّلته هذه الشاشة.
- لا تُستضاف ساعة مصغّرة إلا بعد إضافتها. الشاشة الجديدة لا تشغّل مستضيف المصغّرات.
- بناء الإصدار مُصغَّر. تصحيح الشبكة لم يعد يحمل مكتبة تشفير. صورة المزار تُفك خارج الإطار الأول وتُصغَّر إلى مقاس الشاشة.
- إعدادات الشاشة تفتح محرّر الصف، واختصارات الشريط العلوي (الإعدادات تبقى)، والخلفية والتعتيم، وصف «السمات · قريبًا» الرمادي حتى يضم الفهرس سمة أخرى، وحافظة الشاشة والنوم، ومواقيت الصلاة مع المكان وطريقة الحساب، والمصغّرات (لا شيء حتى تُضاف، ومواقيت الصلاة أولًا)، والتاريخ والوقت، والشاشة الرئيسية الافتراضية، واللغة، وحول الشاشة والتحديثات.
- التاريخ والوقت: ١٢ أو ٢٤ ساعة، والثواني، وأشكال للتاريخ، وميلادي فقط أو هجري فقط أو الاثنان، وإزاحة هجرية من −٢ إلى +٢ (أم القرى). قائمة المناطق تبدأ بآسيا/الرياض.
- مواقيت الصلاة صفحة وبطاقة ووحدة مصغّرة. المكان الافتراضي الدمام والطريقة الجعفري.
- حافظة الضريح هي حافظة الشاشة: ساعة، أو عرض صور كل ٥ ثوانٍ، أو الخلفية الحالية.
- الضغط المطوّل على موافق فوق أيقونة يخفي أو يلغي التثبيت أو يحذف. الحذف والاستعادة يطلبان نافذة التصحيح: خذني إلى هناك، أظهر الخطوات فقط، إلغاء.
- أيقونة الشاشة ولافتة التلفاز صورة المزار بعلامة منزل بيضاء وحافة ذهبية.

### Release notes

English: CleanYourTV 3.2-shrine edits the featured dock, hides or removes apps through this TV’s own debugging, and adds Arabic and English. About & updates can install a newer `CleanYourTV-Shrine.apk` from this repo. An older build will not replace this one until you uninstall.

العربية: الإصدار 3.2-shrine يعدّل صف التطبيقات المميزة، ويخفي التطبيقات أو يزيلها عبر تصحيح هذا التلفاز، ويضيف العربية والإنجليزية. من «حول الشاشة والتحديثات» يمكن تثبيت ملف `CleanYourTV-Shrine.apk` الأحدث. الإصدار الأقدم لا يحل محل هذا حتى تزيل التثبيت.

## 3.1-shrine

The first shrine build, on CleanYourTV v3.1.0.

أول بناء للمزار، على CleanYourTV الإصدار v3.1.0.

### English

- The Imam Hussain shrine theme is inside the APK and is applied the first time Home starts, if the theme folder has no `config.json` yet.
- Fixed wallpaper, dim 45%, dock opacity 70%, glass rim, six columns.
- Dock order: YouTube, Shahid, Netflix, Prime Video, OSN+, Disney+. An app that is not installed is skipped.
- Signed with a private release key. It does not set itself as the default launcher and it does not disable other packages.
- A theme already on the TV is left as it is.

### العربية

- خلفية مزار الإمام الحسين داخل ملف التثبيت، وتُطبَّق عند أول تشغيل إن لم يكن في مجلد السمة ملف `config.json`.
- خلفية ثابتة، تعتيم ٤٥٪، شفافية الصف ٧٠٪، حافة زجاجية، وستة أعمدة.
- ترتيب الصف: يوتيوب، شاهد، نتفليكس، برايم فيديو، أو إس إن بلس، ديزني+. التطبيق غير المثبّت يُتخطى.
- التوقيع بمفتاح إصدار خاص. لا يجعل نفسه الشاشة الافتراضية ولا يعطّل حزمًا أخرى.
- السمة الموجودة أصلًا على التلفاز تُترك كما هي.
