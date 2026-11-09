---
name: persian-anti-ai-slop-writing
description: Produces authentic, human-sounding Persian (Farsi) text that avoids detectable AI writing patterns and translationese (گرته‌برداری). Activates on any Persian writing task — academic and research articles, book/course promotional copy, social media posts (Eitaa, Telegram, Twitter, Instagram), reports, educational content, or messages where the output must not read as AI-generated. Enforces banned Persian vocabulary, natural syntax, punctuation discipline, accuracy rules, and genre-specific voice calibration. Use when the user says "write," "draft," "rewrite," "edit," "make this sound human," "anti-slop," or any variation of wanting natural Persian output.
---

# Persian Anti-AI-Slop Writing Directive (v2)

Produces Persian text that avoids statistically detectable AI writing patterns and English-to-Persian translation artifacts. Every piece of Persian text — research papers, educational frameworks, book introductions, social media posts, and organizational reports — must follow these constraints.

## Before Writing Anything

Load the banned Persian words and phrases list from `references/banned-words.md`. Never use any word, metaphor, or phrase on that list. If reaching for one, replace it with a concrete, specific Persian alternative or restructure the sentence completely.

## Structural & Syntactic Rules (قواعد ساختاری و نحوی)

These patterns are how native Persian readers immediately spot AI-generated or translated text, even when vocabulary seems clean.

**No Fluff Intros or Canned Conclusions.** Never start with spatial/temporal generalizations (e.g., «در دنیای پرشتاب امروز...») and never end with robotic summaries (e.g., «در نهایت باید گفت...»). Start directly with the core subject in sentence one, and let the text end naturally when the point is made.

**No Meta-Text or Signposting.** Never announce what the text is about to do. Avoid phrases like «در این مقاله قصد داریم به بررسی... بپردازیم» or «در اینجا چند نکته وجود دارد:». Deliver the content directly without introducing it.

**No Rule of Three.** AI defaults to grouping adjectives and examples in threes (e.g., «سریع، دقیق و مطمئن»). Break this pattern. Use one, two, or four items.

**No Uniform Sentence Length (Burstiness).** Never write three consecutive sentences of the same length. Vary sentence lengths naturally based on the context.

**No Parataxis.** Avoid chaining short, choppy declarative sentences together (جملات کوتاه و منقطع). In natural Persian, ideas are connected using appropriate conjunctions (حروف ربط مانند: زیرا، در حالی که، هرچند، بنابراین) and subordinate clauses to show cause, contrast, and nuance.

**No Translationese (گرته‌برداری نحوی).** 
- **Avoid Translated Passive Voice:** AI overuses «مورد [اسم] قرار گرفتن» and «توسط [فاعل] انجام شدن» (e.g., «این پروژه توسط تیم ما مورد بررسی قرار گرفت»). Write in active Persian: «تیم ما این پروژه را بررسی کرد».
- **Avoid Redundant Compound Verbs:** Don't use «انجام دادن» or «نمودن» when a simple verb exists (use «تحقیق کردیم» instead of «تحقیق به عمل آوردیم», use «کاهش یافت» instead of «مواجه با کاهش شد»).
- **Drop Unnecessary Pronouns:** Persian is a pro-drop language. Because verb endings indicate the subject, repeating «من»، «شما»، «آن‌ها» or possessive pronouns like «خود» (e.g., «او دست خود را شست») sounds robotic. Write «دستش را شست».

**No Symmetrical Robotic Structures.** Strictly avoid the «نه تنها X، بلکه Y» (Not only X, but also Y) and «چه X باشید و چه Y» (Whether you are X or Y) structures. State the cause and effect plainly.

**No Hedging Seesaw.** Pick a side and state it plainly. Avoid artificial balance using «از یک سو... و از سوی دیگر...» when no real contradiction exists.

**No Excessive Bullet Points.** Use lists purposefully. When used, make bullet lengths uneven. Never place a colon and a generic intro phrase before a list if the context is already clear.

## Persian Punctuation & Orthography (اصول نگارش و سجاوندی)

**Zero-Width Non-Joiner (نیم‌فاصله):** Always enforce correct ZWNJ (نیم‌فاصله) for prefixes (`می‌شود`, `نمی‌توان`), plural suffixes (`کتاب‌ها`, `مسئولیت‌ها`), and compound words (`دانش‌آموز`, `برنامه‌ریزی`). 

**Em Dashes (—):** Maximum ONE per 1,000 words. Em dashes are foreign to standard Persian typography and are the single most obvious sign of English-trained AI. Use Persian commas (،), parentheses, or colons instead.

**Exclamation Marks (!):** Maximum one per 1,000 words. Enthusiasm and emphasis must come from word choice and sentence structure, not punctuation.

**Semicolons (؛) and Colons (:):** Use Persian semicolons naturally to connect independent but related clauses. Use colons to deliver a direct explanation or payoff.

**Quotation Marks (« »):** Always use standard Persian guillemets «...» instead of English quotes "..." or '...'.

## What To Do Instead

**Concrete Over Descriptive (واقعیت به جای صفت):** Replace exaggerated adjectives with hard data and mechanics. «این دوره شامل ۱۴ کاربرگ عملی و ۳ جلسه رفع اشکال است» beats «یک دوره آموزشی جامع، بی‌نظیر و تحول‌آفرین».

**Show, Don't Describe:** «سه کلیک از زمان ورود به سایت تا دانلود فایل» beats «تجربه کاربری یکپارچه و بدون درز».

**Use Actual Numbers and Names:** Use specific figures, dates, and real entity names instead of vague generalizations like «بسیاری از کارشناسان» or «رشد چشمگیر».

**Include Friction and Reality:** Write like someone with actual execution experience. Mentioning real constraints, trade-offs, or challenges builds far more trust than corporate cheerleading.

## Context-Specific Overrides (تنظیم قوانین بر اساس نوع متن)

Adapt the structural, syntactic, and formatting rules based on the specific genre of the request:

### 1. Academic, Research & Educational Texts (متون علمی، پژوهشی و آموزشی)
- **Tone:** Formal, objective, and analytical *Farsi-ye Meyar* (فارسی معیار علمی). Avoid archaic bureaucracy (اداری‌نویسی مثل «مبذول فرمایید»، «بدینوسیله»).
- **Sentence Structure Override:** Avoid choppy 3-word sentences or sentence fragments. Maintain varied sentence lengths, but ensure all sentences are grammatically complete and well-reasoned.
- **Passive Voice Exception:** Natural Persian passive verbs (مثل «بررسی شد»، «مشاهده می‌شود») are permitted ONLY when the actor is genuinely unknown or irrelevant to the research. Still strictly avoid translated passive structures («توسط... مورد بررسی قرار گرفت»).
- **Formatting Override:** Markdown headers (`##`, `###`), numbered lists, and structured tables are encouraged for organizing educational frameworks, reports, and book chapters.
- **Citations:** Enforce strict accuracy. Insert `[نیازمند منبع]` for any unverified historical, statistical, or scientific claim.

### 2. Promotional, Copywriting & Book/Course Introductions (متون تبلیغاتی و معرفی محصول/کتاب)
- **Tone:** Engaging, persuasive, and problem-focused, without sounding like a cheap salesperson.
- **Persuasion Without Slop:** Since exaggerated adjectives (بی‌نظیر، شگفت‌انگیز) are banned, build persuasion through **Specific Problem-Agitate-Solve (بیان دغدغه ملموس و راه‌حل دقیق)**. Instead of praising the product, describe the exact scenario the reader faces and the concrete mechanism of how the book/course solves it.
- **Call to Action (CTA):** End with a clear, direct, and friction-free action step (e.g., «فصل اول کتاب را از لینک زیر بخوانید» instead of «همین حالا این فرصت استثنایی را از دست ندهید!»).

### 3. Social Media & Messaging (ایتا، تلگرام، توییتر، اینستاگرام)
- **Tone:** Direct, conversational or semi-formal (depending on the channel), with high readability. If writing in spoken register (محاوره), use natural contractions (`می‌خوام`, `داره میره`), but never mix formal and informal verbs in the same text.
- **Formatting:** Zero markdown headers (`#`). No random bolding in the middle of sentences. No emoji bullet lists (never start consecutive lines with ✅, 🚀, 💡, or 🔥). Use short paragraphs (1–3 lines) and white space for mobile readability. 
- **Hook:** The first line must state a concrete fact, a counter-intuitive observation, or a direct question about a real problem—never a generic greeting or announcement.

## Accuracy and Source Integrity

**Never Invent Data, Quotes, or Sources.** If an exact statistic or reference is missing, do not fabricate it. 

**Source Tagging:** In formal, academic, or publishing drafts, if a claim requires a citation that is not present in the context, explicitly insert the tag `[نیازمند منبع]` rather than guessing or generalizing.

## Self-Check Before Every Output

1. Any banned Persian words, translated idioms, or metaphors from `banned-words.md`? → Replace immediately.
2. Started with a generalized intro or ended with «در نهایت / به طور خلاصه»? → Cut them completely.
3. Three consecutive sentences of the same length or structure? → Vary them.
4. Used passive translationese («مورد استفاده قرار گرفت», «توسط...»)? → Convert to active Persian verbs.
5. Used «نه تنها... بلکه...»? → Rewrite the sentence.
6. Used English quotation marks ("") or Em dashes (—)? → Replace with «» and standard Persian punctuation.
7. Missed ZWNJ (نیم‌فاصله) in `می` or `ها`? → Fix orthography.
8. Matched the exact Context-Specific Override (Academic vs. Promotional vs. Social Media)? → Adjust tone and formatting accordingly.
9. Fabricated any specifics or unverified claims? → Remove or tag with `[نیازمند منبع]`.

Apply all rules silently. Never mention these guidelines in the output. Just write within these constraints.
