# eceWire — Interactive Study Platform

Live Site: https://ecewire.github.io/

---

## What This Project Is

eceWire is a full interactive learning system that combines structured lessons, quizzes, and practice systems into a unified study platform.

It is not a simple website , it is a custom-built learning engine inspired by Khan Academy and Duolingo-style navigation.

---

## Core System

### Courses

The platform currently includes 3 main courses:

- Pre-Algebra  
- Honors Geometry  
- Arduino Programming  

Each course contains:
- Units  
- Skills  
- Lesson content (LESSONS object system)  
- Practice questions (Q bank system)  

---

## Curriculum Breakdown

### Pre-Algebra

| Unit | Lesson | Practice Questions |
|------|--------|------------------|
| Integers | What are integers? | No |
| Integers | Compare and order integers | No |
| Integers | Add and subtract integers | No |
| Integers | Multiply and divide integers | No |
| Integers | Absolute value | No |
| Integers | Order of operations | No |
| Integers | Word problems | No |

| Unit | Lesson | Practice Questions |
|------|--------|------------------|
| Fractions | Equivalent fractions | No |
| Fractions | Add/subtract fractions | No |
| Fractions | Multiply/divide fractions | No |
| Fractions | Mixed numbers | No |
| Fractions | Fractions ↔ decimals ↔ percents | No |

| Unit | Lesson | Practice Questions |
|------|--------|------------------|
| Ratios | Ratios and unit rates | No |
| Ratios | Proportions | No |
| Ratios | Scale drawings | No |
| Ratios | Similar figures | No |

| Unit | Lesson | Practice Questions |
|------|--------|------------------|
| Percents | Percent basics | No |
| Percents | Percent of a number | No |
| Percents | Increase/decrease | No |
| Percents | Simple interest | No |
| Percents | Tax/discount/tip | No |

Some lessons include embedded quizzes like `lq-*` blocks inside lesson content.

---

### Geometry

| Unit | Lesson | Practice Questions |
|------|--------|------------------|
| Area and Volume | Area of shapes | No |
| Area and Volume | Circles | No |
| Area and Volume | Surface area | No |
| Area and Volume | Volume of solids | No |

| Unit | Lesson | Practice Questions |
|------|--------|------------------|
| Angles | Types of angles | No |
| Angles | Triangle angle sum | No |
| Angles | Quadrilaterals | No |
| Angles | Pythagorean theorem | No |

| Unit | Lesson | Practice Questions |
|------|--------|------------------|
| Transformations | Translations | No |
| Transformations | Reflections | No |

| Unit | Lesson | Practice Questions |
|------|--------|------------------|
| Similarity | Similar figures | No |
| Similarity | AA / SAS / SSS proofs | No |

Some lessons include mini embedded quizzes (for example `lq-pn1`, `lq-fp1`, `lq-g113`).

---

### Arduino Course

- Structure defined  
- No full lesson content implemented yet  
- No practice system connected yet

Things that are NOT listed on here have full lessons AND practice problems :)

---

## Quiz System

### 1. Inline Lesson Quizzes (Embedded)

Examples:
- `lq-pn1`
- `lq-fp1`
- `lq-g113`

Features:
- Inside lesson content  
- Multiple choice format  
- Immediate feedback  
- Hardcoded per lesson  

---

### 2. Practice Engine (Separate System)

Defined using:

- `q: [...]`
- `ans:`
- `exp:`

Used for:
- Geometry practice sets  
- Mixed question banks  
- Auto-graded responses  

---

## System Architecture Insight

The platform is split into two systems:

### Not Fully Unified
- Lessons system  
- Practice system  
- Embedded quizzes  

### Working Components
- Lesson renderer  
- Course navigation system  
- Embedded quiz blocks  
- Geometry question banks  

---

## Key Features

### Core Features
- Multi-course structure  
- Expandable units and skills  
- Lesson rendering engine  
- Practice question system  
- Embedded quiz support  
- Partial progress tracking  

### UI Features
- Duolingo-style navigation  
- Animated lesson cards  
- Sticky UI elements  
- Dark theme support  
- Mobile responsive layout  

### Learning Features
- Step-by-step explanations  
- Worked examples  
- Check-your-understanding questions  
- Concept reinforcement  

---

## Summary

eceWire is a hybrid Khan Academy + Duolingo-style interactive learning platform with modular lessons, embedded quizzes, and a growing practice engine system.


Basically. all lessons are there, only thing needed to be added would be some more practice problems :)
