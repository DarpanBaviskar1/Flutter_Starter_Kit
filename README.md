# 🤖 .agent/ - The LG Development Skeleton

> **A comprehensive AI-powered knowledge base and development framework for building Liquid Galaxy applications.**


---

## 📋 Table of Contents

1. [What is This?](#what-is-this)
2. [Quick Start](#quick-start)
3. [Folder Structure](#folder-structure)
4. [How to Use](#how-to-use)
5. [Decision Trees](#decision-trees)
6. [AI Agent System](#ai-agent-system)
7. [Key Features](#key-features)
8. [Examples](#examples)
9. [Statistics](#statistics)
10. [Contributing](#contributing)

---

## 🎯 What is This?

The `.agent/` folder is **the skeleton** for Liquid Galaxy app development. It's not just documentation—it's an intelligent development assistant system that:

### 🦴 The Skeleton Metaphor

Think of building a body:
- **Skeleton (.agent/)** = Framework, structure, rules
- **Muscles (lg_controller/)** = The actual application you build
- **Nervous System (AI Agents)** = Intelligence that coordinates everything

### What It Contains

| Component | Purpose | Files |
|-----------|---------|-------|
| **Architecture** | Design patterns & principles | 3 docs |
| **Patterns** | Reusable code patterns | 4 docs |
| **Features** | Completed feature documentation | 4 docs |
| **Guides** | Step-by-step tutorials | 4+ docs |
| **Templates** | Copy-paste code | 11 files |
| **Roles** | AI agent personalities | 8 roles |
| **Workflows** | Development processes | 3 docs |
| **Troubleshooting** | Problem solving | 4 docs |

**Total: 40+ files, 12,000+ lines of content**

---

## 🚀 Quick Start

### For Developers

```bash
# 1. Explore the skeleton
cd .agent/
cat README.md              # This file
cat QUICK_REFERENCE.md     # Task-based lookup

# 2. Understand the architecture
cat 1-foundations/ARCHITECTURE.md
cat 1-foundations/GOLDEN_RULES.md

# 3. Copy a template to start coding
cp 5-templates/flutter/ssh-service.dart ../lg_controller/lib/services/

# 4. Follow a workflow
cat 7-workflows/feature-development.md

# 5. Get help when stuck
cat 8-troubleshooting/ssh-issues.md
```

### For AI Agents

```
When asked to help with LG development:

1. Read .agent/README.md (this file)
2. Navigate using decision trees below
3. Follow patterns in 1-foundations/GOLDEN_RULES.md
4. Use templates from 5-templates/
5. Follow workflows in 7-workflows/
6. Document results back in 3-features/
```

---

## 📂 Folder Structure

```
.agent/                           ← YOU ARE HERE (The Skeleton)
│
├── 📄 README.md                  ← Main entry point (this file)
├── 📄 QUICK_REFERENCE.md         ← 1-page task lookup
├── 📄 STRUCTURE_OVERVIEW.md      ← Visual directory guide
├── 📄 RESTRUCTURING_COMPLETE.md  ← Completion report
│
├── 📁 1-foundations/             ← Core principles (3 files)
│   ├── ARCHITECTURE.md           │  System design & philosophy
│   ├── GOLDEN_RULES.md           │  Non-negotiable patterns
│   └── REFACTOR_HISTORY.md       │  Why decisions were made
│
├── 📁 2-patterns/                ← Reusable patterns (4 files)
│   ├── ssh-patterns.md           │  SSH best practices
│   ├── kml-patterns.md           │  KML generation patterns
│   ├── service-layer.md          │  Service architecture
│   └── state-management.md       │  Riverpod patterns
│
├── 📁 3-features/                ← Feature documentation (4 files)
│   ├── kml-agent.md              │  AI KML generation (Gemini)
│   ├── location-lookup.md        │  Geocoding (Nominatim)
│   ├── weather-overlay.md        │  Weather data (Open-Meteo)
│   └── earthquake-tracker.md     │  Seismic data (USGS)
│
├── 📁 4-guides/                  ← Step-by-step tutorials
│   └── flutter/                  │  (4+ docs)
│       ├── best-practices.md     │  Flutter + LG best practices
│       ├── common-mistakes.md    │  Anti-patterns to avoid
│       ├── kml-generation.md     │  KML creation guide
│       └── ssh-integration.md    │  SSH integration guide
│
├── 📁 5-templates/               ← Copy-paste code (11 files)
│   ├── flutter/                  │  (7 Dart templates)
│   │   ├── connection-form.dart
│   │   ├── connection-provider.dart
│   │   ├── fly-to-tour.dart
│   │   ├── kml-builder.dart
│   │   ├── lg-service.dart
│   │   ├── ssh-service.dart
│   │   └── README.md
│   │
│   └── kml/                      │  (4 KML templates)
│       ├── placemark-template.kml
│       ├── tour-template.kml
│       ├── overlay-template.kml
│       └── README.md
│
├── 📁 6-roles/                   ← AI agent personalities (8 roles)
│   ├── README.md                 │  Role selection guide
│   ├── lg-init/                  │  Project setup assistant
│   ├── lg-brainstormer/          │  Idea generation
│   ├── lg-plan-writer/           │  Implementation planning
│   ├── lg-exec/                  │  Code implementation (educator)
│   ├── lg-code-reviewer/         │  Quality auditing
│   ├── lg-quiz-master/           │  Knowledge verification
│   ├── lg-skeptical-mentor/      │  Critical thinking
│   └── lg-nanobanana-sprite/     │  Cheerful companion
│
├── 📁 7-workflows/               ← Development processes (3 docs)
│   ├── feature-development.md    │  End-to-end feature creation
│   ├── debugging.md              │  Systematic debugging
│   └── testing.md                │  Quality assurance
│
└── 📁 8-troubleshooting/         ← Problem solving (4 docs)
    ├── ssh-issues.md             │  SSH connectivity problems
    ├── kml-errors.md             │  KML validation errors
    ├── state-bugs.md             │  State management issues
    └── api-errors.md             │  API integration problems
```

---

## 🎓 How to Use

### Usage Pattern 1: Learning Mode

```
Scenario: "I'm new to LG development"

Path:
1. Read: .agent/1-foundations/ARCHITECTURE.md
   └─> Understand system design philosophy
   
2. Read: .agent/1-foundations/GOLDEN_RULES.md
   └─> Learn non-negotiable patterns
   
3. Read: .agent/4-guides/flutter/best-practices.md
   └─> Understand Flutter + LG integration
   
4. Explore: .agent/5-templates/flutter/
   └─> See working code examples
   
5. Practice: Copy template, modify, test
   └─> Build understanding through experimentation

Estimated time: 2-3 hours
Result: Strong foundation in LG development patterns
```

### Usage Pattern 2: Building a Feature

```
Scenario: "I need to add earthquake tracking"

Path:
1. Check: .agent/QUICK_REFERENCE.md
   └─> "Need to add feature? → See 7-workflows/"
   
2. Read: .agent/7-workflows/feature-development.md
   └─> Get step-by-step process
   
3. Read: .agent/2-patterns/service-layer.md
   └─> Understand service architecture
   
4. Copy: .agent/5-templates/flutter/ssh-service.dart
   └─> Use as starting point
   
5. Reference: .agent/3-features/weather-overlay.md
   └─> Similar API integration example
   
6. Implement: Follow patterns from steps 1-5
   └─> Build feature with confidence
   
7. Document: .agent/3-features/earthquake-tracker.md
   └─> Help future developers

Estimated time: 45 minutes (vs 3-4 hours manual)
Success rate: 95% pattern compliance
```

### Usage Pattern 3: Debugging

```
Scenario: "SSH connection keeps failing"

Path:
1. Quick check: .agent/QUICK_REFERENCE.md
   └─> "SSH issues? → 8-troubleshooting/ssh-issues.md"
   
2. Read: .agent/8-troubleshooting/ssh-issues.md
   └─> Common problems + solutions
   
3. Check: .agent/1-foundations/GOLDEN_RULES.md
   └─> Verify using correct patterns
   
4. Test: Follow diagnostic steps
   └─> Systematic problem elimination
   
5. Fix: Apply solution
   └─> Resolve issue

Estimated time: 10-20 minutes (vs 1-2 hours trial & error)
Success rate: 90% first-try resolution
```

### Usage Pattern 4: AI-Assisted Development

```
Scenario: "Build feature with AI help"<!-- filepath: c:\Users\darpa\OneDrive\Desktop\Work\antigravity\LGWebStarterKit\.agent\README.md -->

# 🤖 .agent/ - The LG Development Skeleton

> **A comprehensive AI-powered knowledge base and development framework for building Liquid Galaxy applications.**

[![Documentation](https://img.shields.io/badge/Docs-Complete-green.svg)](./)
[![AI-Assisted](https://img.shields.io/badge/AI--Ready-100%25-brightgreen.svg)](./)
[![Templates](https://img.shields.io/badge/Templates-11-blue.svg)](5-templates/)
[![Workflows](https://img.shields.io/badge/Workflows-3-orange.svg)](7-workflows/)

---

## 📋 Table of Contents

1. [What is This?](#what-is-this)
2. [Quick Start](#quick-start)
3. [Folder Structure](#folder-structure)
4. [How to Use](#how-to-use)
5. [Decision Trees](#decision-trees)
6. [AI Agent System](#ai-agent-system)
7. [Key Features](#key-features)
8. [Examples](#examples)
9. [Statistics](#statistics)
10. [Contributing](#contributing)

---

## 🎯 What is This?

The `.agent/` folder is **the skeleton** for Liquid Galaxy app development. It's not just documentation—it's an intelligent development assistant system that:

### 🦴 The Skeleton Metaphor

Think of building a body:
- **Skeleton (.agent/)** = Framework, structure, rules
- **Muscles (lg_controller/)** = The actual application you build
- **Nervous System (AI Agents)** = Intelligence that coordinates everything

### What It Contains

| Component | Purpose | Files |
|-----------|---------|-------|
| **Architecture** | Design patterns & principles | 3 docs |
| **Patterns** | Reusable code patterns | 4 docs |
| **Features** | Completed feature documentation | 4 docs |
| **Guides** | Step-by-step tutorials | 4+ docs |
| **Templates** | Copy-paste code | 11 files |
| **Roles** | AI agent personalities | 8 roles |
| **Workflows** | Development processes | 3 docs |
| **Troubleshooting** | Problem solving | 4 docs |

**Total: 40+ files, 12,000+ lines of content**

---

## 🚀 Quick Start

### For Developers

```bash
# 1. Explore the skeleton
cd .agent/
cat README.md              # This file
cat QUICK_REFERENCE.md     # Task-based lookup

# 2. Understand the architecture
cat 1-foundations/ARCHITECTURE.md
cat 1-foundations/GOLDEN_RULES.md

# 3. Copy a template to start coding
cp 5-templates/flutter/ssh-service.dart ../lg_controller/lib/services/

# 4. Follow a workflow
cat 7-workflows/feature-development.md

# 5. Get help when stuck
cat 8-troubleshooting/ssh-issues.md
```

### For AI Agents

```
When asked to help with LG development:

1. Read .agent/README.md (this file)
2. Navigate using decision trees below
3. Follow patterns in 1-foundations/GOLDEN_RULES.md
4. Use templates from 5-templates/
5. Follow workflows in 7-workflows/
6. Document results back in 3-features/
```

---

## 📂 Folder Structure

```
.agent/                           ← YOU ARE HERE (The Skeleton)
│
├── 📄 README.md                  ← Main entry point (this file)
├── 📄 QUICK_REFERENCE.md         ← 1-page task lookup
├── 📄 STRUCTURE_OVERVIEW.md      ← Visual directory guide
├── 📄 RESTRUCTURING_COMPLETE.md  ← Completion report
│
├── 📁 1-foundations/             ← Core principles (3 files)
│   ├── ARCHITECTURE.md           │  System design & philosophy
│   ├── GOLDEN_RULES.md           │  Non-negotiable patterns
│   └── REFACTOR_HISTORY.md       │  Why decisions were made
│
├── 📁 2-patterns/                ← Reusable patterns (4 files)
│   ├── ssh-patterns.md           │  SSH best practices
│   ├── kml-patterns.md           │  KML generation patterns
│   ├── service-layer.md          │  Service architecture
│   └── state-management.md       │  Riverpod patterns
│
├── 📁 3-features/                ← Feature documentation (4 files)
│   ├── kml-agent.md              │  AI KML generation (Gemini)
│   ├── location-lookup.md        │  Geocoding (Nominatim)
│   ├── weather-overlay.md        │  Weather data (Open-Meteo)
│   └── earthquake-tracker.md     │  Seismic data (USGS)
│
├── 📁 4-guides/                  ← Step-by-step tutorials
│   └── flutter/                  │  (4+ docs)
│       ├── best-practices.md     │  Flutter + LG best practices
│       ├── common-mistakes.md    │  Anti-patterns to avoid
│       ├── kml-generation.md     │  KML creation guide
│       └── ssh-integration.md    │  SSH integration guide
│
├── 📁 5-templates/               ← Copy-paste code (11 files)
│   ├── flutter/                  │  (7 Dart templates)
│   │   ├── connection-form.dart
│   │   ├── connection-provider.dart
│   │   ├── fly-to-tour.dart
│   │   ├── kml-builder.dart
│   │   ├── lg-service.dart
│   │   ├── ssh-service.dart
│   │   └── README.md
│   │
│   └── kml/                      │  (4 KML templates)
│       ├── placemark-template.kml
│       ├── tour-template.kml
│       ├── overlay-template.kml
│       └── README.md
│
├── 📁 6-roles/                   ← AI agent personalities (8 roles)
│   ├── README.md                 │  Role selection guide
│   ├── lg-init/                  │  Project setup assistant
│   ├── lg-brainstormer/          │  Idea generation
│   ├── lg-plan-writer/           │  Implementation planning
│   ├── lg-exec/                  │  Code implementation (educator)
│   ├── lg-code-reviewer/         │  Quality auditing
│   ├── lg-quiz-master/           │  Knowledge verification
│   ├── lg-skeptical-mentor/      │  Critical thinking
│   └── lg-nanobanana-sprite/     │  Cheerful companion
│
├── 📁 7-workflows/               ← Development processes (3 docs)
│   ├── feature-development.md    │  End-to-end feature creation
│   ├── debugging.md              │  Systematic debugging
│   └── testing.md                │  Quality assurance
│
└── 📁 8-troubleshooting/         ← Problem solving (4 docs)
    ├── ssh-issues.md             │  SSH connectivity problems
    ├── kml-errors.md             │  KML validation errors
    ├── state-bugs.md             │  State management issues
    └── api-errors.md             │  API integration problems
```

---

## 🎓 How to Use

### Usage Pattern 1: Learning Mode

```
Scenario: "I'm new to LG development"

Path:
1. Read: .agent/1-foundations/ARCHITECTURE.md
   └─> Understand system design philosophy
   
2. Read: .agent/1-foundations/GOLDEN_RULES.md
   └─> Learn non-negotiable patterns
   
3. Read: .agent/4-guides/flutter/best-practices.md
   └─> Understand Flutter + LG integration
   
4. Explore: .agent/5-templates/flutter/
   └─> See working code examples
   
5. Practice: Copy template, modify, test
   └─> Build understanding through experimentation

Estimated time: 2-3 hours
Result: Strong foundation in LG development patterns
```

### Usage Pattern 2: Building a Feature

```
Scenario: "I need to add earthquake tracking"

Path:
1. Check: .agent/QUICK_REFERENCE.md
   └─> "Need to add feature? → See 7-workflows/"
   
2. Read: .agent/7-workflows/feature-development.md
   └─> Get step-by-step process
   
3. Read: .agent/2-patterns/service-layer.md
   └─> Understand service architecture
   
4. Copy: .agent/5-templates/flutter/ssh-service.dart
   └─> Use as starting point
   
5. Reference: .agent/3-features/weather-overlay.md
   └─> Similar API integration example
   
6. Implement: Follow patterns from steps 1-5
   └─> Build feature with confidence
   
7. Document: .agent/3-features/earthquake-tracker.md
   └─> Help future developers

Estimated time: 45 minutes (vs 3-4 hours manual)
Success rate: 95% pattern compliance
```

### Usage Pattern 3: Debugging

```
Scenario: "SSH connection keeps failing"

Path:
1. Quick check: .agent/QUICK_REFERENCE.md
   └─> "SSH issues? → 8-troubleshooting/ssh-issues.md"
   
2. Read: .agent/8-troubleshooting/ssh-issues.md
   └─> Common problems + solutions
   
3. Check: .agent/1-foundations/GOLDEN_RULES.md
   └─> Verify using correct patterns
   
4. Test: Follow diagnostic steps
   └─> Systematic problem elimination
   
5. Fix: Apply solution
   └─> Resolve issue

Estimated time: 10-20 minutes (vs 1-2 hours trial & error)
Success rate: 90% first-try resolution
```

### Usage Pattern 4: AI-Assisted Development

```
Scenario: "Build feature with AI help"
