# ❤️ Care

### Smart Medication Adherence. Connected Families. Better Care.

**Care** is a smart family medication-adherence mobile application designed to bring parents and their children closer through technology.

The application helps parents remember their medications, supplements, painkillers, and other scheduled treatments while allowing their children to remotely follow their medication adherence, receive important alerts, exchange notes, and stay connected throughout the day.

> Technology should not replace family care — it should make it easier.

---

# 🎯 The Problem

Medication schedules can become difficult to manage, especially when a person needs to take several medications at different times throughout the day.

A simple alarm can remind someone that it is time to take medication, but it cannot answer important questions such as:

* Did the parent actually take the medication?
* Was the medication taken on time?
* How many scheduled doses were missed today?
* Is the parent consistently following the medication schedule?
* Should a family member be notified?
* Does the parent need another reminder?
* Is there an important instruction such as taking the medication after food?

At the same time, children may want to follow up with their parents without repeatedly calling them throughout the day.

**Care aims to solve both problems through one connected family platform.**

---

# 💡 The Idea

Care connects two main types of users:

### 👨‍👩‍🦳 Parent

The parent manages their medication schedule and receives smart reminders.

### 👨‍👦 Child / Family Member

The child can connect their account to the parent's account and remotely follow medication adherence and important medication events.

This creates a simple communication loop:

**Medication Schedule → Reminder → Parent Response → Adherence Tracking → Family Update**

---

# 💊 Medication Management

Parents can add their medications and supplements to Care.

Each medication can include information such as:

* Medication name
* Dosage
* Scheduled time
* Number of doses per day
* Repeat days
* Instructions
* Additional notes

Example:

```text
Medication: Concor
Dosage: 1 Tablet
Time: 8:00 PM
Repeat: Daily
Instruction: After food
```

Care then uses this schedule to automatically generate reminders.

---

# ⏰ Smart Medication Alarm

Care is more than a normal notification.

When it is time to take a medication, the parent receives an alarm-like reminder.

Example:

```text
💊 Medication Reminder

It is time to take your Concor.

8:00 PM
1 Tablet
```

The parent can respond directly:

```text
✅ I Took It

⏰ Remind Me in 5 Minutes
```

If the parent selects:

### ✅ I Took It

The dose is recorded as completed.

### ⏰ Remind Me in 5 Minutes

Care schedules another reminder after five minutes.

This creates an interactive medication reminder instead of a simple notification that can easily be ignored.

---

# 🔁 Recurring Medication Reminders

Medication schedules can repeat automatically.

For example:

```text
08:00 AM → Medication Reminder

02:00 PM → Medication Reminder

08:00 PM → Medication Reminder
```

If the medication must be taken every day, Care automatically repeats these reminders according to the parent's medication plan.

The user does not need to create a new alarm every day.

---

# ⚠️ Final Medication Reminder

Care can send an additional warning before the allowed medication period ends.

For example, if the medication should be taken before 9:00 PM and it has not yet been recorded:

```text
⚠️ Care Reminder

You still haven't recorded your medication.

30 minutes remaining before your scheduled medication window ends.
```

This gives the parent another opportunity to take the medication before the dose is considered missed.

---

# 👨‍👦 Parent & Child Account Connection

One of Care's main features is the connection between family accounts.

A child can securely connect their account to their parent's Care account.

Once connected, the child can view information such as:

* Today's medication schedule
* Medications already taken
* Remaining medications
* Missed doses
* Medication adherence score
* Medication history
* Important alerts

This makes Care a **family-connected health adherence system**, not only a medication reminder.

---

# 📡 Real-Time Family Monitoring

The child can follow the parent's medication progress throughout the day.

Example:

```text
Dad's Medication Progress

✅ Concor — Taken

✅ Vitamin D — Taken

❌ Glucophage — Missed

⏳ Aspirin — Upcoming
```

The child can quickly understand whether the parent is following the medication plan.

---

# 🚨 Missed Medication Alerts

If a scheduled medication time passes and the parent has not recorded the dose, Care can notify the connected child.

Example:

```text
⚠️ Care Alert

Dad's medication time has passed.

Medication: Glucophage
Scheduled Time: 2:00 PM

The medication has not been recorded yet.
```

This allows the child to check on their parent when it actually matters.

---

# 📊 Medication Adherence Score

Care tracks how consistently the parent follows the daily medication schedule.

For example:

```text
Scheduled Doses: 6

Taken: 5

Missed: 1
```

Care can calculate an adherence score such as:

```text
Today's Care Score

8.3 / 10
```

The score can consider factors such as:

* Number of medications scheduled
* Number of doses taken
* Missed doses
* Late doses
* On-time medication adherence

Example:

```text
Today

✅ 5 doses completed
❌ 1 dose missed

Adherence Score: 8.3 / 10
```

---

# 📈 Medication Progress

Both the parent and the connected child can follow medication adherence.

For example:

```text
Today's Progress

Taken          5
Remaining      1
Missed         1

Adherence      83%
```

Future versions of Care can also provide:

* Daily reports
* Weekly reports
* Monthly adherence statistics
* Medication history
* Adherence trends

---

# 📝 Shared Family Notes

Care also provides simple communication between the parent and child.

A child can attach an instruction or reminder to a medication.

Example:

```text
Ahmed's Note ❤️

Dad, remember to eat before taking this medication.
```

The parent can also leave messages for the child.

Example:

```text
Dad:

I took my medication. Don't worry ❤️
```

This transforms Care from only a medication tracker into a lightweight family care communication platform.

---

# 💙 Family Connection Reminders

Care is not only about medication.

The application can occasionally remind family members to stay connected.

Example:

```text
💙 Care Reminder

It has been a while.

Why not check on Dad today?
```

Or:

```text
❤️ Stay Connected

A small call can make someone's day.

Call your parent.
```

The goal is to use technology to **encourage human connection rather than replace it.**

---

# 🔔 Notification System

Care will use multiple types of notifications.

### Medication Reminder

Sent to the parent when it is time to take medication.

### Snooze Reminder

Sent again when the parent chooses:

```text
Remind Me in 5 Minutes
```

### Final Reminder

Sent when the medication window is close to ending.

### Missed Medication Alert

Sent to the connected child when a parent misses a medication.

### Medication Status Update

A child may receive an update when a medication is successfully recorded.

Example:

```text
✅ Dad took his medication.
```

### Family Connection Reminder

Encourages family members to call or check on each other.

---

# 🔄 Example User Flow

```text
Parent Creates Account
        ↓
Parent Adds Medication
        ↓
Medication Schedule Saved
        ↓
Child Creates Account
        ↓
Child Connects to Parent
        ↓
Child Adds Medication Note
        ↓
Scheduled Medication Time Arrives
        ↓
Parent Receives Alarm
        ↓
     ┌──────────────┐
     │              │
I Took It      Remind Me
     │          in 5 Minutes
     ↓              ↓
Dose Recorded   New Reminder
     │
     ↓
Adherence Updated
     │
     ↓
Child Can View Status
```

If the parent does not take the medication:

```text
Medication Time
      ↓
No Response
      ↓
Reminder
      ↓
Final Reminder
      ↓
Still No Response
      ↓
Dose Marked Late / Missed
      ↓
Child Receives Alert
      ↓
Adherence Score Updated
```

---

# 🏗️ Planned Technology Stack

Care is planned as a cross-platform mobile application.

### Mobile Application

**Flutter**

Used to build Android and iOS applications from a single codebase.

### Programming Language

**Dart**

### Authentication

**Firebase Authentication**

Used for secure Parent and Child accounts.

### Cloud Database

**Cloud Firestore**

Used to store and synchronize:

* Users
* Medication schedules
* Family connections
* Medication status
* Shared notes
* Adherence information

### Notifications

**Firebase Cloud Messaging — FCM**

Used for medication reminders and family alerts.

### Backend Logic

**Firebase Cloud Functions**

Can be used for server-side operations such as:

* Scheduled medication checks
* Missed-dose detection
* Child notifications
* Adherence calculations
* Daily reports

---

# 🗃️ Planned Core Data

The initial Care system will contain four main data areas:

```text
Users

Medicines

Family Connections

Notes
```

As the project grows, additional modules can be added for:

```text
Medication Logs

Notifications

Adherence Scores

Daily Reports

Medication History
```

---

# 🚀 Development Roadmap

## Milestone 1 — Connected Medication Scheduling

The first milestone focuses on building the foundation of Care.

### Features

* Parent account registration
* Child account registration
* Parent and Child user roles
* Add medication
* Set medication schedule
* Parent–Child account connection
* Child can view parent's medications
* Child can leave medication notes
* Medication-time notification for the parent
* Medication-time notification for the connected child

---

## Milestone 2 — Medication Tracking

The second milestone introduces medication interaction and tracking.

### Features

* **I Took It** action
* **Remind Me in 5 Minutes**
* Medication completion tracking
* Late medication detection
* Missed medication detection
* Child missed-dose alerts
* Medication history

---

## Milestone 3 — Smart Adherence

The third milestone introduces analytics and adherence monitoring.

### Features

* Daily adherence score
* Medication completion percentage
* Daily report
* Weekly report
* Medication adherence history
* Child monitoring dashboard
* Late-dose analysis

---

## Milestone 4 — Family Care Experience

Future versions can expand Care beyond medication management.

### Planned Features

* Family connection reminders
* Smart care notifications
* Shared family messages
* Advanced adherence analytics
* Multiple children connected to one parent
* Multiple parents connected to one child
* Emergency contact options
* Caregiver accounts

---

# 🌟 Project Vision

Care is built around one simple idea:

> **Use technology to bring families closer while helping loved ones stay consistent with their medication.**

Instead of creating another basic medication alarm, Care aims to build a connected family experience where medication adherence, communication, reminders, and family support work together.

---

# ⚕️ Important Note

Care is intended to support medication reminders, organization, and family communication.

It is **not a replacement for professional medical advice, diagnosis, treatment, or emergency medical services.**

Users should always follow instructions provided by qualified healthcare professionals.

---

# ❤️ Care

### Medication remembered. Family connected. Care delivered.

**Built to make technology feel more human.**
