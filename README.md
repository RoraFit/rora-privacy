# Rora Privacy Policy

**Last updated: 13 September 2026**

Rora is a personal training app. It builds you a workout plan from what you tell
it about yourself, adjusts that plan as you train, and lets you talk to an AI
trainer about it.

This policy explains exactly what Rora collects, where it goes, and how to get
rid of it. It is written to be read, not skimmed past.

---

## 1. Who we are

Rora is operated by Mac Costin.

Questions, requests, or complaints: **maccostin23@outlook.com**

---

## 2. What Rora collects

Rora only collects what you type into it. There is **no analytics SDK, no
advertising SDK, and no third-party tracking of any kind** in the app. Rora does
not track you across other apps or websites, and does not build an advertising
profile.

### Account

- Email address and password (the password is handled by our authentication
  provider and is never visible to us)

### Your fitness profile

You provide this during onboarding and can change it any time under
Profile → Edit My Info:

- First name, age, gender
- Height, weight, current and goal body-fat percentage
- Occupation, average sleep, self-reported stress level
- Training experience, years training, past or current sport and level
- Goals, target timelines, any event you are training for
- Diet notes
- Equipment access and where you train
- Preferred training days, times, session length, and workout styles
- Hobbies and other sports

### Health information

Two fields specifically ask about your health, and you can leave both blank:

- **Injuries or physical limitations** (free text)
- **Medical conditions or clearance concerns** (a yes/no flag and free text)

We treat these as sensitive. They exist so the plan can work around them. See
section 3 — they are sent to our AI provider along with the rest of your
profile, because a plan that ignores your injuries is worse than no plan.

### Training activity

- Which exercises you marked complete, and when
- Weights you entered
- How a workout felt ("too easy" / "just right" / "too hard")
- Activities you logged outside the plan, in your own words

### Conversations

- Everything you send your AI trainer, and everything it replies
- Feedback you submit through Profile → Send Feedback

### Device

- A push notification token, if you allow notifications
- Your timezone, so reminders arrive at a sensible local hour

### Voice input

If you use the microphone button, your speech is converted to text by **your
device's own operating system** (Apple's or Google's speech recognition). Rora
receives only the resulting text. Depending on your device settings, your
operating system may process that audio on-device or on its own servers, under
its own privacy policy — not ours. Rora never stores audio.

---

## 3. Who your data is shared with

Rora does not sell your data and does not share it for advertising. It is shared
with exactly three providers, each doing a specific job:

### Supabase — storage and accounts

Hosts the database and handles sign-in. Everything in section 2 is stored there.
**Data is stored in the United States (Oregon).** If you are outside the US,
this means your data is transferred to and held in the US.

### Anthropic — the AI trainer

**This is the sharing most worth understanding.** To write and adjust your plan,
and to answer you in chat, Rora sends Anthropic:

- your fitness profile, **including your injury and medical notes**
- your recent training history and how workouts felt
- your chat messages

This happens on our servers, not from your device. It is required for the app's
core function: the plan is written by that model, from that information.

Anthropic processes this to generate the response and, under its commercial
terms, does not use it to train its models.

### Expo — notifications and updates

Delivers push notifications (which means it handles your device token and the
notification text) and delivers app updates.

### Legal

We will disclose data if we are legally required to.

---

## 4. Why Rora is allowed to hold this

We process your data because you asked us to provide the service, and you
agreed to the Terms of Use when you signed up. For the health information in
section 2, we rely on **your explicit consent**, which you give by choosing to
type it in. You can withdraw that consent by clearing those fields.

---

## 5. How long it is kept

Your data stays until you delete your account. Chat history, plans, and
completion logs are kept for as long as the account exists, because the app uses
your history to write your next block of training.

---

## 6. Deleting your account

**Account deletion is handled manually right now.** There is no button in the
app that deletes your account by itself, and we would rather say so than imply
otherwise.

To delete your account, email **maccostin23@outlook.com** from the address you
signed up with. Tapping Profile → Delete Account in the app shows you the same
instruction. Please allow a few days; we will confirm by email once it is done,
and in any case we will complete the request within 30 days.

Deleting your account removes your profile, plans, workout history, and chat
history. Some records may persist briefly in encrypted backups before being
overwritten on our providers' normal cycles.

---

## 7. Your rights

Depending on where you live, you can ask us to give you a copy of your data,
correct it, delete it, or restrict what we do with it. Most of this you can do
yourself in the app; for anything else, email the address in section 1.

If you are in the UK or EU and think we have handled your data badly, you can
complain to your national data protection authority.

---

## 8. Children

Rora is not intended for children. **Do not create an account if you are under
16.** We apply the same age floor everywhere rather than varying it by country.

---

## 9. Security

Data is encrypted in transit. Access to the production database is restricted,
and per-user access rules mean one account cannot read another's data.

No system is perfectly secure, and we will not pretend otherwise.

---

## 10. Rora is not medical advice

Rora generates training plans using AI. It is not a doctor, a physiotherapist,
or a substitute for either. It can be wrong. Talk to a qualified professional
before starting a new training programme, especially if you flagged a medical
condition. This mirrors the Acknowledgment of Risk you accepted in the app.

---

## 11. Changes

If this policy changes materially, we will update the date at the top and notify
you in the app before the change takes effect.
