# 🧠 بطّل تشرح لـ Claude نفس الكلام كل مرة

كل مرة تفتح Chat جديد وتقعد تشرح: أنا مين، وبشتغل في إيه، وعملائي مين، وعايز الرد إزاي… ده وقت بيضيع كل يوم.
الحل اسمه **Projects**: بتشرح مرة واحدة، وكل Chat جوه الـ Project بيبدأ وهو فاهم كل حاجة.

هنا هتلاقي **الـ Instructions اللي أنا كاتبها بالظبط** لكل Project، ومعاها إيه الملفات اللي ترفعها، وشرح كل حاجة بتعمل إيه.

> 💡 انسخ الـ Instructions زي ما هي، وغيّر بس الحاجات اللي بين `[ ]`.

---

## 🔌 الأول: اعمل الـ Project

1. افتح Claude وادخل على **Projects** واعمل Project جديد، وسمّيه باسم الشغلانة (مثلاً: المحتوى).
2. في الـ **Instructions** الخاصة بالـ Project، الزق الـ Template المناسب من تحت بعد ما تعدّله.
3. ارفع الملفات المهمة في الـ **Knowledge** بتاعة الـ Project (هتلاقي تحت كل Template إيه الملفات اللي ترفعها).

وبعد كده افتح أي Chat **جوه الـ Project** نفسه، مش Chat عادي برّه.

لو احتجت مساعدة في الخطوات: https://support.claude.com

---

## 🏗️ أنا بقسّمها إزاي؟

| Project | بستخدمه في إيه |
|---|---|
| ✍️ المحتوى | سكريبتات الريلز، الـ Hooks، الكابشنز |
| 🤝 العملاء | الرد على العملاء، العروض، متابعة كل عميل |
| 💼 البيزنس | قرارات، أسعار، خطط، تحليل أرقام |

قاعدة بسيطة: **Project لكل شغلانة**، مش Project واحد لكل حاجة. كل ما الـ Project يكون مركّز، الرد بيبقى أدق.

---

## ✍️ 1. Project المحتوى (ده اللي السكريبت ده اتكتب منه)

استخدمه لأي حاجة محتوى: سكريبتات، Hooks، كابشنز، أفكار.

```
## Who I am
I'm [اسمك], [وظيفتك] at [اسم البيزنس]. I create short-form video content (Instagram Reels / TikTok) about [المجال بتاعك] for [الجمهور بتاعك، مثلاً: أصحاب البيزنس الصغير في مصر].

## Language & voice
- Write all scripts in Egyptian Arabic (عامية مصرية), spoken style — like I'm talking to a friend, not reading.
- Keep technical terms in English the way Egyptians say them (e.g. الـ Automation، الـ Prompt).
- Short sentences. No formal Arabic (فصحى). No corporate tone.
- Never use these words/phrases: [كلمات مش بتحبها]

## Script format (always follow this)
1. 3 hook options (one line each, max ~12 words, start with the pain or a surprising result)
2. The script: 30–45 seconds when spoken, one idea only
3. One personal example from my own work
4. CTA: "اكتب [KEYWORD] في الكومنتات، وهبعتلك [الحاجة]"

## Rules
- One reel = one idea. If the topic is big, suggest splitting it into a series.
- Prefer concrete steps over theory.
- Don't invent stats, numbers, or product features. If unsure, say so.
- Before writing, check the files in this project for my style and past scripts.
```

**بيعمل إيه؟** بيخلي Claude يكتب بنفس صوتك ونفس الفورمات كل مرة، من غير ما تشرح الستايل من الأول.

**ارفع في الـ Knowledge:**
- 5–10 سكريبتات قديمة نجحت (أمثلة على صوتك)
- ملف فيه الجمهور بتاعك ومشاكلهم
- ليستة الـ Content Pillars (المواضيع الأساسية اللي بتتكلم فيها)

**نصيحة:** كل ما سكريبت ينجح، ضيفه للملفات. الـ Project بيتحسن مع الوقت.

---

## 🤝 2. Project العملاء

استخدمه للرد على العملاء، كتابة العروض، ومتابعة الشغل.

```
## Who I am
I'm [اسمك] from [اسم البيزنس]. We offer [الخدمات بتاعتك] to [نوع العملاء].

## How to help me
- Draft replies to clients in the same language they wrote in (Egyptian Arabic or English).
- Tone: professional but warm, short, clear next step at the end of every message.
- For proposals, use the structure in the "proposal-template" file.
- Use ONLY the prices in the "pricing" file. Never invent a price or a discount.

## Rules
- Draft only. Do NOT send anything — I review and send myself.
- Never promise a deadline or a feature I didn't confirm. If missing, ask me first.
- If a client message is angry or unclear, first summarize what they actually want in one line, then draft the reply.
- Flag anything that sounds like scope creep (طلب زيادة عن الاتفاق).
```

**بيعمل إيه؟** بيكتبلك ردود وعروض بأسعارك الحقيقية وبأسلوبك، ويطلعلك أي طلب زيادة عن الاتفاق.

**ارفع في الـ Knowledge:**
- ملف الأسعار والباقات
- Template العرض (Proposal)
- أسئلة العملاء المتكررة وردودك عليها
- 2–3 عروض قديمة اتقبلت

**نصيحة:** متحطش بيانات حساسة للعملاء (باسوردات، أرقام حسابات) في الملفات.

---

## 💼 3. Project البيزنس

استخدمه للتفكير، القرارات، والتخطيط.

```
## Context
I run [اسم البيزنس], a [نوع البيزنس] in [البلد]. Team: [عدد الفريق وأدوارهم]. Current stage: [مثلاً: أول سنة، عندنا X عميل].
Current goals: [أهم 2–3 أهداف دلوقتي].

## How to help me
- Be direct. Give me your honest opinion, including when you think I'm wrong.
- When I ask for a decision, give: options → pros/cons → your recommendation → the first step.
- Use numbers from the files in this project. If data is missing, tell me what you need.
- Keep answers short unless I ask for detail.

## Rules
- Don't make up market numbers or stats.
- Think about Egyptian market context (pricing, payment habits) when relevant.
```

**بيعمل إيه؟** بيبقى زي شريك بيفهم وضع البيزنس، ويديك رأي صريح مبني على أرقامك.

**ارفع في الـ Knowledge:**
- ملف عن البيزنس (خدماتكم، الفريق، الأهداف)
- الأسعار والتكاليف
- أي أرقام أو تقارير شهرية

---

## 🧩 4. Template فاضي لأي Project تاني

لو عندك شغلانة تانية (Project لعميل معين، كورس بتعمله، إلخ):

```
## Who I am & what this project is for
[إنت مين + الـ Project ده معمول لإيه في سطرين]

## What I usually ask for here
[أكتر 3 حاجات هتطلبها في الـ Project ده]

## Output format
[عايز الرد يكون شكله إزاي: نقط؟ جدول؟ طول معين؟ لغة؟]

## Rules
- [حاجة لازم يعملها دايماً]
- [حاجة ممنوع يعملها]
- Always check the files in this project before answering.
- If something is missing or unclear, ask me instead of guessing.
```

---

## 🇪🇬 تقدر تكتب الـ Instructions بالمصري كمان

مش لازم إنجليزي، Claude فاهم المصري كويس:

```
أنا [اسمك]، وبعمل محتوى عن [المجال] لـ [الجمهور].
اكتبلي دايماً بالعامية المصرية، جمل قصيرة، كأني بكلم صاحبي.
أي سكريبت يبقى: 3 Hooks، وبعدين سكريبت 30–45 ثانية، وفي الآخر CTA.
متألفش أرقام ولا معلومات. ولو مش متأكد قولي.
وقبل ما تكتب، بص على الملفات اللي في الـ Project عشان تعرف الستايل بتاعي.
```

---

## ⚠️ نصايح مهمة

- **الـ Chat لازم يبقى جوه الـ Project.** لو فتحت Chat عادي برّه، مش هيشوف الـ Instructions ولا الملفات.
- **ابدأ بسيط وحسّن مع الوقت.** كل ما تلاقي نفسك بتصحح نفس الحاجة، ضيفها في الـ Instructions.
- **الأمثلة أقوى من الوصف.** ملف فيه 5 سكريبتات بتوعك أحسن من 10 سطور بتوصف الستايل.
- **متحطش بيانات حساسة** (باسوردات، أرقام حسابات، بيانات عملاء خاصة) في الملفات.
- **راجع أي حاجة قبل ما تبعتها.** Claude بيكتب Draft، وإنت اللي بتقرر.

---

## 🚀 الخلاصة

| قبل | بعد |
|---|---|
| كل Chat تشرح من الأول | بتشرح مرة واحدة بس |
| الرد عام ومش شبهك | الرد بصوتك وبالفورمات بتاعتك |
| بتنسى تقوله الأسعار أو التفاصيل | الملفات موجودة وهو بيرجعلها |
| Chat واحد فيه كل حاجة ملخبطة | Project لكل شغلانة ومنظم |

---

لو استفدت، تابعني عشان فيه Prompts وأتمتة أكتر جاية 🔥

**Steven Ayman — Vida AI**
