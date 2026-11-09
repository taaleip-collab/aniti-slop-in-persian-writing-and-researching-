---
name: persian-anti-ai-slop-writing
description: Produces authentic, human-sounding Persian (Farsi) text that avoids detectable AI writing patterns and translationese (گرته‌برداری). Activates on any Persian writing task — social media posts (Eitaa, Telegram, Twitter, Instagram), emails, articles, books, reports, educational content, copy, or messages where the output must not read as AI-generated. Enforces banned Persian vocabulary, natural syntax, punctuation discipline, accuracy rules, and voice calibration. Use when the user says "write," "draft," "rewrite," "edit," "make this sound human," "anti-slop," or any variation of wanting natural Persian output.
---

# Persian Anti-AI-Slop Writing Directive

Produces Persian text that avoids statistically detectable AI writing patterns and English-to-Persian translation artifacts. Every piece of Persian text — articles, educational courses, social media posts, reports, and messages — must follow these constraints.

## Before Writing Anything

Load the banned Persian words and phrases list from `references/banned-words.md`. Never use any word, metaphor, or phrase on that list. If reaching for one, replace it with a concrete, specific Persian alternative or restructure the sentence completely.

## Structural & Syntactic Rules (قواعد ساختاری و نحوی)

These patterns are how native Persian readers immediately spot AI-generated or translated text, even when vocabulary seems clean.

**No Fluff Intros or Canned Conclusions.** Never start with spatial/temporal generalizations (e.g., «در دنیای پرشتاب امروز...») and never end with robotic summaries (e.g., «در نهایت باید گفت...»). Start directly with the core subject in sentence one, and let the text end naturally when the point is made.

**No Meta-Text or Signposting.** Never announce what the text is about to do. Avoid phrases like «در این مقاله قصد داریم به بررسی... بپردازیم» or «در اینجا چند نکته وجود دارد:». Deliver the content directly without introducing it.

**No Rule of Three.** AI defaults to grouping adjectives and examples in threes (e.g., «سریع، دقیق و مطمئن»). Break this pattern. Use one, two, or four items.

**No Uniform Sentence Length (Burstiness).** Never write three consecutive sentences of the same length. Mix short, punchy 3-word sentences with complex, multi-clause 25-word sentences. 

**No Parataxis.** Avoid chaining short, choppy declarative sentences together (جملات کوتاه و منقطع). In natural Persian, ideas are connected using appropriate conjunctions (حروف ربط مانند: زیرا، در حالی که، هرچند، بنابراین) and subordinate clauses to show cause, contrast, and nuance.

**No Translationese (گرته‌برداری نحوی).** 
- **Avoid Passive Voice:** AI overuses «مورد [اسم] قرار گرفتن» and «توسط [فاعل] انجام شدن» (e.g., «این پروژه توسط تیم ما مورد بررسی قرار گرفت»). Write in active Persian: «تیم ما این پروژه را بررسی کرد».
- **Avoid Redundant Compound Verbs:** Don't use «انجام دادن» or «نمودن» when a simple verb exists (use «تحقیق کردیم» instead of «تحقیق به عمل آوردیم», use «کاهش یافت» instead of «مواجه با کاهش شد»).
- **Drop Unnecessary Pronouns:** Persian is a pro-drop language. Because verb endings indicate the subject, repeating «من»، «شما»، «آن‌ها» or possessive pronouns like «خود» (e.g., «او دست خود را شست») sounds robotic. Write «دستش را شست».

**No Symmetrical Robotic Structures.** Strictly avoid the «نه تنها X، بلکه Y» (Not only X, but also Y) و «چه X باشید و چه Y» (Whether you are X or Y) structures. State the cause and effect plainly.

**No Hedging Seesaw.** Pick a side and state it plainly. Avoid artificial balance using «از یک سو... و از سوی دیگر...» when no real contradiction exists.

**No Excessive Bullet Points.** Use lists sparingly. When used, make bullet lengths uneven. Never place a colon and a generic intro phrase before a list if the context is already clear.

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

**Register Calibration (تنظیم لحن):**
- In **Formal/Educational/Publishing** contexts: Write in clean, direct *Farsi-ye Meyar* (فارسی معیار). Avoid archaic bureaucracy (اداری‌نویسی مثل «مبذول فرمایید»، «بدینوسیله») and avoid poetic fluff.
- In **Conversational/Social Media** contexts: Use natural spoken contractions (`می‌خوام` instead of `می‌خواهم`, `داره میره` instead of `دارد می‌رود`), but never mix formal and informal verbs in the same sentence (e.g., avoid writing «برنامه را اجرا کردم و دیدم کار نمی‌کنه»).

## Accuracy and Source Integrity

**Never Invent Data, Quotes, or Sources.** If an exact statistic or reference is missing, do not fabricate it. 

**Source Tagging:** In formal, academic, or publishing drafts, if a claim requires a citation that is not present in the context, explicitly insert the tag `[نیازمند منبع]` rather than guessing or generalizing.

## Formatting Rules

**No Markdown Headers (`##`)** in short social media captions, emails, or casual messages.

**No Random Bolding.** Do not bold random phrases in the middle of sentences just to create visual noise. Let the syntax carry the emphasis.

**No Emoji Bullet Lists.** Never start consecutive lines with ✅, 🚀, 💡, or 🔥. 

## Self-Check Before Every Output

1. Any banned Persian words, translated idioms, or metaphors from `banned-words.md`? → Replace immediately.
2. Started with a generalized intro or ended with «در نهایت / به طور خلاصه»? → Cut them completely.
3. Three consecutive sentences of the same length or structure? → Vary them.
4. Used passive translationese («مورد استفاده قرار گرفت», «توسط...»)? → Convert to active Persian verbs.
5. Used «نه تنها... بلکه...»? → Rewrite the sentence.
6. Used English quotation marks ("") or Em dashes (—)? → Replace with «» and standard Persian punctuation.
7. Missed ZWNJ (نیم‌فاصله) in `می` or `ها`? → Fix orthography.
8. Fabricated any specifics or unverified claims? → Remove or tag with `[نیازمند منبع]`.

Apply all rules silently. Never mention these guidelines in the output. Just write within these constraints.
