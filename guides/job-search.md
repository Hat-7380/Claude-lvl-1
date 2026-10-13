# 💼 Job search

Job hunting is stressful. Claude can make the writing parts faster and help you practice for the scary parts.

> **Golden rule:** never let Claude invent experience, skills, or numbers you don't have. It makes things sound good, but **everything on your CV must be true.**

## 1. Improve your CV

```
Here's my CV. I'm applying for junior marketing roles.
Review it like a recruiter who has 30 seconds per CV.
What would make you stop reading? What should I change first?

"""
[paste your CV text]
"""
```

Then fix specific parts:

```
Rewrite my job descriptions so they focus on results, not duties.
Use strong action verbs. Only use facts I gave you. If a bullet
would be better with a number, ask me for the number instead of
making one up.
```

The last sentence is important. It stops Claude from inventing "increased sales by 40%".

## 2. Tailor your CV to a job

```
Here's a job posting and my CV. Which of my experiences match
best? What keywords from the posting am I missing? Suggest
changes to make my CV a better fit, without adding anything untrue.

JOB POSTING:
"""
[paste]
"""

MY CV:
"""
[paste]
"""
```

## 3. Write a cover letter

```
Write a cover letter for this job using my CV. Keep it under
250 words. Sound like a real person, not a template. Mention
one specific thing about the company that I'll fill in myself.
Don't use clichés like "I am writing to express my interest".
```

Then make it yours: add the real detail about the company, and change any sentence that doesn't sound like you.

## 4. Practice interviews

This is one of the best uses of Claude.

```
Act as an interviewer for a [job title] position at a
[type of company]. Ask me one question at a time, like a real
interview. After each answer, give me short feedback: what was
good, and how to make it stronger. Start with "Tell me about yourself."
```

Try variations:
- `Now ask me the hardest questions you can think of.`
- `Ask me technical questions for this role.`
- `Ask me questions in English and correct my grammar too.`

💡 Use the **phone app with voice mode** and answer out loud. It feels much more like the real thing.

## 5. Prepare great answers

```
Help me prepare an answer to "What's your biggest weakness?"
Here's something real I struggle with: [be honest].
Make it honest but positive, and under 1 minute when spoken.
```

Other ones to prepare: *Why do you want this job? Why are you leaving your current job? Tell me about a time you failed. Where do you see yourself in 5 years?*

## 6. Research the company

```
I have an interview at [company]. What should I find out about
them before the interview? Give me 5 smart questions I could
ask the interviewer at the end.
```

⚠️ Claude may not have up-to-date info about the company. Check their website and recent news yourself.

## 7. After the interview

- `Write a short thank-you email to the interviewer. We talked about [topic].`
- `I got rejected. Write a polite reply asking for feedback.`
- `I got two offers. Help me compare them.` (See [Planning: make a decision](planning-and-organizing.md#6-make-a-decision))
- `Help me negotiate a higher salary. Here's the offer and my situation.`

---

**Prompts for this:** [Work prompts →](../prompts/work.md)

← [Back to Guides](README.md)
