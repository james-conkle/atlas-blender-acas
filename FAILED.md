# FAILED.md

## Failure Capture Protocol

### Goal Not Achieved — Failure Recorded

---

## Purpose

This document defines the **standard failure capture action** for a work session
that did **not** achieve its stated objective.

When execution diverges from intent or fails verification, invoking “failed” or
an equivalent phrase triggers the following output,
**in this exact order, with no omissions**:

1. **Name**
2. **Repository tree placement**
3. **File contents (observed state)**
4. **Commit message**
5. **Extended description**
6. **Closing thoughts (on and off the record)**

This protocol exists to **preserve signal**, prevent silent drift, and convert
failure into durable diagnostic data.

---

## Trigger Phrase

Executed when the user says, explicitly or implicitly:

* “failed”
* “this didn’t work”
* “that’s wrong”
* “stop”
* “abort”
* “this diverged”

---

## Required Output Structure (Mandatory)

### 1. Name

Provide the filename of the failure artifact.

---

### 2. Repository Tree Placement

Specify where the failure artifact should live.

---

### 3. Contents

Provide the **full observed-state report**, including:

* Original goal
* Observed reality
* Divergence point
* Actual step count
* Best-current root cause
* Recovery options

Presented as a complete, copy/paste-ready file.

---

### 4. Commit Message

Provide a **single-line**, imperative commit message.

---

### 5. Extended Description

Provide a commit / PR body explaining:

* What failed
* Where divergence occurred
* Why the data is valuable

---

### 6. Closing Thoughts (No Code Block)

#### On the record

* Why this qualifies as a failure
* What objective criteria were not met

#### Off the record

* Human reflection
* Pattern recognition
* Course correction acknowledgment

---

## Status

* **Outcome:** Failed
* **Data Preserved:** Yes
* **Retry Required:** Optional
* **Artifact Value:** Diagnostic

---

## Guiding Principle

> Failure is not the absence of progress.
> Failure is progress that has not yet been named.
